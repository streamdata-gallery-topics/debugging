---
name: Google App Engine
description: 'Build modern web and mobile applications on an open cloud platform:
  bring your own language runtimes, frameworks, and third party libraries. Google
  App Engine is a fully managed platform that completely abstracts away infrastructure
  so you focus only on code. Go from zero to planet-scale and see why some of todayrsquo;s
  most successful companies power their applications on App Engine.'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
x-kinRank: "9"
x-alexaRank: ""
tags:
- Stack Network
- Google APIs
- Deployment
- Compute
- Cloud
created: "2018-03-23"
modified: "2018-03-23"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/debugging/master/_listings/google-app-engine/apis.yaml
specificationVersion: "0.14"
apis:
- name: Google App Engine Admin API
  description: 'Build modern web and mobile applications on an open cloud platform:
    bring your own language runtimes, frameworks, and third party libraries'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: ""
  baseURL: ://appengine.googleapis.com//
  tags: Debugging
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/debugging/master/_listings/google-app-engine/v1-apps-appsid-services-servicesid-versions-versionsid-instances-instancesid-debug-post.md
- name: Google App Engine Admin API Enable Debugging
  description: Enables debugging on a VM instance. This allows you to use the SSH
    command to connect to the virtual machine where the instance lives. While in "debug
    mode", the instance continues to serve live traffic. You should delete the instance
    when you are done debugging and then allow the system to take over and determine
    if another instance should be started.Only applicable for instances in App Engine
    flexible environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/google-app-engine-icon.png
  humanURL: https://cloud.google.com/appengine/
  baseURL: http:://appengine.googleapis.com//
  tags: Debugging
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/debugging/master/_listings/google-app-engine/v1-apps-appsid-services-servicesid-versions-versionsid-instances-instancesid-debug-post.md
x-common:
- type: x-code-page
  url: https://cloud.google.com/appengine/docs/admin-api/client-libraries
- type: x-developer
  url: https://cloud.google.com/appengine/docs/admin-api/
- type: x-documentation
  url: https://cloud.google.com/appengine/docs/admin-api/apis
- type: x-getting-started
  url: https://cloud.google.com/appengine/docs/admin-api/getting-started/
- type: x-how-to-guides
  url: https://cloud.google.com/appengine/docs/admin-api/how-to
- type: x-launcher
  url: https://cloud.google.com/launcher/
- type: x-pricing
  url: https://cloud.google.com/pricing/
- type: x-sla
  url: https://cloud.google.com/appengine/sla
- type: x-website
  url: https://cloud.google.com/appengine/
- type: x-code-page
  url: https://cloud.google.com/appengine/docs/admin-api/client-libraries
- type: x-developer
  url: https://cloud.google.com/appengine/docs/admin-api/
- type: x-documentation
  url: https://cloud.google.com/appengine/docs/admin-api/apis
- type: x-getting-started
  url: https://cloud.google.com/appengine/docs/admin-api/getting-started/
- type: x-how-to-guides
  url: https://cloud.google.com/appengine/docs/admin-api/how-to
- type: x-launcher
  url: https://cloud.google.com/launcher/
- type: x-pricing
  url: https://cloud.google.com/pricing/
- type: x-sla
  url: https://cloud.google.com/appengine/sla
- type: x-website
  url: https://cloud.google.com/appengine/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---