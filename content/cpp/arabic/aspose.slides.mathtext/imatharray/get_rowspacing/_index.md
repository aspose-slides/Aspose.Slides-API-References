---
title: get_RowSpacing()
second_title: Aspose.Slides لـ C++ مرجع API
description: "المسافة بين صفوف مصفوفة تُستخدم فقط عندما يتم تعيين RowSpacingRule إلى 3 بالضبط، حيث تكون وحدة القياس نقاط أو Multiple حيث تكون وحدة القياس نصف أسطر. القيمة الافتراضية: 0"
type: docs
weight: 118
url: /ar/aspose.slides.mathtext/imatharray/get_rowspacing/
---
## IMathArray::get_RowSpacing() طريقة

المسافة بين صفوف المصفوفة يتم استخدامها فقط عندما تكون RowSpacingRule مُعيَّنة إلى 3 في الحالة الأولى تكون وحدة القياس نقاط، وفي الحالة الثانية Multiple تكون وحدة القياس نصف أسطر. القيمة الافتراضية: 0

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathArray::get_RowSpacing()=0
```

## ملاحظات

مثال:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## انظر أيضًا

* الفئة [IMathArray](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)