---
title: InsertColumnBefore()
second_title: Aspose.Slides برای مرجع API C++
description: یک ستون جدید را قبل از ستون مشخص‌شده درج می‌کند. در ابتدا تمام عناصر در ستون جدید برابر null هستند.
type: docs
weight: 326
url: /fa/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) method

یک ستون جدید قبل از ستون مشخص‌شده درج می‌کند. در ابتدا تمام عناصر در ستون جدید برابر null هستند.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | **int32_t** | شاخص ستونی که پیش از آن یک ستون جدید قرار می‌گیرد |

## توضیحات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## موارد مرتبط

* کلاس [MathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)