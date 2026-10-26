---
title: InsertRowAfter()
second_title: مرجع API Aspose.Slides برای C++
description: یک ردیف جدید پس از ردیف مشخص شده اضافه می‌کند. در ابتدا تمام عناصر ردیف جدید null هستند.
type: docs
weight: 300
url: /fa/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) متد

یک ردیف جدید پس از ردیف مشخص شده اضافه می‌کند. ابتدا تمام عناصر ردیف جدید برابر null هستند.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rowIndex | **int32_t** | شاخص ردیفی که پس از آن ردیف جدید قرار می‌گیرد |
## توضیحات

مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## موارد مرتبط

* کلاس [MathMatrix](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)