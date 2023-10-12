---
title: ForEach_
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/foreach_/
---

## ForEach_ class

 Represents a group of methods intended to iterate over different  Presentation model objects.
 These methods can be useful if you need to iterate and change some Presentation' elements formatting or content,
  e.g. change each portion formatting. 
 
| [ForEach_]() |  |

### Result
ForEach_


---


| [layoutSlide] ([Presentation], [ForEach_.ForEachLayoutSlideCallback]) | Iterate each #layoutSlide(Presentation,ForEachLayoutSlideCallback) in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation] | Presentation to iterate layout slides |
| forEachLayoutSlide | [ForEach_.ForEachLayoutSlideCallback] | Callback that will be invoked for each layout slide |


---


| [masterSlide] ([Presentation], [ForEach_.ForEachMasterSlideCallback]) | Iterate each #masterSlide(Presentation,ForEachMasterSlideCallback) in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation] | Presentation to iterate master slides |
| forEachMasterSlide | [ForEach_.ForEachMasterSlideCallback] | Callback that will be invoked for each master slide |


---


| [paragraph] ([Presentation], [ForEach_.ForEachParagraphCallback]) | Iterate each Paragraph in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation] | Presentation to iterate paragraphs |
| forEachParagraph | [ForEach_.ForEachParagraphCallback] | Callback that will be invoked for each paragraph Shapes will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) and #layoutSlide(Presentation,ForEachLayoutSlideCallback) |


---


| [paragraph] ([Presentation], [boolean], [ForEach_.ForEachParagraphCallback]) | Iterate each Paragraph in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation] | Presentation to iterate paragraphs |
| includeNotes | [boolean] | Flag that indicates whether NotesSlides should be included in processing. |
| forEachParagraph | [ForEach_.ForEachParagraphCallback] | Callback that will be invoked for each paragraph Shapes will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback), #layoutSlide(Presentation,ForEachLayoutSlideCallback) and NotesSlide |


---


| [portion] ([Presentation], [ForEach_.ForEachPortionCallback]) | Iterate each Portion in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation] | Presentation to iterate portions |
| forEachPortion | [ForEach_.ForEachPortionCallback] | Callback that will be invoked for each portion Portions will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) and #layoutSlide(Presentation,ForEachLayoutSlideCallback) |


---


| [portion] ([Presentation], [boolean], [ForEach_.ForEachPortionCallback]) | Iterate each Portion in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation] | Presentation to iterate portions |
| includeNotes | [boolean] | Flag that indicates whether NotesSlides should be included in processing. |
| forEachPortion | [ForEach_.ForEachPortionCallback] | Callback that will be invoked for each portion Portions will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback), #layoutSlide(Presentation,ForEachLayoutSlideCallback) and NotesSlide |


---


| [shape] ([Presentation], [ForEach_.ForEachShapeCallback]) | Iterate each Shape in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation] | Presentation to iterate layout shapes |
| forEachShape | [ForEach_.ForEachShapeCallback] | Callback that will be invoked for each shape Shapes will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) and #layoutSlide(Presentation,ForEachLayoutSlideCallback) |


---


| [shape] ([Presentation], [boolean], [ForEach_.ForEachShapeCallback]) | Iterate each Shape in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation] | Presentation to iterate layout shapes |
| includeNotes | [boolean] | Flag that indicates whether NotesSlides should be included in processing. |
| forEachShape | [ForEach_.ForEachShapeCallback] | Callback that will be invoked for each shape Shapes will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback), #layoutSlide(Presentation,ForEachLayoutSlideCallback) and NotesSlide if needed. |


---


| [shape] ([BaseSlide], [ForEach_.ForEachShapeCallback]) | Iterate each Shape in the BaseSlide. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| baseSlide | [BaseSlide] | Slide to iterate layout shapes |
| forEachShape | [ForEach_.ForEachShapeCallback] | Callback that will be invoked for each shape BaseSlide is the base type for #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) and #layoutSlide(Presentation,ForEachLayoutSlideCallback) |


---


| [slide] ([Presentation], [ForEach_.ForEachSlideCallback]) | Iterate each #slide(Presentation,ForEachSlideCallback) in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation] | Presentation to iterate slides |
| forEachSlide | [ForEach_.ForEachSlideCallback] | Callback that will be invoked for each slide |


---


