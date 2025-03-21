---
title: AddClone()
second_title: Aspose.Slides for C++ API Reference
description: Adds a copy of a specified layout slide to the end of the collection.
type: docs
weight: 1
url: /aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method


Adds a copy of a specified layout slide to the end of the collection.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) to clone. |

### Return Value

Added slide.
## Remarks



1) New layout will be linked with parent master slide for this layout slides collection. So this is analogue of copy/paste with \"Use Destination Theme\" option in PowerPoint. 2) Analogue of this method is method [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) accessed with [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/) property. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)