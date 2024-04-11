---
title: SlideSize
second_title: Aspose.Slides for Python via .NET API Reference
description: 
type: docs
url: /aspose.slides/slidesize/
---


SlideSize class

Represents a size of slide.

The SlideSize type exposes the following members:

## Properties

| Property | Description |
| :- | :- |
| [size](/slides/python-net/aspose.slides/slidesize/size/) | Returns or sets the size in points.<br/>            <br/>Assigning any value will reset <br/>[`SlideSize.type`](/slides/python-net/aspose.slides/slidesize#type)<br/> property to <br/>[`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype#CUSTOM)<br/> and set <br/>[`SlideSize.orientation`](/slides/python-net/aspose.slides/slidesize#orientation)<br/>.<br/><br/>            Read/write <br/>.NET type System.Drawing.SizeF<br/>. |
| [type](/slides/python-net/aspose.slides/slidesize/type/) | Returns or sets the type of slide size.<br/>            <br/>Assigning any value except <br/>[`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype#CUSTOM)<br/> will change <br/>[`SlideSize.size`](/slides/python-net/aspose.slides/slidesize#size)<br/> accordingly, but will keep <br/>[`SlideSize.orientation`](/slides/python-net/aspose.slides/slidesize#orientation)<br/> intact.<br/><br/>            Read/write <br/>[`SlideSizeType`](/slides/python-net/aspose.slides/slidesizetype)<br/>. |
| [orientation](/slides/python-net/aspose.slides/slidesize/orientation/) | Returns or sets the slide orientation.<br/>            <br/>Changing this value will swap slide's dimensions.<br/><br/>            Read/write <br/>[`SlideOrientation`](/slides/python-net/aspose.slides/slideorientation)<br/>. |

## Methods

| Method | Description |
| :- | :- |
| [set_size](/slides/python-net/aspose.slides/slidesize/slidesize/#SlideSizeType-SlideSizeScaleType/) | Sets the type of slide size and scales content using scale type.<br/>             <br/>Assigning any value except <br/>[`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype#CUSTOM)<br/> will change <br/>[`SlideSize.size`](/slides/python-net/aspose.slides/slidesize#size)<br/> accordingly, but will keep <br/>[`SlideSize.orientation`](/slides/python-net/aspose.slides/slidesize#orientation)<br/> intact. |
| [set_size](/slides/python-net/aspose.slides/slidesize/slidesize/#float-float-SlideSizeScaleType/) | Sets the size in points and scales content using scale type.<br/>            <br/>Assigning any value will reset <br/>[`SlideSize.type`](/slides/python-net/aspose.slides/slidesize#type)<br/> property to <br/>[`SlideSizeType.CUSTOM`](/slides/python-net/aspose.slides/slidesizetype#CUSTOM)<br/> and set <br/>[`SlideSize.orientation`](/slides/python-net/aspose.slides/slidesize#orientation)<br/>. |

