---
title: CreateMathBorderBox()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: إنشاء مربع حد رياضي بتطبيقه على العنصر
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) طريقة

إنشاء مربع حد رياضي بتطبيقه على العنصر

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر رياضي لتطبيق مربع الحد |
 
### قيمة الإرجاع

عنصر مربع حد جديد

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) طريقة

إنشاء مربع حد رياضي بتطبيقه على العنصر

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر رياضي لتطبيق مربع الحد |
| hideTop | **bool** | إخفاء الحافة العليا |
| hideBottom | **bool** | إخفاء الحافة السفلية |
| hideLeft | **bool** | إخفاء الحافة اليسرى |
| hideRight | **bool** | إخفاء الحافة اليمنى |
| strikethroughHorizontal | **bool** | خط أفقي عبر مربع الحد |
| strikethroughVertical | **bool** | خط عمودي عبر مربع الحد |
| strikethroughBottomLeftToTopRight | **bool** | خط قطري من أسفل اليسار إلى أعلى اليمين عبر مربع الحد |
| strikethroughTopLeftToBottomRight | **bool** | خط قطري من أعلى اليسار إلى أسفل اليمين عبر مربع الحد |

### قيمة الإرجاع

عنصر مربع حد جديد

## انظر أيضاً

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBorderBox](../../imathborderbox/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathBorderBoxFactory](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)