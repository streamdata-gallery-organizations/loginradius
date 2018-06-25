---
name: LoginRadius
x-slug: loginradius
description: Simplify customer authentication and authorization to amplify your business
  with better understanding of your audience using our customer identity management
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1086-loginradius.jpg
x-kinRank: "8"
x-alexaRank: "60839"
tags: LoginRadius
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/loginradius/master/_listings/loginradius/apis.md
specificationVersion: "0.14"
apis:
- name: Matrix Login Operations API Get the login mechanism to use when logging in.
  x-api-slug: matrix-login-operations-api
  description: All login stages MUST be mentioned if there is >1 login type.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1086-loginradius.jpg
  humanURL: http://www.loginradius.com/
  baseURL: :///login/http://localhost:8008/_matrix/client/api/v1//login
  tags: Login,Mechanism,To,Use,When,Logging,In
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/loginradius/master/_listings/loginradius/login-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/loginradius/master/_listings/loginradius/login-get-openapi.md
- name: Matrix Login Operations API Submit a login action.
  x-api-slug: matrix-login-operations-api
  description: If this is part of a multi-stage login, there MUST be a session key.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1086-loginradius.jpg
  humanURL: http://www.loginradius.com/
  baseURL: :///login/http://localhost:8008/_matrix/client/api/v1//login
  tags: Submit,Login,Action
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/loginradius/master/_listings/loginradius/login-post-openapi.md
- name: Matrix Login Operations API
  x-api-slug: matrix-login-operations-api
  description: Matrix is an open standard for decentralised communication, providing
    simple HTTP APIs and open source reference implementations for securely distributing
    and persisting JSON over an open federation of servers.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/1086-loginradius.jpg
  humanURL: http://www.loginradius.com/
  baseURL: :///login/http://localhost:8008/_matrix/client/api/v1
  tags: LoginRadius
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/loginradius/master/_listings/loginradius/openapi.md
x-common:
- type: x-base
  url: https://api.loginradius.com
- type: x-blog
  url: http://blog.loginradius.com
- type: x-blog-rss
  url: http://blog.loginradius.com/feed/
- type: x-crunchbase
  url: https://crunchbase.com/organization/loginradius
- type: x-crunchbase
  url: http://www.crunchbase.com/company/loginradius
- type: x-developer
  url: http://www.loginradius.com/developers
- type: x-email
  url: privacy@loginradius.com
- type: x-email
  url: legal@loginradius.com
- type: x-email
  url: support@loginradius.com
- type: x-github
  url: https://github.com/LoginRadius
- type: x-pricing
  url: http://www.loginradius.com/pricing
- type: x-twitter
  url: https://twitter.com/LoginRadius
- type: x-website
  url: http://www.loginradius.com/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---