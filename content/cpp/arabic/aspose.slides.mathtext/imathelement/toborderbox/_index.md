---
title: ToBorderBox()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يضع هذا العنصر داخل صندوق حدود
type: docs
weight: 261
url: /ar/aspose.slides.mathtext/imathelement/toborderbox/
---
## IMathElement::ToBorderBox() طريقة

يضع هذا العنصر داخل صندوق حدود

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox()=0
```

### قيمة الإرجاع

صندوق حدود يحتوي على هذا العنصر
## ملاحظات



مثال: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## IMathElement::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) طريقة

يضع هذا العنصر داخل صندوق حدود

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathElement::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### المعامل

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hideTop | **bool** | إخفاء الحافة العليا |
| hideBottom | **bool** | إخفاء الحافة السفلى |
| hideLeft | **bool** | إخفاء الحافة اليسرى |
| hideRight | **bool** | إخفاء الحافة اليمنى |
| strikethroughHorizontal | **bool** | خط أفقي في صندوق الحدود |
| strikethroughVertical | **bool** | خط عمودي في صندوق الحدود |
| strikethroughBottomLeftToTopRight | **bool** | خط مقطوع من أسفل اليسار إلى أعلى اليمين في صندوق الحدود |
| strikethroughTopLeftToBottomRight | **bool** | خط مقطوع من أعلى اليسار إلى أسفل اليمين في صندوق الحدود |

### قيمة الإرجاع

صندوق حدود يحتوي على هذا العنصر
## ملاحظات



مثال: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBorderBox](../../imathborderbox/)
* فئة [IMathElement](../)
* فضاء الأسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)