---
title: ILinkEmbedController
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/ilinkembedcontroller/
---


ILinkEmbedController class

Callback interface used to determine how object should be processed during saving.

The ILinkEmbedController type exposes the following members:

## Methods

| Method | Description |
| :- | :- |
| [get_object_storing_location](/slides/python-net/aspose.slides.export/ilinkembedcontroller/ilinkembedcontroller/#int-bytes-string-string-string/) | Determines where object should be stored.<br/>            This method is called once for each object id.<br/>            It is not guaranteed that there won't be two objects with same data, semanticName and contentType but with different id. |
| [get_url](/slides/python-net/aspose.slides.export/ilinkembedcontroller/ilinkembedcontroller/#int-int/) | Returns an URL to an external object.<br/>            This method always called if <br/>Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste. returned <br/>[`LinkEmbedDecision.LINK`](/slides/python-net/aspose.slides.export/linkembeddecision#LINK) and may be called if <br/>Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste. returned <br/>[`LinkEmbedDecision.EMBED`](/slides/python-net/aspose.slides.export/linkembeddecision#EMBED) but embedding is impossible.<br/>            Can be called multiple time for same object id. |
| [save_external](/slides/python-net/aspose.slides.export/ilinkembedcontroller/ilinkembedcontroller/#int-bytes/) | Saves external object. |

