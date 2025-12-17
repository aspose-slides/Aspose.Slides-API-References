---
title: AlignShapes()
second_title: Aspose.Slides for C++ API Reference
description: Changes the placement of all shapes on the slide. Aligns shapes to the margins or the edge of the slide or align them relative to each other.
type: docs
weight: 27
url: /aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) method


Changes the placement of all shapes on the slide. Aligns shapes to the margins or the edge of the slide or align them relative to each other.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Determines which type of alignment will be applied. |
| alignToSlide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Parent slide. |
## Remarks



Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) method


Changes the placement of selected shapes on the slide. Aligns shapes to the margins or the edge of the slide or align them relative to each other.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Determines which type of alignment will be applied. |
| alignToSlide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Parent slide. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Indexes of shapes to be aligned. |
## Remarks



Example: 
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto slide = pres->get_Slides()->idx_get(0);
auto shape1 = slide->get_Shapes()->idx_get(0);
auto shape2 = slide->get_Shapes()->idx_get(1);
SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, false, pres->get_Slides()->idx_get(0),
    System::MakeArray<int32_t>({
        slide->get_Shapes()->IndexOf(shape1),
        slide->get_Shapes()->IndexOf(shape2)
    }));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) method


Changes the placement of all shapes within group shape. Aligns shapes to the margins or the edge of the slide or align them relative to each other.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Determines which type of alignment will be applied. |
| alignToSlide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Parent group shape. |
## Remarks



Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) method


Changes the placement of selected shapes within group shape. Aligns shapes to the margins or the edge of the slide or align them relative to each other.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | Determines which type of alignment will be applied. |
| alignToSlide | **bool** | If true, shapes will be aligned relative to the slide edges. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | Parent group shape. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Indexes of shapes to be aligned. |
## Remarks



Example: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## See Also

* Enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [SlideUtil](../)
* Class [IGroupShape](../../../aspose.slides/igroupshape/)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)