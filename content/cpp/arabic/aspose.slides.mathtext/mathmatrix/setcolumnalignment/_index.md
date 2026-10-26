---
title: SetColumnAlignment()
second_title: مرجع واجهة برمجة التطبيقات Aspose.Slides للـ C++
description: تعيين المحاذاة الأفقية للعمود المحدد
type: docs
weight: 261
url: /ar/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) طريقة

تعيين المحاذاة الأفقية للعمود المحدد

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```

### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | **int32_t** | مؤشر العمود يبدأ من الصفر |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | القيمة الجديدة للمحاذاة الأفقية للعمود المحدد |
## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## انظر أيضًا

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* فئة [MathMatrix](../)
* المجال [Aspose::Slides::MathText](../../)
* المكتبة [Aspose.Slides](../../../)