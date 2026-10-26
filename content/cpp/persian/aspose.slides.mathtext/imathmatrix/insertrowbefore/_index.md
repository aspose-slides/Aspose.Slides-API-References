---
title: InsertRowBefore()
second_title: Aspose.Slides برای C++ مرجع API
description: یک ردیف جدید را پیش از ردیف مشخص شده درج می‌کند. در ابتدا تمام عناصر ردیف جدید مقدار null دارند.
type: docs
weight: 274
url: /fa/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) متد

یک ردیف جدید را پیش از ردیف مشخص شده درج می‌کند. در ابتدا تمام عناصر ردیف جدید مقدار null دارند.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rowIndex | **int32_t** | اندیس ردیفی که پیش از آن یک ردیف جدید درج می‌شود |
## توضیحات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## نگاه کنید به

* کلاس [IMathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)