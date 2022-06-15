---
title: HtmlExternalResolver
type: docs
weight: 0
url: /php-java/htmlexternalresolver/
---

# HtmlExternalResolver class

 Callback object used by HTML import routine to obtain referrenced objects such as images.
 Using this resolver could create a vulnurability when client provided HTML file will make server software to obtain local or network file. Use with caution. It is recommended not to specify HtmlExternalResolver at all (only embedded objects will be read) or create some subclass which checks if specified uri is valid.

## Constructors

| name | description |
| --- | --- |
| [HtmlExternalResolver](/slides/php-java/htmlexternalresolver/htmlexternalresolver/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getEntity](/slides/php-java/htmlexternalresolver/getentity/)(String) | InputStream | Maps a URI to an object containing the actual resource. |
| [resolveUri](/slides/php-java/htmlexternalresolver/resolveuri/)(String, String) | String | Resolves the absolute URI from the base and relative URIs. |
