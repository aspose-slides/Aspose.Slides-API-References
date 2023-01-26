---
title: addSectionZoomFrame
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 200
url: /php-java/aspose.slides/shapecollection/addsectionzoomframe/
---

## addSectionZoomFrame(float x, float y, float width, float height, [Section](../../section) section)  method

 Adds a new Section Zoom object to the end of a collection.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new Section Zoom frame {@code float}. |
| y | float | Y coordinate of a new Section Zoom frame {@code float}. |
| width | float | Width of a new Section Zoom frame {@code float}. |
| height | float | Height of a new Section Zoom frame {@code float}. |
| section | [Section](../../section) | The section object referenced by the Section Zoom frame ISection. |

### Returns
[SectionZoomFrame](../../sectionzoomframe), [SummaryZoomSection](../../summaryzoomsection)

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


## addSectionZoomFrame(float x, float y, float width, float height, [Section](../../section) section, [PPImage](../../ppimage) image)  method

 Adds a new Section Zoom object to the end of a collection with a predefined image.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| x | float | X coordinate of a new Section Zoom frame {@code float}. |
| y | float | Y coordinate of a new Section Zoom frame {@code float}. |
| width | float | Width of a new Section Zoom frame {@code float}. |
| height | float | Height of a new Section Zoom frame {@code float}. |
| section | [Section](../section) | The section object referenced by the Section Zoom frame ISection. |
| image | [PPImage](../../ppimage) | The image for the referenced slide IPPImage |

### Returns
[SectionZoomFrame](../../sectionzoomframe), [SummaryZoomSection](../../summaryzoomsection)

### Exception

| Exception | Condition |
| --- | --- |
 | ArgumentException | Referenced section does not belong to the current presentation or does not contains any slides. |


---


