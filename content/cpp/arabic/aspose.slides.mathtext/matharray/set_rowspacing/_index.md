---
title: set_RowSpacing()
second_title: مرجع API Aspose.Slides للغة C++
description: "التباعد بين صفوف المصفوفة يُستخدم فقط عندما يتم ضبط RowSpacingRule على 3. في هذه الحالة تكون وحدة القياس نقاط أو Multiple في هذه الحالة تكون وحدة القياس نصف أسطر. الافتراضي: 0"
type: docs
weight: 131
url: /ar/aspose.slides.mathtext/matharray/set_rowspacing/
---
## MathArray::set_RowSpacing(uint32_t) طريقة

التباعد بين صفوف المصفوفة يُستخدم فقط عندما يتم ضبط RowSpacingRule على 3. بالضبط في هذه الحالة تكون وحدة القياس نقاط أو Multiple في هذه الحالة تكون وحدة القياس نصف أسطر. الافتراضي: 0

```cpp
void Aspose::Slides::MathText::MathArray::set_RowSpacing(uint32_t value) override
```

## ملاحظات

مثال:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::Exactly);
mathArray->set_RowSpacing(10);
```

## انظر أيضاً

* الفئة [MathArray](../)
* المجال [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)