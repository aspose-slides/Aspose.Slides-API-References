---
title: get_MinColumnWidth()
second_title: مرجع API Aspose.Slides برای C++
description: "حداقل عرض ستون در twips (1/20th of a point) فاصلهٔ بین ستون‌ها (که همچنین به عنوان \\u201CColumn Gap\\u201D یا \\u201CGap Width\\u201D اشاره می‌شود) به MinColumnWidth اضافه می‌شود تا کل Matrix Column Spacing (فاصله بین لبه‌های مشابه ستون‌های مختلف) تعیین شود. پیش‌فرض: 0."
type: docs
weight: 79
url: /fa/aspose.slides.mathtext/imathmatrix/get_mincolumnwidth/
---
## IMathMatrix::get_MinColumnWidth() متد

حداقل عرض ستون در twips (1/20th of a point) فاصله بین ستون‌ها (که همچنین به عنوان \\u201CColumn Gap\\u201D یا \\u201CGap Width\\u201D نامیده می‌شود) به MinColumnWidth اضافه می‌شود تا مجموع Matrix [Column](../../../aspose.slides/column/) Spacing (فاصله بین لبه‌های مشابه ستون‌های مختلف) تعیین شود. پیش‌فرض: 0.

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_MinColumnWidth()=0
```

## توضیحات

مثال:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## مراجع

* کلاس [IMathMatrix](../)
* فضای‌نام [Aspose::Slides::MathText](../../)
* کتابخانه [Aspose.Slides](../../../)