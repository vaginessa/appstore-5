# Viaduct App Store

This repository contains the manifests for applications which exist in the Viaduct
app store. If you'd like to suggest applications for inclusion please
[drop us an email](mailto:team@viaduct.io), or submit a pull request with the appropriate
manifest files within.

## Creating an application

To create an application for the Viaduct app store, the best place to start is by
taking a look at an existing application like Wordpress or Ghost.

Every application in the store must have a file which describes itself (the `.app` file).
This will include details of the application which will be displayed in the web interface.

Applications also must have at least one `.version` file which sets out how the application
can be downloaded and run on the platform. It includes details of where the application's
source code lives, information to be displayed throughout the deployment process and
an `Archfile` which sets out how to provision the application on Viaduct.

## Submitting applications

To submit an application to the app store, simply add your application into one of the
categories provided and submit a pull request on GitHub.
