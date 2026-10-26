---
title: AlignShapes()
second_title: Aspose.Slides for C++ API 参考
description: 更改幻灯片上所有形状的位置。将形状对齐到边距或幻灯片的边缘，或相互对齐。
type: docs
weight: 27
url: /zh/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) 方法

更改幻灯片上所有形状的位置。将形状对齐到边距或幻灯片的边缘，或相互对齐。

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 确定将应用哪种对齐方式。 |
| alignToSlide | **bool** | 为 true 时，形状将相对于幻灯片边缘对齐。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 父幻灯片。 |
## 备注

示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) 方法

更改幻灯片上所选形状的位置。将形状对齐到边距或幻灯片的边缘，或相互对齐。

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 确定将应用哪种对齐方式。 |
| alignToSlide | **bool** | 为 true 时，形状将相对于幻灯片边缘对齐。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 父幻灯片。 |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 要对齐的形状索引。 |
## 备注

示例： 
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

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) 方法

更改组形状内所有形状的位置。将形状对齐到边距或幻灯片的边缘，或相互对齐。

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 确定将应用哪种对齐方式。 |
| alignToSlide | **bool** | 为 true 时，形状将相对于幻灯片边缘对齐。 |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | 父组形状。 |
## 备注

示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) 方法

更改组形状内所选形状的位置。将形状对齐到边距或幻灯片的边缘，或相互对齐。

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 确定将应用哪种对齐方式。 |
| alignToSlide | **bool** | 为 true 时，形状将相对于幻灯片边缘对齐。 |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | 父组形状。 |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 要对齐的形状索引。 |
## 备注

示例： 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## 另请参见

* 枚举 [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类型定义 [ArrayPtr](../../../system/arrayptr/)
* 类 [IBaseSlide](../../../aspose.slides/ibaseslide/)
* 类 [SlideUtil](../)
* 类 [IGroupShape](../../../aspose.slides/igroupshape/)
* 命名空间 [Aspose::Slides::Util](../../)
* 库 [Aspose.Slides](../../../)