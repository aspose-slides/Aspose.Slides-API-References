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
| [size](/slides/python-net/aspose.slides/islidesize/size/) | Returns or sets the size in points.<br/>            <br/>Assigning any value will reset <br/>[`ISlideSize.type`](/slides/python-net/aspose.slides/islidesize#type)<br/> property to <br/>[`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype#CUSTOM)<br/> and set <br/>[`ISlideSize.orientation`](/slides/python-net/aspose.slides/islidesize#orientation)<br/>.<br/><br/>            Read/write <br/>.NET type System.Drawing.SizeF<br/>. |
| [type](/slides/python-net/aspose.slides/islidesize/type/) | Returns or sets the type of slide size.<br/>            <br/>Assigning any value except <br/>[`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype#CUSTOM)<br/> will change <br/>[`ISlideSize.size`](/slides/python-net/aspose.slides/islidesize#size)<br/> accordingly, but will keep <br/>[`ISlideSize.orientation`](/slides/python-net/aspose.slides/islidesize#orientation)<br/> intact.<br/><br/>            Read/write <br/>[`SlideSizeType`](/slides/python-net/aspose.slides/slidesizetype)<br/>. |
| [orientation](/slides/python-net/aspose.slides/islidesize/orientation/) | Returns or sets the slide orientation.<br/>            <br/>Changing this value will swap slide's dimensions.<br/><br/>            Read/write <br/>[`SlideOrientation`](/slides/python-net/aspose.slides/slideorientation)<br/>. |

## Methods

| Method | Description |
| :- | :- |
| [set_size](/slides/python-net/aspose.slides/islidesize/islidesize/#SlideSizeType-SlideSizeScaleType/) | Sets the type of slide size and scales content using scale type.<br/>             <br/>Assigning any value except <br/>[`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype#CUSTOM)<br/> will change <br/>[`ISlideSize.size`](/slides/python-net/aspose.slides/islidesize#size)<br/> accordingly, but will keep <br/>[`ISlideSize.orientation`](/slides/python-net/aspose.slides/islidesize#orientation)<br/> intact. |
| [set_size](/slides/python-net/aspose.slides/islidesize/islidesize/#float-float-SlideSizeScaleType/) | Sets the size in points and scales content using scale type.<br/>            <br/>Assigning any value will reset <br/>[`ISlideSize.type`](/slides/python-net/aspose.slides/islidesize#type)<br/> property to <br/>[`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype#CUSTOM)<br/> and set <br/>[`ISlideSize.orientation`](/slides/python-net/aspose.slides/islidesize#orientation)<br/>. |

