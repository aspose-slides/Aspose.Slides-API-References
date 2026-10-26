---
title: idx_get()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عناصر المصفوفة
type: docs
weight: 209
url: /ar/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) طريقة

عناصر المصفوفة

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| row | **int32_t** | الفهرس الصفري للصف للحصول على العنصر |
| column | **int32_t** | الفهرس الصفري للعمود للحصول على العنصر |

### قيمة الإرجاع


## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [IMathMatrix](../)
* نطاق الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)