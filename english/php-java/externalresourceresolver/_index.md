---
title: ExternalResourceResolver
type: docs
weight: 0
url: /php-java/externalresourceresolver/
---

# ExternalResourceResolver class

 Callback class used to resolve external resources during Html, Svg documents import.
 Using this resolver could create a vulnerability when client provided HTML or SVG file will make server software to obtain local or network file. Use with caution. It is recommended not to specify ExternalResourceResolver at all (only embedded objects will be read) or create some subclass which checks if specified uri is valid.

## Constructors

| name | description |
| --- | --- |
| [ExternalResourceResolver](/php-java/externalresourceresolver/externalresourceresolver/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getEntity](/php-java/externalresourceresolver/getentity/)(String) | InputStream | Maps a URI to an object containing the actual resource. |
| [resolveUri](/php-java/externalresourceresolver/resolveuri/)(String, String) | String | Resolves the absolute URI from the base and relative URIs. |
