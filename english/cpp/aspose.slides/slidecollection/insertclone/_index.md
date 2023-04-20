---
title: InsertClone()
second_title: Aspose.Slides for C++ API Reference
description: Inserts a copy of a specified slide to specified position of the collection.
type: docs
weight: 66
url: /cpp/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) method


Inserts a copy of a specified slide to specified position of the collection.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index of new slide. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) to clone. |

### Return Value

Inserted slide.
## Remarks



When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) or [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) for cloning slides and [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) for cloning masters. 


The following example shows how to clone at another position within [Presentation](../../presentation/). 
```cpp
// Instantiate Presentation class that represents a presentation file
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Clone the desired slide to the end of the collection of slides in the same presentation
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Clone the desired slide to the specified index in the same presentation
slides->InsertClone(2, slides->idx_get(1));
// Write the modified presentation to disk
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
 The following example shows how to clone at another position within [Presentation](../../presentation/). 
```cpp
// Instantiate Presentation class to load the source presentation file
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Instantiate Presentation class for destination PPTX (where slide is to be cloned)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Write the destination presentation to disk
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method


Inserts a copy of a specified slide to specified position of the collection.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index of new slide. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) to clone. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layout slide for a new slide. |

### Return Value

Inserted slide.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method


Inserts a copy of a specified source slide to specified position of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | Index of new slide. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) to clone. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide for a new slide. |
| allowCloneMissingLayout | **bool** | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Return Value

Inserted slide.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [SlideCollection](../)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)