---
title: AddClone()
second_title: Aspose.Slides for C++ API Reference
description: Adds a copy of a specified layout slide to the presentation.
type: docs
weight: 1
url: /cpp/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method


Adds a copy of a specified layout slide to the presentation.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) to clone. |

### Return Value

Added slide.
## Remarks



When cloning a layout between different presentations layout's master can be cloned too to keep source formatting. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. 
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) method


Adds a copy of a specified layout slide to the presentation.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) to clone. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide for a new layout. |

### Return Value

Added slide.
## Remarks



1) New layout will be linked with defined master in destination presentation. So this is analogue of copy/paste with \"Use Destination Theme\" option in PowerPoint. 2) Analogue of this method is method [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) accessed with [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) property. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [GlobalLayoutSlideCollection](../)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)