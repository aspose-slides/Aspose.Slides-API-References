---
title: GetColumnAlignment()
second_title: مرجع API Aspose.Slides برای C++
description: دریافت ترازبندی افقی ستون مشخص شده
type: docs
weight: 235
url: /fa/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) متد


دریافت ترازبندی افقی ستون مشخص شده

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | **int32_t** | ایندکس ستون با مبنای صفر |

### مقدار برگشتی

ترازبندی افقی ستون مشخص شده
## توضیحات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## موارد مرتبط

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* کلاس [IMathMatrix](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)