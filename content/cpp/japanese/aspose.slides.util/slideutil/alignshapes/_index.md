---
title: AlignShapes()
second_title: Aspose.Slides for C++ API リファレンス
description: スライド上のすべての図形の配置を変更します。図形を余白またはスライドの端に揃えるか、互いに相対的に揃えます。
type: docs
weight: 27
url: /ja/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) メソッド

スライド上のすべての図形の配置を変更します。図形をスライドの余白または端に揃えるか、互いに相対的に揃えます。

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 適用される整列の種類を決定します。 |
| alignToSlide | **bool** | true の場合、図形はスライドの端に対して揃えられます。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 親スライド。 |

## 備考



例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) メソッド

スライド上の選択された図形の配置を変更します。図形をスライドの余白または端に揃えるか、互いに相対的に揃えます。

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 適用される整列の種類を決定します。 |
| alignToSlide | **bool** | true の場合、図形はスライドの端に対して揃えられます。 |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 親スライド。 |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 揃える図形のインデックス。 |

## 備考



例:
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

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) メソッド

グループ形状内のすべての図形の配置を変更します。図形をスライドの余白または端に揃えるか、互いに相対的に揃えます。

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 適用される整列の種類を決定します。 |
| alignToSlide | **bool** | true の場合、図形はスライドの端に対して揃えられます。 |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | 親グループ形状。 |

## 備考



例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) メソッド

グループ形状内の選択された図形の配置を変更します。図形をスライドの余白または端に揃えるか、互いに相対的に揃えます。

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | 適用される整列の種類を決定します。 |
| alignToSlide | **bool** | true の場合、図形はスライドの端に対して揃えられます。 |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | 親グループ形状。 |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 揃える図形のインデックス。 |

## 備考



例:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## 参照

* 列挙体 [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* 型エイリアス [SharedPtr](../../../system/sharedptr/)
* 型エイリアス [ArrayPtr](../../../system/arrayptr/)
* クラス [IBaseSlide](../../../aspose.slides/ibaseslide/)
* クラス [SlideUtil](../)
* クラス [IGroupShape](../../../aspose.slides/igroupshape/)
* 名前空間 [Aspose::Slides::Util](../../)
* ライブラリ [Aspose.Slides](../../../)