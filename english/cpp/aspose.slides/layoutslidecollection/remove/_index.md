---
title: Remove()
second_title: Aspose.Slides for C++ API Reference
description: Removes a layout from the collection.
type: docs
weight: 66
url: /cpp/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) method


Removes a layout from the collection.

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | The layout slide to remove from the collection. |
## Remarks



1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also [ILayoutSlide::Remove](../../ilayoutslide/remove/) method to simplify code. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [LayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)