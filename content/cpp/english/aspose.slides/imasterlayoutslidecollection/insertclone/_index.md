---
title: InsertClone()
second_title: Aspose.Slides for C++ API Reference
description: Inserts a copy of a specified layout slide to specified position of the collection.
type: docs
weight: 14
url: /aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) method


Inserts a copy of a specified layout slide to specified position of the collection.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index of new slide. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) to clone. |

### Return Value

Inserted slide.
## Remarks



New layout will be linked with parent master slide for this layout slides collection. So this is analogue of copy/paste with \"Use Destination Theme\" option in PowerPoint. 

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)