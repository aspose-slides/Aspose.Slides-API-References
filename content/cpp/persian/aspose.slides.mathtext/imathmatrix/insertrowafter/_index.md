---
title: InsertRowAfter()
second_title: مرجع API Aspose.Slides برای C++
description: یک ردیف جدید پس از ردیف مشخص شده اضافه می‌کند. در ابتدا تمام عناصر ردیف جدید null هستند.
type: docs
weight: 287
url: /fa/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) متد


یک ردیف جدید پس از ردیف مشخص شده اضافه می‌کند. در ابتدا تمام عناصر ردیف جدید null هستند.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rowIndex | **int32_t** | اندیس ردیفی که بعد از آن یک ردیف جدید درج می‌شود |
## توضیحات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## موارد مرتبط

* کلاس [IMathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)