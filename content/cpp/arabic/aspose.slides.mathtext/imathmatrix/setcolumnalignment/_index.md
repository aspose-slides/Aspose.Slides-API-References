---
title: SetColumnAlignment()
second_title: Aspose.Slides لـ C++ مرجع API
description: تعيين المحاذاة الأفقية للعمود المحدد
type: docs
weight: 248
url: /ar/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) طريقة

تعيين المحاذاة الأفقية للعمود المحدد

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | **int32_t** | فهرس العمود يبدأ من الصفر |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | القيمة الجديدة للمحاذاة الأفقية للعمود المحدد |

## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## انظر أيضاً

* تعداد [MathHorizontalAlignment](../../mathhorizontalalignment/)
* فئة [IMathMatrix](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)