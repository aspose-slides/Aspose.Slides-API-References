---
title: AddClone()
second_title: Aspose.Slides for C++ API Reference
description: Adds a copy of a specified slide to the end of the collection.
type: docs
weight: 53
url: /aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) method


Adds a copy of a specified slide to the end of the collection.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) to clone. |

### Return Value

New slide.
## Remarks



When cloning a slide between different presentations slide's master can be cloned too. Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide. Manual cloning of master slides will be neither prevented nor registered. If you need more control over cloning process use [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) or [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) for cloning slides, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) or [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) for cloning layouts and [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) for cloning masters. 
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) method


Adds a copy of a specified slide to the end of the specified section.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) to clone. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) for a new slide. |

### Return Value

New slide.
## Remarks



```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Now the second section contains a copy of the first slide.
```


## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method


Adds a copy of a specified slide to the end of the collection.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) to clone. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layout slide for a new slide. |

### Return Value

New slide.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method


Adds a copy of a specified source slide to the end of the collection. Appropriate layout will be selected automatically from the specified master (appropriate layout is the layout with the same Type or Name as of layout of the source slide). If there is no appropriate layout then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) to clone. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide for a new slide. |
| allowCloneMissingLayout | **bool** | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Return Value

New slide.

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [SlideCollection](../)
* Class [ISection](../../isection/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)