# Advanced Settings

The following section shows advanced configurations of the APIs.

## Spider Settings

The following image shows the advanced configurations tab of Spider in the desktop UI.

![spider_advanced](../images/spider_advanced.png)

Use the [setOptionMaxDepth](#spideractionsetoptionmaxdepth) to set the maximum depth the spider can crawl, where 0 refers to unlimited depth. 
The [setOptionMaxChildren](#spideractionsetoptionmaxchildren) sets the maximum number of child nodes (per node) that can be crawled, 
where 0 means no limit. The [setOptionMaxDuration](#spideractionsetoptionmaxduration) API can be used to set the maximum duration the Spider will run.
Use the [setOptionMaxParseSizeBytes](#spideractionsetoptionmaxparsesizebytes) to limit the amount of data parsed by the spider. 
This allows the spider to skip big responses/files. 

View the [Spider section](#spider) in the API Catalogue for additional APIs.

## Ajax Spider  Settings

The following image shows the advanced configurations tab of Ajax Spider in the desktop UI.

![ajax_spider_advanced](../images/ajax_spider_advanced.png)

Similar to the Spider API, the Ajax spider also provides APIs to set the [maximum depth](#), [crawl state](#), and [maximum duration](#).

## Passive Scan Settings

The scanning rules can be enabled/disabled using the [enableScanners](#pscanactionenablescanners) and [disableScanners]((#pscanactiondisablescanners)) API.
Also use the [setScanOnlyInScope](#pscanviewscanonlyinscope) API to limit the passive scanning to a scope. View
the advanced section to learn how to configure a context or scope using ZAP APIs.

Passive scanning can also be used to automatically add tags and raise alerts for potential issues. A set of rules for 
automatic tagging are provided by default. These can be changed, deleted or added to via the Options Passive Scan Tags Screen.

## Active Scan Settings

Content in progress!

## Troubleshooting

This section has troubleshooting procedures for the following problems that people may encounter with ZAP APIs:

**No Implementor Error**

- Check that the necessary addon or component is installed and enabled. (For example if you receive "no_implementor" in relation 
to Ajax Spider calls, perhaps the Ajax Spider addon isn't installed.)

