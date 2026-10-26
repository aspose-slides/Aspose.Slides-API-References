---
title: ToBorderBox()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: يقوم بوضع هذا العنصر داخل صندوق الحد
type: docs
weight: 248
url: /ar/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() method

يقوم بوضع هذا العنصر داخل صندوق الحد

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```

### قيمة الإرجاع

صندوق الحد مع وضع هذا العنصر داخله

## ملاحظات



مثال: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) method

يقوم بوضع هذا العنصر داخل صندوق الحد

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| hideTop | **bool** | إخفاء الحافة العلوية |
| hideBottom | **bool** | إخفاء الحافة السفلية |
| hideLeft | **bool** | إخفاء الحافة اليسرى |
| hideRight | **bool** | إخفاء الحافة اليمنى |
| strikethroughHorizontal | **bool** | شطب صلب الصندوق أفقيًا |
| strikethroughVertical | **bool** | شطب صلب الصندوق عموديًا |
| strikethroughBottomLeftToTopRight | **bool** | شطب صلب الصندوق من الأسفل-يسار إلى الأعلى-يمين |
| strikethroughTopLeftToBottomRight | **bool** | شطب صلب الصندوق من الأعلى-يسار إلى الأسفل-يمين |

### قيمة الإرجاع

صندوق الحد مع وضع هذا العنصر داخله

## ملاحظات



مثال: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathBorderBox](../../imathborderbox/)
* فئة [MathElementBase](../)
* فضاء الأسماء [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)