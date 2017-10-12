# Keycloak Node.js Adapter-v2.3.0-ipv6 support

[![Build Status](https://travis-ci.org/keycloak/keycloak-nodejs-connect.svg?branch=master)](https://travis-ci.org/keycloak/keycloak-nodejs-connect)
[![Dependency Status](https://img.shields.io/david/keycloak/keycloak-nodejs-connect.svg?style=flat-square)](https://david-dm.org/keycloak/keycloak-nodejs-connect)

[Keycloak](http://keycloak.org/) is a standalone authentication
server, akin to a standalone database.  It provides hooks for federated
authentication, including authenticating against various social networks
and OAuth providers (G+, Facebook, etc).

This module makes it simple to implement a Node.js Connect-friendly
application that uses Keycloak for its authentication and authorization needs. For usage instructions, please read the [documentation](https://keycloak.gitbooks.io/securing-client-applications-guide/content/topics/oidc/nodejs-adapter.html).
Currently, the official keycloak Node.js couldn't support ipv6 address parsed,see [ticket](https://issues.jboss.org/browse/KEYCLOAK-5347?filter=-2)
So,NOKIA make enhancement for ipv6 parsed based on keycloak-nodejs-adapter-v2.3.0. 

## Contributing

Please read the [contributing guide](./CONTRIBUTING.md)
