---
title: GetColumnAlignment()
second_title: مرجع API Aspose.Slides للغة C++
description: احصل على المحاذاة الأفقية للعمود المحدد
type: docs
weight: 235
url: /ar/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## طريقة IMathMatrix::GetColumnAlignment(int32_t)

احصل على المحاذاة الأفقية للعمود المحدد

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | **int32_t** | فهرس العمود يبدأ من الصفر |

### قيمة الإرجاع

المحاذاة الأفقية للعمود المحدد
## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## انظر أيضًا

* تعداد [MathHorizontalAlignment](../../mathhorizontalalignment/)
* فئة [IMathMatrix](../)
* مساحة اسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)