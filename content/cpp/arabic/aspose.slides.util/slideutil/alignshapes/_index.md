---
title: AlignShapes()
second_title: مرجع API Aspose.Slides للغة C++
description: يغيّر موضع جميع الأشكال على الشريحة. يُمحّص الأشكال إلى الهوامش أو إلى حافة الشريحة أو يضبطها بالنسبة لبعضها البعض.
type: docs
weight: 27
url: /ar/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) طريقة


يغيّر موضع جميع الأشكال على الشريحة. يُمحّص الأشكال إلى الهوامش أو حافة الشريحة أو يضبطها بالنسبة لبعضها البعض.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```


### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | يحدد أي نوع من المحاذاة سيتم تطبيقه. |
| alignToSlide | **bool** | إذا كان true، سيتم محاذاة الأشكال بالنسبة إلى حواف الشريحة. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | الشريحة الأم. |
## ملاحظات



مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) طريقة


يغيّر موضع جميع الأشكال على الشريحة. يُمحّص الأشكال إلى الهوامش أو حافة الشريحة أو يضبطها بالنسبة لبعضها البعض.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```


### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | يحدد أي نوع من المحاذاة سيتم تطبيقه. |
| alignToSlide | **bool** | إذا كان true، سيتم محاذاة الأشكال بالنسبة إلى حواف الشريحة. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | الشريحة الأم. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | فهارس الأشكال التي سيتم محاذاتها. |
## ملاحظات



مثال: 
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

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) طريقة


يغيّر موضع جميع الأشكال داخل شكل المجموعة. يُمحّص الأشكال إلى الهوامش أو حافة الشريحة أو يضبطها بالنسبة لبعضها البعض.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```


### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | يحدد أي نوع من المحاذاة سيتم تطبيقه. |
| alignToSlide | **bool** | إذا كان true، سيتم محاذاة الأشكال بالنسبة إلى حواف الشريحة. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | شكل المجموعة الأم. |
## ملاحظات



مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) طريقة


يغيّر موضع الأشكال المختارة داخل شكل المجموعة. يُمحّص الأشكال إلى الهوامش أو حافة الشريحة أو يضبطها بالنسبة لبعضها البعض.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```


### وسائط

| معامل | نوع | وصف |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | يحدد أي نوع من المحاذاة سيتم تطبيقه. |
| alignToSlide | **bool** | إذا كان true، سيتم محاذاة الأشكال بالنسبة إلى حواف الشريحة. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | شكل المجموعة الأم. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | فهارس الأشكال التي سيتم محاذاتها. |
## ملاحظات



مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## انظر أيضًا

* تعداد [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* تعريف_نوع [SharedPtr](../../../system/sharedptr/)
* تعريف_نوع [ArrayPtr](../../../system/arrayptr/)
* فئة [IBaseSlide](../../../aspose.slides/ibaseslide/)
* فئة [SlideUtil](../)
* فئة [IGroupShape](../../../aspose.slides/igroupshape/)
* نطاق [Aspose::Slides::Util](../../)
* مكتبة [Aspose.Slides](../../../)