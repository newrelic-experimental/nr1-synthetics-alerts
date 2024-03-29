[![New Relic Experimental header](https://github.com/newrelic/opensource-website/raw/master/src/images/categories/Experimental.png)](https://opensource.newrelic.com/oss-category/#new-relic-experimental)[`New Relic One Catalog`](https://github.com/newrelic/open-source-office/blob/master/examples/categories/index.md#nr1-catalog)

# Synthetics Alert Condition Search 

>This NerdPack allows you to check what Alert Conditions are targetting a specific Synthetics Monitor Entity, from within the context of the Entity UI.

## Features
 - Auto-detects region to ensure EU accounts use EU REST API endpoints
 - Fetches Single and Multi-Location Conditions targeting the Monitor via API
 - Fetches NRQL Conditions containing the Monitor Name or ID
 - Fetches NRQL Conditions with general `monitorName` and `monitorId` FACETS which may be targeting the Monitor
 - Links each Condition to their Policy in Alerts & AI

## Installation

> Setup your Developer Environment as per the guidelines on the Developer site:
 - https://developer.newrelic.com/build-apps/set-up-dev-env

> Check your local profile is correct:

```
nr1 profiles:default
```

> Clone the Repository
```
nr1 nerdpack:clone -r https://github.com/newrelic-experimental/nr1-synthetics-alerts.git
```

> **Enter your password**

> Install Node Modules:

```
cd Synthetics-Alert-Condition-Search
npm i
```

> Generate a new UUID for the NerdPack:
```
nr1 nerdpack:uuid -gf
```

## Serve Locally
 - `nr1 nerdpack:serve`
 - OR `npm start`

## Publish and Subscribe

To Publish to New Relic and Subscribe your Account:

```
nr1 nerdpack:publish
nr1 subscription:set
```

## Getting Started

>There is a launcher but all the functionality is currently accessed through the Entity UI
Go to any Synthetics Monitor entity and you should see `Synthetics Condition Search` in the **More Views** section on the LHS panel

## Support

New Relic has open-sourced this project. This project is provided AS-IS WITHOUT WARRANTY OR DEDICATED SUPPORT. Issues and contributions should be reported to the project here on GitHub.

>We encourage you to bring your experiences and questions to the [Explorers Hub Post](https://discuss.newrelic.com/t/relic-solution-just-dropped-in-to-see-what-conditions-my-synthetics-were-in/114182) where our community members collaborate on solutions and new ideas.

## Issues / enhancement requests

Issues and enhancement requests can be submitted in the [Issues tab of this repository](../../issues). Please search for and review the existing open issues before submitting a new issue.

## Contributing

We encourage your contributions to improve Synthetics Alert Condition Search! Keep in mind when you submit your pull request, you'll need to sign the CLA via the click-through using CLA-Assistant. You only have to sign the CLA one time per project.

If you have any questions, or to execute our corporate CLA, required if your contribution is on behalf of a company,  please drop us an email at opensource@newrelic.com.

## License

Synthetics Alert Condition Search is licensed under the [Apache 2.0](http://apache.org/licenses/LICENSE-2.0.txt) License.

>Synthetics Condition Search also uses source code from third-party libraries. You can find full details on which libraries are used and the terms under which they are licensed in the third-party notices document.
