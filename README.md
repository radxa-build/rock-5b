# ROCK 5B
[![Build](https://github.com/radxa-build/rock-5b/workflows/Build/badge.svg)](https://github.com/radxa-build/rock-5b/actions/workflows/build.yml)

## What is this?

This repo is the central location for Radxa-built system images for ROCK 5B.

Not all images are officially supported by Radxa. Some of them are only provided as-is with no warranty. Please read below for detailed explanations.

## What images are provided?

Currently the following images are provided:
* Radxa [`debos-radxa`](https://github.com/radxa/debos-radxa) images (currently supported)
* Radxa [`rbuild`](https://github.com/radxa-repo/rbuild) images (currently testing)
* [`Armbian`](https://github.com/armbian/build) images (**Unofficial build**)

`debos-radxa` images contain the build time in the file name, while `rbuild` images have a fixed file name across releases. They have similar file name format as `rbuild` is intended to replace `debos-radxa`. Once we deem `rbuild` is production-ready we will cease to produce `debos-radxa` images to avoid confusion.

We provide **unofficial** Armbian images for evaluation purposes only. This is not a Radxa custom fork but built using unmodified upstream code. We do not support those images, and prefer to work with upstream directly to resolve the issues in their official releases.

## Is there any other options?

Armbian users are strongly recommended to use [Armbian official image](https://www.armbian.com/rock-5b/).

Please visit [our Wiki](https://wiki.radxa.com/Rock5/downloads) for more download options.

## Where can I download the Radxa image?

Every month new images are [built](https://github.com/radxa-build/rock-5b/actions/workflows/build.yml) and [published](https://github.com/radxa-build/rock-5b/releases) as pre-releases, which serve as release candidates (RC). Radxa will periodically select an RC for additional testing, and once it passes those tests, promote it as an officially supported release. This is why you are always recommended to use [the latest release](https://github.com/radxa-build/rock-5b/releases/latest).

## Help! Something doesn't work!

For other questions, please first take a look at [our Wiki](https://wiki.radxa.com/Rock5), which covers the most basic usages.

Should you have any additional questions, please visit [our forum](https://forum.radxa.com/) or [our Discord](https://rock.sh/go), and we are willing to help.
