![Simplicit&eacute; Software](https://www.simplicite.io/resources/logos/logo250.png)
* * *

<a href="https://www.simplicite.io"><img src="https://img.shields.io/badge/author-Simplicite_Software-blue.svg?style=flat-square" alt="Author"></a>&nbsp;<img src="https://img.shields.io/badge/license-Apache--2.0-orange.svg?style=flat-square" alt="License"> [![Gitter chat](https://badges.gitter.im/org.png)](https://gitter.im/simplicite/Lobby)

OpenShift&reg; template for Simplicit&eacute;&reg;
==================================================

This is the webapp template for OpenShift&reg; designed for Simplicit&eacute;&reg; sandboxes.

Prerequisites
-------------

A OpenShift&reg; account.

Get the Simplicit&eacute;&reg; sandbox template from our GIT repository
(see [simplicite.io website](http://www.simplicite.io) for details on how to get access to this repository).

Replace the default test `src/webapp/` root webapp folder content with your Simplicit&eacute; root webapp content.

If required you can customize the `src/webapp/META-INF/context.xml` and/or `src/webapp/WEB-INF/web.xml` to your needs (e.g. to add additional datasources).

If required you can also add:

- Additional Java libs in `src/webapp/WEB-INF/lib`
- Static JavaScript files in `src/webapp/scripts`
- Static CSS/images files in `src/webapp/images`
- Etc.

Deploy
------

Push to an OpenShift&reg; **Tomcat cartridge** as described in [this documentation](https://developers.openshift.com/en/tomcat-getting-started.html).
