# OGC API - Connected Systems Micro Website

This repository hosts the source code of the OGC API - Connected Systems Micro Website: https://csapi.developer.ogc.org

The site is built and deployed automatically by [GitHub Actions](https://github.com/opengeospatial/ogc-csapi-website/actions) on every push to `master`. Read [this note](#note-about-publishing-the-website) for details.

This project was forked from [opengeospatial/ogc-features-website](https://github.com/opengeospatial/ogc-features-website) and adapted for the OGC API – Connected Systems standards family (CSAPI Part 1: Feature Resources, Part 2: Dynamic Data, plus the SensorML and SWE Common encodings).

## Quick Start :rocket:

Clone this repository with:

`git clone https://github.com/opengeospatial/ogc-csapi-website.git`

Then enter the folder:

`cd ogc-csapi-website`

Install dependencies:

`npm install`

Start development server:

`npm start`

Once you start the development server, the site will be available at:

`http://localhost:3000`

The hot reload will ensure that the changes you do on the code will be reflected on the browser.

### Note about Publishing the Website

Commit all your changes to the `master` branch. The [GitHub Actions workflow](./.github/workflows/main.yml) builds the static site from `src/` into `dist/`, uploads it as a Pages artifact, and deploys it. **You don't need to do anything to publish the website** - the republish is triggered automatically with each push to `master`.

## Contributing 🤝

This website is a live project and we welcome contributions from the community! If you have suggestions for improvements, found a bug, or want to add new features, feel free to:

* Open an [issue](https://github.com/opengeospatial/ogc-csapi-website/issues) to start a discussion
* Submit a [pull request](https://github.com/opengeospatial/ogc-csapi-website/pulls) with your proposed changes

We appreciate your support in making this website better!


## License

This project is released under an [MIT License](./LICENSE)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
(dev-exercise-template)
