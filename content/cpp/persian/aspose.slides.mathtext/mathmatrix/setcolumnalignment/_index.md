---
title: SetColumnAlignment()
second_title: مرجع API Aspose.Slides برای C++
description: هم‌ترازی افقی ستون مشخص‌شده را تنظیم می‌کند
type: docs
weight: 261
url: /fa/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) متد


هم‌ترازی افقی ستون موردنظر را تنظیم می‌کند

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | **int32_t** | اندیس ستون شمارش‌شده از صفر |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | مقدار جدید هم‌ترازی افقی ستون مشخص‌شده |
## یادداشت‌ها


مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## موارد مرتبط

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)