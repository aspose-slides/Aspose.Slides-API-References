﻿---
title: IResourceLoadingArgs class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/iresourceloadingargs/
---


## IResourceLoadingArgs class

Interface for external resource loading arguments.

The IResourceLoadingArgs type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`original_uri`](/slides/python-net/aspose.slides/iresourceloadingargs/original_uri/) | Original URI of the resource as specified in imported presentation. |
| [`uri`](/slides/python-net/aspose.slides/iresourceloadingargs/uri/) | URI of the resource which is used for downloading if [`IResourceLoadingCallback.resource_loading`](/slides/python-net/aspose.slides/iresourceloadingcallback/resource_loading) <br/>            returns [`ResourceLoadingAction.DEFAULT`](/slides/python-net/aspose.slides/resourceloadingaction/DEFAULT). <br/>            Initially it's set to original URI of the resource, but can be redefined to any value. |

## Methods

| Method | Description |
| :- | :- |
| [`set_data`](/slides/python-net/aspose.slides/iresourceloadingargs/set_data/#bytes) | Sets user provided data of the resource which used if [`IResourceLoadingCallback.resource_loading`](/slides/python-net/aspose.slides/iresourceloadingcallback/resource_loading) <br/>            returns [`ResourceLoadingAction.USER_PROVIDED`](/slides/python-net/aspose.slides/resourceloadingaction/USER_PROVIDED). |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

