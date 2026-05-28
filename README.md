# dav4android

<!-- OSPO-managed README | Generated: 2026-04-16 | v2 -->

[![License](https://img.shields.io/badge/License-MPL--2.0-blue.svg)](LICENSE) [![ownCloud OSPO](https://img.shields.io/badge/OSPO-ownCloud-blue)](https://kiteworks.com/opensource)

dav4android is an Android library for WebDAV, CalDAV, and CardDAV protocol support. Originally developed for [DAVdroid](https://www.davdroid.com) (now DAVx5) by bitfire, this fork is used by the ownCloud Android app to communicate with ownCloud servers using standard DAV protocols. The library handles XML parsing, property management, and HTTP communication required for DAV operations.

> **Note:** This repository is in maintenance/legacy mode and is no longer actively developed.

## Part of Mobile (Android)

This library is a dependency of the [ownCloud Android app](https://github.com/owncloud/android), providing the DAV protocol layer for server communication. The original repository is maintained at [bitfireAT/dav4android on GitLab](https://gitlab.com/bitfireAT/dav4android/).

> **Note:** This repository is currently in Archived/Legacy mode. It is an ownCloud-specific fork of the upstream bitfire project.

## Getting Started

Follow the steps below to build the library and run its tests.

### Building

```bash
./gradlew build
```

### Running Tests

```bash
./run-tests.sh
```

## Documentation

- [Generated KDoc](https://bitfireAT.gitlab.io/dav4android/dokka/dav4android/)
- [Original repository (bitfire)](https://gitlab.com/bitfireAT/dav4android/)
- [DAVdroid/DAVx5](https://www.davdroid.com)

## Community & Support

**[Star](https://github.com/owncloud/dav4android)** this repo and **Watch** for release notifications!

- [ownCloud Website](https://owncloud.com)
- [Community Discussions](https://github.com/orgs/owncloud/discussions)
- [Matrix Chat](https://app.element.io/#/room/#owncloud:matrix.org)
- [Documentation](https://doc.owncloud.com)
- [Enterprise Support](https://owncloud.com/contact-us/)
- [OSPO Home](https://kiteworks.com/opensource)

## Contributing

We welcome contributions! Please read the [Contributing Guidelines](CONTRIBUTING.md)
and our [Code of Conduct](CODE_OF_CONDUCT.md) before getting started.

### Workflow

- **Rebase Early, Rebase Often!** We use a rebase workflow. Always rebase on the target branch before submitting a PR.
- **Dependabot**: Automated dependency updates are managed via Dependabot. Review and merge dependency PRs promptly.
- **Signed Commits**: All commits **must** be PGP/GPG signed. See [GitHub's signing guide](https://docs.github.com/en/authentication/managing-commit-signature-verification).
- **DCO Sign-off**: Every commit must carry a `Signed-off-by` line:
  ```
  git commit -s -S -m "your commit message"
  ```
- **GitHub Actions Policy**: Workflows may only use actions that are (a) owned by `owncloud`, (b) created by GitHub (`actions/*`), or (c) verified in the GitHub Marketplace.

## Security

**Do not open a public GitHub issue for security vulnerabilities.**

Report vulnerabilities at **<https://security.owncloud.com>** -- see [SECURITY.md](SECURITY.md).

Bug bounty: [YesWeHack ownCloud Program](https://yeswehack.com/programs/owncloud-bug-bounty-program)

## License

This project is licensed under the [MPL-2.0](LICENSE).

## About the ownCloud OSPO

The [Kiteworks Open Source Program Office](https://kiteworks.com/opensource), operating under
the [ownCloud](https://owncloud.com) brand, launched on May 5, 2026, to steward the open source
ecosystem around ownCloud's products. The OSPO ensures transparent governance, license compliance,
community health, and sustainable collaboration between the open source community and
[Kiteworks](https://www.kiteworks.com), which acquired ownCloud in 2023.

- **OSPO Home**: <https://kiteworks.com/opensource>
- **GitHub**: <https://github.com/owncloud>
- **ownCloud**: <https://owncloud.com>

For questions about the OSPO or licensing, contact ospo@kiteworks.com.

### License Migration to Apache 2.0

The OSPO is driving a strategic relicensing of ownCloud repositories toward the
[Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0), following
the [Apache Software Foundation's third-party license policy](https://www.apache.org/legal/resolved.html).

Individual repositories will migrate as their audit is completed. The LICENSE file
in each repo reflects its **current** license status (not the target).

**Current license: MPL-2.0** (Category B per Apache policy -- weak copyleft, may be included with care).

Migration prerequisites for this repository:

- **CLA/DCO coverage**: All past contributors must have signed agreements permitting relicensing
- **File-level analysis**: MPL-2.0 is a file-level copyleft; each source file's license must be assessed
- **Header updates**: All source file headers must be updated from MPL-2.0 to Apache-2.0 notice
- **Dependency audit**: Verify no Category X dependencies
