---
title: Remove()
second_title: Aspose.Slides for C++ API Reference
description: Removes layout from presentation.
type: docs
weight: 105
url: /aspose.slides/ilayoutslide/remove/
---
## ILayoutSlide::Remove() method


Removes layout from presentation.

```cpp
virtual void Aspose::Slides::ILayoutSlide::Remove()=0
```


### Exceptions

| Exception | Description |
| --- | --- |
| [Aspose::Slides::PptxEditException](../../pptxeditexception/) | Thrown if layout is already removed from presentation or if layout is used in presentation (its HasDependingSlides property is true). |

## Remarks



To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 
## See Also

* Class [ILayoutSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)