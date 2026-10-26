---
title: SetColumnAlignment()
second_title: مرجع API Aspose.Slides برای C++
description: تراز افقی ستون مشخص‌شده را تنظیم کنید
type: docs
weight: 248
url: /fa/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) متد

تراز افقی ستون مشخص‌شده را تنظیم کنید

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | **int32_t** | اندیس ستون مبتنی بر صفر |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | مقدار جدید تراز افقی ستون مشخص‌شده |

## توضیحات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## موارد مرتبط

* شمارش [MathHorizontalAlignment](../../mathhorizontalalignment/)
* کلاس [IMathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)