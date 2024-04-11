---
title: ISlideSize
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/islidesize/
---


ISlideSize class

Represents a size of slide.

The ISlideSize type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [size](/slides/python-net/aspose.slides/islidesize/size/) | Returns or sets the size in points.<br/>            Assigning any value will reset [`ISlideSize.type`](/slides/python-net/aspose.slides/islidesize#type) property to [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype#CUSTOM) and set [`ISlideSize.orientation`](/slides/python-net/aspose.slides/islidesize#orientation).<br/>            Read/write .NET type System.Drawing.SizeF. |
| [type](/slides/python-net/aspose.slides/islidesize/type/) | Returns or sets the type of slide size.<br/>            Assigning any value except [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype#CUSTOM) will change [`ISlideSize.size`](/slides/python-net/aspose.slides/islidesize#size) accordingly, but will keep [`ISlideSize.orientation`](/slides/python-net/aspose.slides/islidesize#orientation) intact.<br/>            Read/write [`SlideSizeType`](/slides/python-net/aspose.slides/slidesizetype). |
| [orientation](/slides/python-net/aspose.slides/islidesize/orientation/) | Returns or sets the slide orientation.<br/>            Changing this value will swap slide's dimensions.<br/>            Read/write [`SlideOrientation`](/slides/python-net/aspose.slides/slideorientation). |

## Methods

| Method | Description |
| :- | :- |
| [set_size](/slides/python-net/aspose.slides/islidesize/set_size/#SlideSizeType-SlideSizeScaleType) | Sets the type of slide size and scales content using scale type.<br/>             Assigning any value except [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype#CUSTOM) will change [`ISlideSize.size`](/slides/python-net/aspose.slides/islidesize#size) accordingly, but will keep [`ISlideSize.orientation`](/slides/python-net/aspose.slides/islidesize#orientation) intact. |
| [set_size](/slides/python-net/aspose.slides/islidesize/set_size/#float-float-SlideSizeScaleType) | Sets the size in points and scales content using scale type.<br/>            Assigning any value will reset [`ISlideSize.type`](/slides/python-net/aspose.slides/islidesize#type) property to [`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype#CUSTOM) and set [`ISlideSize.orientation`](/slides/python-net/aspose.slides/islidesize#orientation). |

