---
title: ExternalResourceResolver
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/externalresourceresolver/
---

## ExternalResourceResolver class

 Callback class used to resolve external resources during Html, Svg documents import.
 Using this resolver could create a vulnerability when client provided HTML or SVG file will make server software to obtain local or network file. Use with caution. It is recommended not to specify ExternalResourceResolver at all (only embedded objects will be read) or create some subclass which checks if specified uri is valid.

## Constructors

| Name | Description |
| --- | --- |
| [ExternalResourceResolver](externalresourceresolver)() |  |

## Methods

| Name | Description |
| --- | --- |
| [getEntity](getentity)(String) | Maps a URI to an object containing the actual resource. |
| [resolveUri](resolveuri)(String, String) | Resolves the absolute URI from the base and relative URIs. |
