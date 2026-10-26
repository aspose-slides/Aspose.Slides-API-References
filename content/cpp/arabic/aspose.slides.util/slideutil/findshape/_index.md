---
title: FindShape()
second_title: Aspose.Slides مرجع API لـ C++
description: ابحث عن الشكل باستخدام النص البديل في عرض تقديمي بصيغة PPTX.
type: docs
weight: 1
url: /ar/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) طريقة

ابحث عن الشكل بواسطة النص البديل في عرض تقديمي بصيغة PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | العرض الممسوح. |
| altText | [System::String](../../../system/string/) | النص البديل لشكل. |

### قيمة الإرجاع

[Shape](../../../aspose.slides/shape/) أو null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) طريقة

ابحث عن الشكل بواسطة النص البديل على شريحة في عرض تقديمي بصيغة PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | الشريحة الممسوحة. |
| altText | [System::String](../../../system/string/) | النص البديل لشكل. |

### قيمة الإرجاع

[Shape](../../../aspose.slides/shape/) أو null.

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IShape](../../../aspose.slides/ishape/)
* فئة [IPresentation](../../../aspose.slides/ipresentation/)
* فئة [String](../../../system/string/)
* فئة [SlideUtil](../)
* فئة [IBaseSlide](../../../aspose.slides/ibaseslide/)
* نطاق [Aspose::Slides::Util](../../)
* مكتبة [Aspose.Slides](../../../)