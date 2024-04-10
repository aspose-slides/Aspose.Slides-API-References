---
title: IResourceLoadingArgs class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/
---


## IResourceLoadingArgs class

Interface for external resource loading arguments.

The IResourceLoadingArgs type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [original_uri](/slides/python-net/aspose.slides/original_uri) | Original URI of the resource as specified in imported presentation. |
| [uri](/slides/python-net/aspose.slides/uri) | URI of the resource which is used for downloading if :py:func:`Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide.` <br/>            returns :py:attr:`aspose.slides.ResourceLoadingAction.DEFAULT`. <br/>            Initially it's set to original URI of the resource, but can be redefined to any value. |

## Methods

| Method | Description |
| :- | :- |
| [__init__](/slides/python-net/aspose.slides/iresourceloadingargs/#bytes) | Sets user provided data of the resource which used if :py:func:`Aspose.Slides.IResourceLoadingCallback.ResourceLoading(Aspose.Slide.` <br/>            returns :py:attr:`aspose.slides.ResourceLoadingAction.USER_PROVIDED`. |

