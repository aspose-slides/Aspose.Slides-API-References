---
title: SetColumnsAlignment()
second_title: Aspose.Slides لـ C++ مرجع API
description: تحديد المحاذاة الأفقية للأعمدة المحددة
type: docs
weight: 274
url: /ar/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) طريقة


تحديد المحاذاة الأفقية للأعمدة المحددة

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```


### المعاملات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | **int32_t** | الفهرس صفر-الأساس للعمود الأول لتحديد المحاذاة |
| columnsCount | **uint32_t** | عدد الأعمدة لتحديد المحاذاة |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | القيمة الجديدة للمحاذاة الأفقية للعمود المحدد |
## ملاحظات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## انظر أيضًا

* تعداد [MathHorizontalAlignment](../../mathhorizontalalignment/)
* فئة [MathMatrix](../)
* مساحة الاسم [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)