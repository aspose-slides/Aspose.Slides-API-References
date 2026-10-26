---
title: InsertRowBefore()
second_title: مرجع API Aspose.Slides برای C++
description: یک ردیف جدید قبل از ردیف مشخص شده درج می‌کند. در ابتدا تمام عناصر ردیف جدید null هستند.
type: docs
weight: 287
url: /fa/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) متد

یک ردیف جدید قبل از ردیف مشخص شده درج می‌کند. در ابتدا تمام عناصر ردیف جدید null هستند.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| rowIndex | **int32_t** | شاخص ردیفی که قبل از آن یک ردیف جدید درج می‌شود |
## توضیحات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## همچنین ببینید

* کلاس [MathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)