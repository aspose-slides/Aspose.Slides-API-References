---
title: AddClone()
second_title: Aspose.Slides for C++ API Reference
description: Adds a copy of a specified layout slide to the presentation.
type: docs
weight: 1
url: /aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method


Adds a copy of a specified layout slide to the presentation.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) to clone. |

### Return Value

Added slide.
## Remarks



When cloning a layout between different presentations layout's master can be cloned too to keep source formatting. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. 
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) method


Adds a copy of a specified layout slide to the presentation.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) to clone. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide for a new layout. |

### Return Value

Added slide.
## Remarks



New layout will be linked with defined master in destination presentation. So this is analogue of copy/paste with \"Use Destination Theme\" option in PowerPoint. 
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IGlobalLayoutSlideCollection](../)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)