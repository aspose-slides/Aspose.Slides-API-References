---
title: Remove()
second_title: Aspose.Slides for C++ API Reference
description: Removes a layout from the collection.
type: docs
weight: 27
url: /aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) method


Removes a layout from the collection.

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
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
* Class [ILayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)