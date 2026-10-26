---
title: GetColumnAlignment()
second_title: مرجع API Aspose.Slides برای C++
description: دریافت هم‌ترازی افقی ستون مشخص‌شده
type: docs
weight: 248
url: /fa/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) متد

دریافت هم‌ترازی افقی ستون مشخص‌شده

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | **int32_t** | اندیس صفر-پایهٔ ستون |

### مقدار بازگشتی

هم‌ترازی افقی ستون مشخص‌شده
## توضیحات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## موارد مرتبط

* enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* کلاس [MathMatrix](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)