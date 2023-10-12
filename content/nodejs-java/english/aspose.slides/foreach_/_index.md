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
 
###ForEach_{#ForEach_}

| Name | Description |
| --- | --- |
| ForEach_() |  |

 **Result**
ForEach_


---


###layoutSlide{#layoutSlide}

| Name | Description |
| --- | --- |
| layoutSlide ([Presentation](../presentation), [ForEach_.ForEachLayoutSlideCallback](../foreach_.foreachlayoutslidecallback)) | Iterate each #layoutSlide(Presentation,ForEachLayoutSlideCallback) in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation to iterate layout slides |
| forEachLayoutSlide | [ForEach_.ForEachLayoutSlideCallback](../foreach_.foreachlayoutslidecallback) | Callback that will be invoked for each layout slide |


---


###masterSlide{#masterSlide}

| Name | Description |
| --- | --- |
| masterSlide ([Presentation](../presentation), [ForEach_.ForEachMasterSlideCallback](../foreach_.foreachmasterslidecallback)) | Iterate each #masterSlide(Presentation,ForEachMasterSlideCallback) in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation to iterate master slides |
| forEachMasterSlide | [ForEach_.ForEachMasterSlideCallback](../foreach_.foreachmasterslidecallback) | Callback that will be invoked for each master slide |


---


###paragraph{#paragraph}

| Name | Description |
| --- | --- |
| paragraph ([Presentation](../presentation), [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback)) | Iterate each Paragraph in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation to iterate paragraphs |
| forEachParagraph | [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback) | Callback that will be invoked for each paragraph Shapes will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) and #layoutSlide(Presentation,ForEachLayoutSlideCallback) |


---


###paragraph{#paragraph}

| Name | Description |
| --- | --- |
| paragraph ([Presentation](../presentation), boolean, [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback)) | Iterate each Paragraph in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation to iterate paragraphs |
| includeNotes | boolean | Flag that indicates whether NotesSlides should be included in processing. |
| forEachParagraph | [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback) | Callback that will be invoked for each paragraph Shapes will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback), #layoutSlide(Presentation,ForEachLayoutSlideCallback) and NotesSlide |


---


###portion{#portion}

| Name | Description |
| --- | --- |
| portion ([Presentation](../presentation), [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback)) | Iterate each Portion in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation to iterate portions |
| forEachPortion | [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback) | Callback that will be invoked for each portion Portions will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) and #layoutSlide(Presentation,ForEachLayoutSlideCallback) |


---


###portion{#portion}

| Name | Description |
| --- | --- |
| portion ([Presentation](../presentation), boolean, [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback)) | Iterate each Portion in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation to iterate portions |
| includeNotes | boolean | Flag that indicates whether NotesSlides should be included in processing. |
| forEachPortion | [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback) | Callback that will be invoked for each portion Portions will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback), #layoutSlide(Presentation,ForEachLayoutSlideCallback) and NotesSlide |


---


###shape{#shape}

| Name | Description |
| --- | --- |
| shape ([Presentation](../presentation), [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback)) | Iterate each Shape in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation to iterate layout shapes |
| forEachShape | [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback) | Callback that will be invoked for each shape Shapes will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) and #layoutSlide(Presentation,ForEachLayoutSlideCallback) |


---


###shape{#shape}

| Name | Description |
| --- | --- |
| shape ([Presentation](../presentation), boolean, [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback)) | Iterate each Shape in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation to iterate layout shapes |
| includeNotes | boolean | Flag that indicates whether NotesSlides should be included in processing. |
| forEachShape | [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback) | Callback that will be invoked for each shape Shapes will be iterated in all type of slides - #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback), #layoutSlide(Presentation,ForEachLayoutSlideCallback) and NotesSlide if needed. |


---


###shape{#shape}

| Name | Description |
| --- | --- |
| shape ([BaseSlide](../baseslide), [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback)) | Iterate each Shape in the BaseSlide. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| baseSlide | [BaseSlide](../baseslide) | Slide to iterate layout shapes |
| forEachShape | [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback) | Callback that will be invoked for each shape BaseSlide is the base type for #slide(Presentation,ForEachSlideCallback), #masterSlide(Presentation,ForEachMasterSlideCallback) and #layoutSlide(Presentation,ForEachLayoutSlideCallback) |


---


###slide{#slide}

| Name | Description |
| --- | --- |
| slide ([Presentation](../presentation), [ForEach_.ForEachSlideCallback](../foreach_.foreachslidecallback)) | Iterate each #slide(Presentation,ForEachSlideCallback) in the Presentation. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Presentation to iterate slides |
| forEachSlide | [ForEach_.ForEachSlideCallback](../foreach_.foreachslidecallback) | Callback that will be invoked for each slide |


---


