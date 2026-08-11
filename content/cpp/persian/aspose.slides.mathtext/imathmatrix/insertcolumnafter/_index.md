---
title: InsertColumnAfter()
second_title: Aspose.Slides برای C++ مرجع API
description: یک ستون جدید پس از ستون مشخص‌شده وارد می‌کند؛ در ابتدا تمام عناصر ستون جدید null هستند.
type: docs
weight: 326
url: /fa/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) متد


یک ستون جدید پس از ستون مشخص‌شده وارد می‌کند. در ابتدا تمام عناصر ستون جدید null هستند.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```


### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | **int32_t** | شاخص ستونی که پس از آن یک ستون جدید وارد می‌شود |
## نکات



مثال: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## موارد مرتبط

* کلاس [IMathMatrix](../)
* فضای نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)