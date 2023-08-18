---
title: SlideSize
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/slidesize/
---

## SlideSize class

 Represents a size of slide.
 

## Functions

| Name | Description |
| --- | --- |
| [getOrientation](getorientation)() | Returns or sets the slide orientation. Read/write SlideOrientation. Changing this value will swap slide's dimensions. |
| [getSize](getsize)() | Returns or sets the size in points. Read/write java.awt.geom.Dimension2D. Assigning any value will reset ( #getType) property to SlideSizeType#Custom and set ( #getOrientation/ #setOrientation(int)). |
| [getType](gettype)() | Returns or sets the type of slide size. Read/write SlideSizeType. Assigning any value except SlideSizeType#Custom will change ( #getSize) accordingly, but will keep ( #getOrientation/ #setOrientation(int)) intact. |
| [setOrientation](setorientation)(int) | Returns or sets the slide orientation. Read/write SlideOrientation. Changing this value will swap slide's dimensions. |
| [setSize](setsize)(int, int) | Sets the type of slide size and scales content using scale type. |
| [setSize](setsize)(float, float, int) | Sets the size in points and scales content using scale type. |
