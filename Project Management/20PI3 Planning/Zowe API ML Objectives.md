# Zowe API ML & Security Squad - 20PI3 Objectives (June 2020 to September 2020)

## x.509 client certificate authentication support for API Mediation Layer
(in support of SECURITY theme)

* [X.509 client certificate authentication support for API Mediation Layer #704](https://github.com/zowe/api-layer/issues/704)
Zowe API ML can validate client certificates by using ESM to map the certificate with the user mainframe identity and issue a JWT


## Remove the dependency of Zowe API ML on z/OSMF for authentication and use SAF to obtain the JWT
(in support of SECURITY theme)

* [Support that APIML can be started without z/OSMF #472](https://github.com/zowe/api-layer/issues/472)
Instead of a call to z/OSMF, Zowe API ML will use SAF APIs to verify credentials. This will be implemented as an additional provider, the z/OSMF authentication provider will remain the default.


## Support for high availability / sysplex distributor in API Mediation Layer
(in support of RESILIENCE theme)

*  [Support for high availability / sysplex distributor in API Mediation Layer #705](https://github.com/zowe/api-layer/issues/705)
The usage of Dynamic Virtual IP Address (DVIPA) will ensure that if an instance of Gateway and/or Discovery fails on one system (LPAR1), the other system (LPAR2) continues to provide service functionality through a sysplex distributor.


## zowe / api-layer backlog management

* [Focus on high priority / high impact issues in Github](https://github.com/zowe/api-layer/labels/20PI3)