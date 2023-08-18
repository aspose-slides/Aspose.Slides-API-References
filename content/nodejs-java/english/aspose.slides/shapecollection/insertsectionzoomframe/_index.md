---
title: insertSectionZoomFrame
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/shapecollection/insertsectionzoomframe/
---

## insertSectionZoomFrame(int index, float x, float y, float width, float height, [Section](../../section) section)  function

 Creates a new Section Zoom object and inserts into to a collection at the specified index.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Section Zoom frame should be inserted. |
| x | float | X coordinate of a new Section Zoom frame {@code float}. |
| y | float | Y coordinate of a new Section Zoom frame {@code float}. |
| width | float | Width of a new Section Zoom frame {@code float}. |
| height | float | Height of a new Section Zoom frame {@code float}. |
| section | [Section](../../section) | The slide object referenced by the Section Zoom frame ISection. |

### Result
[SectionZoomFrame](../../sectionzoomframe), [SummaryZoomSection](../../summaryzoomsection)

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


## insertSectionZoomFrame(int index, float x, float y, float width, float height, [Section](../../section) section, [PPImage](../../ppimage) image)  function

 Creates a new Section Zoom object and inserts it to a collection at the specified index.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which Section Zoom frame should be inserted. |
| x | float | X coordinate of a new Section Zoom frame {@code float}. |
| y | float | Y coordinate of a new Section Zoom frame {@code float}. |
| width | float | Width of a new Section Zoom frame {@code float}. |
| height | float | Height of a new Section Zoom frame {@code float}. |
| section | [Section](../section) | The slide object referenced by the Section Zoom frame ISection. |
| image | [PPImage](../../ppimage) | The image for the referenced slide IPPImage |

### Result
[SectionZoomFrame](../../sectionzoomframe), [SummaryZoomSection](../../summaryzoomsection)

### Error

| Error | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


