---
title: HtmlExternalResolver
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 10
url: /php-java/aspose.slides/htmlexternalresolver/
---

## HtmlExternalResolver class

 Callback object used by HTML import routine to obtain referrenced objects such as images.
 Using this resolver could create a vulnurability when client provided HTML file will make server software to obtain local or network file. Use with caution. It is recommended not to specify HtmlExternalResolver at all (only embedded objects will be read) or create some subclass which checks if specified uri is valid.

## Constructors

| Name | Description |
| --- | --- |
| [HtmlExternalResolver](htmlexternalresolver)() |  |

## Methods

| Name | Description |
| --- | --- |
| [getEntity](getentity)(String) | Maps a URI to an object containing the actual resource. |
| [resolveUri](resolveuri)(String, String) | Resolves the absolute URI from the base and relative URIs. |
