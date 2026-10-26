---
title: InsertColumnBefore()
second_title: مرجع API Aspose.Slides برای C++
description: یک ستون جدید را پیش از ستون مشخص‌شده وارد می‌کند. در ابتدا تمام عناصر ستون جدید مقدار null دارند.
type: docs
weight: 313
url: /fa/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) متد

یک ستون جدید را پیش از ستون مشخص‌شده وارد می‌کند. در ابتدا تمام عناصر ستون جدید مقدار null دارند.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| columnIndex | **int32_t** | شاخص ستونی که قبل از آن می‌خواهید یک ستون جدید وارد کنید |
## ملاحظات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## موارد مرتبط

* کلاس [IMathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)