---
title: ExternalResourceResolver class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.importing/externalresourceresolver/
---


## ExternalResourceResolver class

Callback class used to resolve external resources during Html, Svg documents import.
Using this resolver could create a vulnerability when client provided HTML or SVG file will make server software to obtain local or network file. Use with caution. It is recommended not to specify ExternalResourceResolver at all (only embedded objects will be read) or create some subclass which checks if specified uri is valid.

The ExternalResourceResolver type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [`__init__`](/slides/python-net/aspose.slides.importing/externalresourceresolver/__init__/#) |  |

## Methods

| Method | Description |
| :- | :- |
| [`resolve_uri`](/slides/python-net/aspose.slides.importing/externalresourceresolver/resolve_uri/#str-str) | Resolves the absolute URI from the base and relative URIs. |
| [`get_entity`](/slides/python-net/aspose.slides.importing/externalresourceresolver/get_entity/#str) | Maps a URI to an object containing the actual resource. |


### See Also
* module [`aspose.slides.importing`](/slides/python-net/aspose.slides.importing)
* library [`Aspose.Slides`](/slides/python-net)

