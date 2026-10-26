---
title: SetColumnsAlignment()
second_title: مرجع API Aspose.Slides برای C++
description: تراز افقی ستون‌های مشخص‌شده را تنظیم می‌کند
type: docs
weight: 261
url: /fa/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) متد


تراز افقی ستون‌های مشخص‌شده را تنظیم می‌کند

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```


### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | **int32_t** | شاخص صفر-پایه اولین ستونی که تراز آن تنظیم می‌شود |
| columnsCount | **uint32_t** | تعداد ستون‌هایی که تراز آن‌ها مشخص می‌شود |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | مقدار جدید تراز افقی ستون مشخص‌شده |
## توضیحات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## موارد مرتبط

* شمارشگر [MathHorizontalAlignment](../../mathhorizontalalignment/)
* کلاس [IMathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)