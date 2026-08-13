---
title: AlignShapes()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 슬라이드에 있는 모든 도형의 위치를 변경합니다. 도형을 여백이나 슬라이드 가장자리에 맞추거나 서로 상대적으로 정렬합니다.
type: docs
weight: 27
url: /ko/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) 메서드


슬라이드에 있는 모든 도형의 위치를 변경합니다. 도형을 슬라이드의 여백이나 가장자리에 맞추거나 서로 상대적으로 정렬합니다.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 적용될 정렬 유형을 결정합니다. |
| alignToSlide | **bool** | true이면 도형이 슬라이드 가장자리를 기준으로 정렬됩니다. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 부모 슬라이드입니다. |
## 비고



예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) 메서드


슬라이드에서 선택된 도형의 위치를 변경합니다. 도형을 슬라이드의 여백이나 가장자리에 맞추거나 서로 상대적으로 정렬합니다.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 적용될 정렬 유형을 결정합니다. |
| alignToSlide | **bool** | true이면 도형이 슬라이드 가장자리를 기준으로 정렬됩니다. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 부모 슬라이드입니다. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 정렬할 도형의 인덱스입니다. |
## 비고



예시: 
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

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) 메서드


그룹 도형 내 모든 도형의 위치를 변경합니다. 도형을 슬라이드의 여백이나 가장자리에 맞추거나 서로 상대적으로 정렬합니다.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 적용될 정렬 유형을 결정합니다. |
| alignToSlide | **bool** | true이면 도형이 슬라이드 가장자리를 기준으로 정렬됩니다. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | 부모 그룹 도형입니다. |
## 비고



예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) 메서드


그룹 도형 내 선택된 도형의 위치를 변경합니다. 도형을 슬라이드의 여백이나 가장자리에 맞추거나 서로 상대적으로 정렬합니다.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 적용될 정렬 유형을 결정합니다. |
| alignToSlide | **bool** | true이면 도형이 슬라이드 가장자리를 기준으로 정렬됩니다. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | 부모 그룹 도형입니다. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 정렬할 도형의 인덱스입니다. |
## 비고



예시: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## 참조

* Enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [SlideUtil](../)
* Class [IGroupShape](../../../aspose.slides/igroupshape/)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)