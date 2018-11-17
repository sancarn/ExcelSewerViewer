## Modelling in Excel

### Limitations:

This is super work in progress, and currently extremely feature lacking as I work on other projects.

The basic idea is to allow users to add as many tables as they like to the viewer, however it currently only works for tables named "Nodes" and "Links" (case sensitive).

Also note: currently system type doesn't update "live", you have to refresh the addin each time you change system types. It is only really good for static viewing at the moment.

## Version info

Version: 0.0.1

Exported on: Saturday, November 17th 2018, 12:14:26 pm

Built with [Script Lab](https://github.com/OfficeDev/script-lab)

## Developer info

### To re-import the snippet into Script Lab:
Copy the metadata (*.yaml) file into the "import" screen in Script Lab. See <https://github.com/OfficeDev/script-lab/blob/master/README.md#import> for detailed instructions.

### To run the snippet *outside* of Script Lab (like a "mini" exported Add-in):

1. Publish the html file to a website. Note that because settings/cookies/etc are stored per domain name (not per page URL, but the entire domain name), it is best to put the snippet in its own website (with its own unique domain name) if you make use of these.

2. Search for `https://<INSERT-URL-HERE>` within manifest file (should be 2 occurrences), and replace both with the URL that the html page is published to. If you've renamed the html file, adjust the path as well.

3. Sideload the manifest using the instructions found at <https://aka.ms/sideload-addins>.
