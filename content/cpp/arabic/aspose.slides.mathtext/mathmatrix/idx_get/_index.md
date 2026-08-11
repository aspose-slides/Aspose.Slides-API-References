---
title: idx_get()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: عنصر من المصفوفة
type: docs
weight: 209
url: /ar/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) طريقة

عنصر من المصفوفة

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| row | **int32_t** | المؤشر الصفري للصف للحصول على العنصر |
| column | **int32_t** | المؤشر الصفري للعمود للحصول على العنصر |

### قيمة الإرجاع


## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [IMathElement](../../imathelement/)
* فئة [MathMatrix](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)