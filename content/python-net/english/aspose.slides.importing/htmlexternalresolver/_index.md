---
title: HtmlExternalResolver
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.importing/htmlexternalresolver/
---


HtmlExternalResolver class

Callback object used by HTML import routine to obtain referrenced objects such as images.
            
Using this resolver could create a vulnurability when client provided HTML file will make server software to obtain local or network file. Use with caution. It is recommended not to specify HtmlExternalResolver at all (only embedded objects will be read) or create some subclass which checks if specified uri is valid.

The HtmlExternalResolver type exposes the following members:

## Constructors

| Constructor | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.importing/htmlexternalresolver/htmlexternalresolver/#/) |  |

## Properties

| Property | Description |
| :- | :- |
| [as_i_external_resource_resolver](/slides/python-net/aspose.slides.importing/htmlexternalresolver/as_i_external_resource_resolver/) |  |

## Methods

| Method | Description |
| :- | :- |
| [resolve_uri](/slides/python-net/aspose.slides.importing/htmlexternalresolver/htmlexternalresolver/#string-string/) | Resolves the absolute URI from the base and relative URIs. |
| [get_entity](/slides/python-net/aspose.slides.importing/htmlexternalresolver/htmlexternalresolver/#string/) | Maps a URI to an object containing the actual resource. |

