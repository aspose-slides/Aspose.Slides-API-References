---
title: GetColumnAlignment()
second_title: مرجع API Aspose.Slides للغة C++
description: احصل على المحاذاة الأفقية للعمود المحدد
type: docs
weight: 248
url: /ar/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) طريقة

احصل على المحاذاة الأفقية للعمود المحدد

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | **int32_t** | فهرس العمود يبدأ من الصفر |

### قيمة الإرجاع

محاذاة أفقية للعمود المحدد
## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## انظر أيضًا

* تعداد [MathHorizontalAlignment](../../mathhorizontalalignment/)
* فئة [MathMatrix](../)
* نطاق الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)