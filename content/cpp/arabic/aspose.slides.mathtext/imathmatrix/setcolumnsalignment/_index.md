---
title: SetColumnsAlignment()
second_title: Aspose.Slides لمرجع API C++
description: تعيين المحاذاة الأفقية للأعمدة المحددة
type: docs
weight: 261
url: /ar/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) دالة

تعيين المحاذاة الأفقية للأعمدة المحددة

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```

### وسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| columnIndex | **int32_t** | فهرس يبدأ من الصفر للعمود الأول لتعيين المحاذاة |
| columnsCount | **uint32_t** | عدد الأعمدة لتحديد المحاذاة |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | القيمة الجديدة للمحاذاة الأفقية للعمود المحدد |
## ملاحظات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## انظر أيضاً

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* فئة [IMathMatrix](../)
* نطاق [Aspose::Slides::MathText](../../)
* مكتبة [Aspose.Slides](../../../)