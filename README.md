# EDGE - shawly's Hass.io Add-ons

![Project Stage][project-stage-shield]
![Maintenance][maintenance-shield]
[![License][license-shield]](LICENSE.md)

[![GitLab CI][gitlabci-shield]][gitlabci]

## WARNING! THIS IS AN EDGE REPOSITORY

This Home Assistant Add-ons repository contains edge builds of add-ons. Edge
builds add-ons are based upon the latest development version.

- They may not work at all.
- They might stop working at any time.
- They could have a negative impact on your system.

This repository was created for:

- Anybody willing to test.
- Anybody interested in trying out upcoming add-ons or add-on features.
- Developers.

If you are more interested in stable releases of our add-ons:

<https://github.com/shawly/hassio-addons>

## Installation

Adding this add-ons repository to your Home Assistant instance is
pretty straightforward. In the Home Assistant add-on store,
a possibility to add a repository is provided.

Use the following URL to add this repository:

```txt
https://github.com/shawly/hassio-addons-dev
```

## Add-ons provided by this repository

### &#10003; [API Scapegoat][addon-apiscapegoat]

![Latest Version][apiscapegoat-version-shield]
![Supports armhf Architecture][apiscapegoat-armhf-shield]
![Supports armv7 Architecture][apiscapegoat-armv7-shield]
![Supports aarch64 Architecture][apiscapegoat-aarch64-shield]
![Supports amd64 Architecture][apiscapegoat-amd64-shield]
![Supports i386 Architecture][apiscapegoat-i386-shield]
![Docker Pulls][apiscapegoat-pulls-shield]

API gateway with failover for REST sensors.

[:books: API Scapegoat add-on documentation][addon-doc-apiscapegoat]

## Releases

Add-on releases are **NOT** based on [Semantic Versioning][semver], unlike
all our other repositories. The latest build commit SHA hash of each
add-on, represents the version number.

## Support

Got questions?

You have several options to get them answered:

You could also open an issue here on GitHub. Note, we use a separate
GitHub repository for each add-on. Please ensure you are creating the issue
on the correct GitHub repository matching the add-on.

- [Open an issue for the add-on: API Scapegoat][apiscapegoat-issue]

For a general repository issue or add-on ideas [open an issue here][issue]

## License

MIT License

Copyright (c) 2020 shawly

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[addon-apiscapegoat]: https://github.com/shawly/hassio-api-scapegoat/tree/ec5ce3f
[addon-doc-apiscapegoat]: https://github.com/shawly/hassio-api-scapegoat/blob/ec5ce3f/README.md
[apiscapegoat-issue]: https://github.com/shawly/hassio-api-scapegoat/issues
[apiscapegoat-version-shield]: https://img.shields.io/badge/version-ec5ce3f-blue.svg
[apiscapegoat-pulls-shield]: https://img.shields.io/docker/pulls/hassiofun/api-scapegoat-armhf.svg
[apiscapegoat-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[apiscapegoat-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[apiscapegoat-armhf-shield]: https://img.shields.io/badge/armhf-yes-green.svg
[apiscapegoat-armv7-shield]: https://img.shields.io/badge/armv7-yes-green.svg
[apiscapegoat-i386-shield]: https://img.shields.io/badge/i386-yes-green.svg
[shawly]: https://github.com/shawly
[gitlabci-shield]: https://gitlab.com/shawly/hassio-addons-dev/badges/master/pipeline.svg
[gitlabci]: https://gitlab.com/shawly/hassio-addons-dev/pipelines
[issue]: https://github.com/shawly/hassio-addons-dev/issues
[license-shield]: https://img.shields.io/github/license/shawly/hassio-addons-dev.svg
[maintenance-shield]: https://img.shields.io/maintenance/yes/2020.svg
[project-stage-shield]: https://img.shields.io/badge/project%20stage-experimental-yellow.svg
[reddit]: https://reddit.com/r/homeassistant
[semver]: http://semver.org/spec/v2.0.0.html
[third-party-addons]: https://home-assistant.io/hassio/installing_third_party_addons/