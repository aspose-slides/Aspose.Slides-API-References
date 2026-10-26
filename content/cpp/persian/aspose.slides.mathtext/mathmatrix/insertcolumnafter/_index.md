---
title: InsertColumnAfter()
second_title: Aspose.Slides برای مرجع API C++
description: یک ستون جدید را پس از ستون مشخص شده وارد می‌کند. در ابتدا تمام عناصر ستون جدید مقدار null دارند.
type: docs
weight: 339
url: /fa/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) متد

یک ستون جدید را پس از ستون مشخص شده وارد می‌کند. در ابتدا تمام عناصر ستون جدید مقدار null دارند.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | **int32_t** | اندیس ستونی که پس از آن ستون جدید قرار می‌گیرد |
## توضیحات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## موارد مرتبط

* کلاس [MathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)