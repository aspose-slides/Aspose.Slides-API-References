---
title: AlignShapes()
second_title: Aspose.Slides برای C++ مرجع API
description: محل قرارگیری تمام اشکال روی اسلاید را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید هم‌تراز می‌کند یا نسبت به یکدیگر هم‌تراز می‌سازد.
type: docs
weight: 27
url: /fa/aspose.slides.util/slideutil/alignshapes/
---
## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>) متد

محل قرارگیری تمام اشکال روی اسلاید را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید هم‌تراز می‌کند یا نسبت به یکدیگر هم‌تراز می‌سازد.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | مشخص می‌کند که چه نوع هم‌ترازی اعمال خواهد شد. |
| alignToSlide | **bool** | اگر true باشد، اشکال نسبت به لبه‌های اسلاید هم‌تراز می‌شوند. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | اسلاید والد. |

## توضیحات

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignBottom, true, pres->get_Slides()->idx_get(0));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IBaseSlide\>, System::ArrayPtr\<int32_t\>) متد

محل قرارگیری اشکال انتخاب شده روی اسلاید را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید هم‌تراز می‌کند یا نسبت به یکدیگر هم‌تراز می‌سازد.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IBaseSlide> slide, System::ArrayPtr<int32_t> shapeIndexes)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | مشخص می‌کند که چه نوع هم‌ترازی اعمال خواهد شد. |
| alignToSlide | **bool** | اگر true باشد، اشکال نسبت به لبه‌های اسلاید هم‌تراز می‌شوند. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | اسلاید والد. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | شاخص‌های اشکالی که باید هم‌تراز شوند. |

## توضیحات

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

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>) متد

محل قرارگیری تمام اشکال داخل شکل گروه را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید هم‌تراز می‌کند یا نسبت به یکدیگر هم‌تراز می‌سازد.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | مشخص می‌کند که چه نوع هم‌ترازی اعمال خواهد شد. |
| alignToSlide | **bool** | اگر true باشد، اشکال نسبت به لبه‌های اسلاید هم‌تراز می‌شوند. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | شکل گروه والد. |

## توضیحات

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()));
```

## SlideUtil::AlignShapes(ShapesAlignmentType, bool, System::SharedPtr\<IGroupShape\>, System::ArrayPtr\<int32_t\>) متد

محل قرارگیری اشکال انتخاب شده داخل شکل گروه را تغییر می‌دهد. اشکال را به حاشیه‌ها یا لبه اسلاید هم‌تراز می‌کند یا نسبت به یکدیگر هم‌تراز می‌سازد.

```cpp
static void Aspose::Slides::Util::SlideUtil::AlignShapes(ShapesAlignmentType alignmentType, bool alignToSlide, System::SharedPtr<IGroupShape> groupShape, System::ArrayPtr<int32_t> shapeIndexes)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| alignmentType | [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/) | مشخص می‌کند که چه نوع هم‌ترازی اعمال خواهد شد. |
| alignToSlide | **bool** | اگر true باشد، اشکال نسبت به لبه‌های اسلاید هم‌تراز می‌شوند. |
| groupShape | [System::SharedPtr](../../../system/sharedptr/)\<[IGroupShape](../../../aspose.slides/igroupshape/)\> | شکل گروه والد. |
| shapeIndexes | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | شاخص‌های اشکالی که باید هم‌تراز شوند. |

## توضیحات

مثال: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

SlideUtil::AlignShapes(ShapesAlignmentType::AlignLeft, false, System::ExplicitCast<GroupShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)), System::MakeArray<int32_t>({0, 2}));
```

## موارد مرتبط

* Enum [ShapesAlignmentType](../../../aspose.slides/shapesalignmenttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [SlideUtil](../)
* Class [IGroupShape](../../../aspose.slides/igroupshape/)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)