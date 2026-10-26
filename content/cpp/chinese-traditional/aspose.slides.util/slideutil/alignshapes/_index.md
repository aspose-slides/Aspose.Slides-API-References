---
title: AlignShapes()
second_title: Aspose.Slides for C++ API 參考文件
description: 變更投影片上所有形狀的位置。將形狀對齊至投影片的邊緣或邊框，或相互之間對齊。
type: docs
weight: 27
url: /zh-hant/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) 方法

變更投影片上所有形狀的位置。將形狀對齊至投影片的邊緣或邊框，或相互之間對齊。

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 決定要套用哪一種對齊類型。 |
| alignToSlide | **bool** | 若為 true，形狀將相對於投影片邊緣對齊。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 父投影片。 |
## 備註



範例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) 方法

變更投影片上所選形狀的位置。將形狀對齊至投影片的邊緣或邊框，或相互之間對齊。

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 決定要套用哪一種對齊類型。 |
| alignToSlide | **bool** | 若為 true，形狀將相對於投影片邊緣對齊。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 父投影片。 |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 要對齊的形狀索引。 |
## 備註



範例: 
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

變更群組形狀內所有形狀的位置。將形狀對齊至投影片的邊緣或邊框，或相互之間對齊。

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 決定要套用哪一種對齊類型。 |
| alignToSlide | **bool** | 若為 true，形狀將相對於投影片邊緣對齊。 |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | 父群組形狀。 |
## 備註



範例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) 方法

變更群組形狀內所選形狀的位置。將形狀對齊至投影片的邊緣或邊框，或相互之間對齊。

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 決定要套用哪一種對齊類型。 |
| alignToSlide | **bool** | 若為 true，形狀將相對於投影片邊緣對齊。 |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | 父群組形狀。 |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 要對齊的形狀索引。 |
## 備註



範例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## 另請參閱

* 列舉 [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 型別別名 [ArrayPtr](../../../system/arrayptr/)
* 類別 [IBaseSlide](../../../aspose.slides/ibaseslide/)
* 類別 [SlideUtil](../)
* 類別 [IGroupShape](../../../aspose.slides/igroupshape/)
* 名稱空間 [Aspose::Slides::Util](../../)
* 程式庫 [Aspose.Slides](../../../)