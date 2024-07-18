---
title: SlideSize class
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/slidesize/
---


## SlideSize class

Represents a size of slide.

The SlideSize type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [`size`](/slides/python-net/aspose.slides/slidesize/size/) | Returns or sets the size in points.<br/>            Assigning any value will reset [`SlideSize.type`](/slides/python-net/aspose.slides/slidesize/type) property to [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype/CUSTOM) and set [`SlideSize.orientation`](/slides/python-net/aspose.slides/slidesize/orientation).<br/>            Read/write **aspose.pydrawing.SizeF**. |
| [`type`](/slides/python-net/aspose.slides/slidesize/type/) | Returns or sets the type of slide size.<br/>            Assigning any value except [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype/CUSTOM) will change [`SlideSize.size`](/slides/python-net/aspose.slides/slidesize/size) accordingly, but will keep [`SlideSize.orientation`](/slides/python-net/aspose.slides/slidesize/orientation) intact.<br/>            Read/write [`SlideSizeType`](/slides/python-net/aspose.slides/slidesizetype). |
| [`orientation`](/slides/python-net/aspose.slides/slidesize/orientation/) | Returns or sets the slide orientation.<br/>            Changing this value will swap slide's dimensions.<br/>            Read/write [`SlideOrientation`](/slides/python-net/aspose.slides/slideorientation). |

## Methods

| Method | Description |
| :- | :- |
| [`set_size`](/slides/python-net/aspose.slides/slidesize/set_size/#slidesizetype-slidesizescaletype) | Sets the type of slide size and scales content using scale type.<br/>             Assigning any value except [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype/CUSTOM) will change [`SlideSize.size`](/slides/python-net/aspose.slides/slidesize/size) accordingly, but will keep [`SlideSize.orientation`](/slides/python-net/aspose.slides/slidesize/orientation) intact. |
| [`set_size`](/slides/python-net/aspose.slides/slidesize/set_size/#float-float-slidesizescaletype) | Sets the size in points and scales content using scale type.<br/>            Assigning any value will reset [`SlideSize.type`](/slides/python-net/aspose.slides/slidesize/type) property to [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype/CUSTOM) and set [`SlideSize.orientation`](/slides/python-net/aspose.slides/slidesize/orientation). |


### See Also
* module [`aspose.slides`](/slides/python-net/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)

