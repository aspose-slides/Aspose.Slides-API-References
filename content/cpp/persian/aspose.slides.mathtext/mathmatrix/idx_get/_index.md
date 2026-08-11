---
title: idx_get()
second_title: مرجع API Aspose.Slides برای C++
description: عنصر ماتریس
type: docs
weight: 209
url: /fa/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) متد

عنصر ماتریس

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| row | **int32_t** | شاخص صفر-محور ردیف برای دریافت آیتم |
| column | **int32_t** | شاخص صفر-محور ستون برای دریافت آیتم |

### مقدار بازگشت


## توضیحات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [MathMatrix](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)