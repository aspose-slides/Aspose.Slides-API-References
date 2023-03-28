---
title: InsertClone()
second_title: Aspose.Slides for C++ API Reference
description: Inserts a copy of a specified master slide to specified position of the collection. Linked layout slides will be copied too.
type: docs
weight: 66
url: /cpp/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(**int32_t**, [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\>) method


Inserts a copy of a specified master slide to specified position of the collection. Linked layout slides will be copied too.

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index of new slide. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) to clone. |

### Return Value

Inserted master slide.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlide](../../imasterslide/)
* Class [IMasterSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
