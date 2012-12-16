Discovery Service
============

This is an example Discovery Service that could be used by a Service Provider that includes both SAML (InCommon in this case) IdPs, and Social IdPs. This is purely an example, as it can not actually be used as a SAML discovery service (although that might change).

The purpose of this example is to show discovery service that has a limited number of IdPs lists for the user to choose, where these IdPs are split out by "Higher Ed Providers" and "Social Providers". These are identified by name as well as an icon, and the service allows the user to filter the options by typing into a text box.

This example is pretending to be a discovery service for Salesforce at UCSF, but it could be intended for any service provider.

## Requirements to Run

To run/view this example, simply take the contents of the project and drop them into the doc root of any web server, and then navigate to:

<pre>
<doc root>/ds.html
<doc root>/ds-configure.html
</pre>

These pages correspond to the discovery service itself, and an example page of how the service could be configured, respectively.