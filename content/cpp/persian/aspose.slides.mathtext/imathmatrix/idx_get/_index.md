---
title: idx_get()
second_title: راهنمای API Aspose.Slides برای C++
description: عناصر ماتریس
type: docs
weight: 209
url: /fa/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) متد


عناصر ماتریس

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| row | **int32_t** | شاخص پایه‌صفر ردیفی که می‌خواهید آیتم را دریافت کنید |
| column | **int32_t** | شاخص پایه‌صفر ستونی که می‌خواهید آیتم را دریافت کنید |

### مقدار بازگشت


## توضیحات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## مراجع

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [IMathElement](../../imathelement/)
* کلاس [IMathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)