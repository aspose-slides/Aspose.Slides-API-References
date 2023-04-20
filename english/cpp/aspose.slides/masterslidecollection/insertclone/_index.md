---
title: InsertClone()
second_title: Aspose.Slides for C++ API Reference
description: Inserts a copy of a specified master slide to specified position of the collection. Linked layout slides will be copied too.
type: docs
weight: 105
url: /cpp/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) method


Inserts a copy of a specified master slide to specified position of the collection. Linked layout slides will be copied too.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index of new slide. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) to clone. |

### Return Value

Inserted master slide.
## Remarks



The following example shows how to clone master slide in another PowerPoint [Presentation](../../presentation/). 
```cpp
// Instantiate Presentation class to load the source presentation file
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// Instantiate Presentation class for destination presentation (where slide is to be cloned)
auto destPres = System::MakeObject<Presentation>();

// Instantiate ISlide from the collection of slides in source presentation along with
// Master slide
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// Get Master Slides of destination presentation
auto masters = destPres->get_Masters();
// Clone the desired master slide from the source presentation to the collection of masters in the
// Destination presentation
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Collection of slides in the destination presentation
auto slides = destPres->get_Slides();
// Clone source slide to destination slides collection.
slides->AddClone(sourceSlide, iSlide, true);
// Save the destination presentation to disk
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlide](../../imasterslide/)
* Class [MasterSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)