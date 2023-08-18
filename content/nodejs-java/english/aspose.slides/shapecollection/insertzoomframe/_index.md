---
title: insertZoomFrame
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/shapecollection/insertzoomframe/
---

## insertZoomFrame(int index, float x, float y, float width, float height, [Slide](../../slide) slide)  function

 Creates a new Zoom object and inserts it to a collection at the specified index.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Zoom frame should be inserted. |
| x | float | X coordinate of a new Zoom frame {@code float}. |
| y | float | Y coordinate of a new Zoom frame {@code float}. |
| width | float | Width of a new Zoom frame {@code float}. |
| height | float | Height of a new Zoom frame {@code float}. |
| slide | [Slide](../../slide) | The slide object referenced by the Zoom frame ISlide. |

### Result
[ZoomFrame](../../zoomframe)

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced slide does not belong to the current presentation. |


---


## insertZoomFrame(int index, float x, float y, float width, float height, [Slide](../../slide) slide, [PPImage](../../ppimage) image)  function

 Creates a new Zoom object and inserts it to a collection at the specified index.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Zoom frame should be inserted. |
| x | float | X coordinate of a new Zoom frame {@code float}. |
| y | float | Y coordinate of a new Zoom frame {@code float}. |
| width | float | Width of a new Zoom frame {@code float}. |
| height | float | Height of a new Zoom frame {@code float}. |
| slide | [Slide](../slide) | The slide object referenced by the Zoom frame ISlide. |
| image | [PPImage](../../ppimage) | The image for the referenced slide IPPImage |

### Result
[ZoomFrame](../../zoomframe)

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced slide does not belong to the current presentation. |


---


