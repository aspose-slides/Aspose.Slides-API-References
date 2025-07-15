---
title: Ink
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/ink/
---

## Ink class

 Represents an ink object on a slide.
 
### getInkEffectImages {#getInkEffectImages}

| Name | Description |
| --- | --- |
| getInkEffectImages () | Gets the collection of custom images used to simulate visual effects for ink brushes. These images are used when rendering ink with specific InkEffectType values, such as Galaxy, Rainbow, etc. By providing your own images, you can control how each ink effect appears. This property allows replacing the default ink effect textures with user-defined ones, which is particularly useful when default assets are restricted by licensing or unavailable at runtime. Each entry in the dictionary must associate an InkEffectType value with a corresponding IImage object (e.g., Bitmap, or an Aspose image interface). |

 **Returns:**
SortedDictionary, SortedList, Dictionary


---


### getTraces {#getTraces}

| Name | Description |
| --- | --- |
| getTraces () | Gets all traces containing in the IInk element IInkTrace. Read-only. |

 **Returns:**
[InkTrace](../inktrace)


---


