---
layout: app

permalink: /Slothy/
description: Changes your Slack status based on the SSID you’re currently connected to.
license: MIT

icons:
  - Slothy/icons/128x128/slothy.png

screenshots:
  - Slothy/screenshot.png

authors:
  - name: kirbo
    url: https://github.com/kirbo

links:
  - type: GitHub
    url: kirbo/slothy
  - type: Download
    url: https://github.com/kirbo/slothy/releases

desktop:
  Desktop Entry:
    Name: Slothy
    Comment: Changes your Slack status based on the SSID you’re currently connected
      to.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: slothy
    StartupWMClass: Slothy
    X-AppImage-Version: 0.1.4
    MimeType: x-scheme-handler/slothy
    Categories: Utility
    X-AppImage-BuildId: 1K9I6ww3i8th3nnNajV15RK28t0
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64
    X-AppImage-Payload-License: MIT

electron:
    to.
  productName: Slothy
  productUrl: https://github.com/kirbo/slothy/releases
  repository: https://github.com/kirbo/slothy
  product:
    GitLabRepository: https://gitlab.com/kirbo/slothy
    GitHubRepository: https://github.com/kirbo/slothy
    Pages: https://kirbo.gitlab.io/slothy/
    Slack: https://join.slack.com/t/slothy-app/shared_invite/enQtNjE1NTcxMzY1MTU4LTcyMzhhZmMwNzdlMjkwZTQ4NzNkYjc3NWI0NWY5YWVjNDg3NTg5MTlhNGQ2ZGQ4NDZjMGMxM2YxNGQxOTBhOTc
    ClientId: '613360590693.615573455494'
    Protocol: slothy
  author: Kirbo (https://gitlab.com/kirbo)
  private: true
  main: build/electron.js
  homepage: "./"
  jest:
    bail: false
    collectCoverage: true
    forceExit: true
    collectCoverageFrom:
    - "/src/**.js"
    coverageDirectory: coverage
    coveragePathIgnorePatterns:
    - "/src/setupTests.js"
    - "/pages/"
    coverageReporters:
    - text
    - html
    notify: true
    testMatch:
    - "/src/**.test.js"
    testPathIgnorePatterns:
    - "/node_modules/"
    - "/pages/"
  dependencies:
    "@fortawesome/fontawesome-svg-core": 1.2.17
    "@fortawesome/free-brands-svg-icons": 5.8.1
    "@fortawesome/free-regular-svg-icons": 5.8.1
    "@fortawesome/free-solid-svg-icons": 5.8.1
    "@fortawesome/react-fontawesome": 0.1.4
    antd: 3.16.3
    axios: 0.18.0
    babel-plugin-import: 1.11.0
    copy-webpack-plugin: 5.0.2
    cross-env: 5.2.0
    customize-cra: 0.2.12
    dotenv: 7.0.0
    electron-json-storage: 4.1.6
    electron-log: 3.0.5
    electron-logger: 0.0.3
    electron-updater: 4.0.6
    less: 3.9.0
    less-loader: 4.1.0
    node-emoji: 1.10.0
    node-wifi: https://github.com/kirbo/node-wifi#testing
    nodemon: 1.18.11
    react: 16.8.6
    react-app-rewired: 2.1.1
    react-axe: 3.1.0
    react-dom: 16.8.6
    react-scripts: 2.1.8
    request: 2.88.0
    slack: 11.0.2
    styled-components: 4.2.0
    uuid: 3.3.2
---
