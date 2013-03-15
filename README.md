workspaceBNDBridgeExample
=========================

Example for https://github.com/tonit/pax-bnd-mavenplugin

How to use:
- first make sure you've built and installed the pax-bnd-mavenplugin from https://github.com/tonit/pax-bnd-mavenplugin
- then go to test-parent and hit "mvn clean install"

Works with BNDTools

Not fully covered yet:
- maven reactor order
- M2E (if installed) will not really like this plugin yet since there is no lifecycle plugin. At best just disable the M2E Nature after importing and let BNDTools do the job.


