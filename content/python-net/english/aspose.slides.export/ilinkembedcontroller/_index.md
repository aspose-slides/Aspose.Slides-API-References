---
title: ILinkEmbedController class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides.export/
---


## ILinkEmbedController class

Callback interface used to determine how object should be processed during saving.

The ILinkEmbedController type exposes the following members:

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides.export/ilinkembedcontroller/#int-bytes-string-string-string) | Determines where object should be stored.<br/>            This method is called once for each object id.<br/>            It is not guaranteed that there won't be two objects with same data, semanticName and contentType but with different id. |
| [__init__](/slides/python-net/aspose.slides.export/ilinkembedcontroller/#int-int) | Returns an URL to an external object.<br/>            This method always called if :py:func:`Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste.` returned :py:attr:`aspose.slides.export.LinkEmbedDecision.LINK` and may be called if :py:func:`Aspose.Slides.Export.ILinkEmbedController.GetObjectStoringLocation(System.Int32,System.Byte[],System.String,System.String,Syste.` returned :py:attr:`aspose.slides.export.LinkEmbedDecision.EMBED` but embedding is impossible.<br/>            Can be called multiple time for same object id. |
| [__init__](/slides/python-net/aspose.slides.export/ilinkembedcontroller/#int-bytes) | Saves external object. |

