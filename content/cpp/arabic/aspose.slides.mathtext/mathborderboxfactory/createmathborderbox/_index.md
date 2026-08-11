---
title: CreateMathBorderBox()
second_title: مرجع API الخاص بـ Aspose.Slides للغة C++
description: إنشاء صندوق حدود رياضي بتطبيقه على العنصر
type: docs
weight: 1
url: /ar/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) طريقة


إنشاء مربع حدود رياضي بتطبيقه على العنصر

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```


### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر رياضي لتطبيق مربع الحدود |

### قيمة الإرجاع

عنصر صندوق الحدود الجديد

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) طريقة


إنشاء مربع حدود رياضي بتطبيقه على العنصر

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### المعاملات

| معامل | نوع | وصف |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | عنصر رياضي لتطبيق مربع الحدود |
| hideTop | **bool** | إخفاء الحافة العلوية |
| hideBottom | **bool** | إخفاء الحافة السفلية |
| hideLeft | **bool** | إخفاء الحافة اليسرى |
| hideRight | **bool** | إخفاء الحافة اليمنى |
| strikethroughHorizontal | **bool** | شطب أفقي لصندوق الحدود |
| strikethroughVertical | **bool** | شطب عمودي لصندوق الحدود |
| strikethroughBottomLeftToTopRight | **bool** | شطب من أسفل اليسار إلى أعلى اليمين لصندوق الحدود |
| strikethroughTopLeftToBottomRight | **bool** | شطب من أعلى اليسار إلى أسفل اليمين لصندوق الحدود |

### قيمة الإرجاع

عنصر صندوق الحدود الجديد

## انظر أيضا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBorderBox](../../imathborderbox/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathBorderBoxFactory](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)