---
title: get_RowSpacing()
second_title: Aspose.Slides لمرجع API للغة C++
description: "المسافة بين صفوف المصفوفة تُستخدم فقط عندما يتم تعيين RowSpacingRule إلى 3 بالضبط، حيث تكون وحدة القياس هي نقاط أو Multiple حيث تكون وحدة القياس نصف السطر. الافتراضي: 0"
type: docs
weight: 118
url: /ar/aspose.slides.mathtext/matharray/get_rowspacing/
---
## MathArray::get_RowSpacing() طريقة

المسافة بين صفوف المصفوفة تُستخدم فقط عندما يتم تعيين RowSpacingRule إلى 3 بالضبط، حيث تكون وحدة القياس هي النقاط أو Multiple حيث تكون وحدة القياس نصف-سطر. الافتراضي: 0

```cpp
uint32_t Aspose::Slides::MathText::MathArray::get_RowSpacing() override
```

## ملاحظات

مثال:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## انظر أيضًا

* الفئة [MathArray](../)
* النطاق [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)