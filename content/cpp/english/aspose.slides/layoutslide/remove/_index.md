---
title: Remove()
second_title: Aspose.Slides for C++ API Reference
description: Removes layout from presentation.
type: docs
weight: 131
url: /aspose.slides/layoutslide/remove/
---
## LayoutSlide::Remove() method


Removes layout from presentation.

```cpp
void Aspose::Slides::LayoutSlide::Remove() override
```


### Exceptions

| Exception | Description |
| --- | --- |
| PptxEditException | Thrown if layout is already removed from presentation or if layout is used in presentation (its HasDependingSlides property is true). |

## Remarks



To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 
## See Also

* Class [LayoutSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)