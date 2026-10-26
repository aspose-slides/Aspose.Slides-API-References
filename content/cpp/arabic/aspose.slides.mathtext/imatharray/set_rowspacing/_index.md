---
title: set_RowSpacing()
second_title: مرجع API لـ Aspose.Slides للـ C++
description: "المسافة بين صفوف مصفوفة تُستخدم فقط عندما يتم تعيين RowSpacingRule إلى 3 بالضبط، وفي هذه الحالة تكون وحدة القياس نقاط أو Multiple في حالة أن وحدة القياس هي نصف سطر. الافتراضي: 0"
type: docs
weight: 131
url: /ar/aspose.slides.mathtext/imatharray/set_rowspacing/
---
## IMathArray::set_RowSpacing(uint32_t) طريقة

المسافة بين صفوف المصفوفة تُستخدم فقط عندما يتم تعيين RowSpacingRule إلى 3 بالضبط، وفي هذه الحالة تكون وحدة القياس نقاطًا أو Multiple في حالة أن وحدة القياس هي نصف سطر. الافتراضي: 0

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_RowSpacing(uint32_t value)=0
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
* مكتبة [Aspose.Slides](../../../)