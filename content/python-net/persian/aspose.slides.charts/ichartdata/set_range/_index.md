---
title: set_range method
second_title: مرجع API Aspose.Slides برای پایتون از طریق .NET
description: 
type: docs
url: /fa/aspose.slides.charts/ichartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
محدوده داده‌های نمودار را تنظیم می‌کند. سری‌ها و دسته‌بندها بر اساس محدوده داده جدید به‌روز می‌شوند.
اگر تعداد سری‌ها در محدوده داده بیشتر از تعداد سری‌های موجود در داده‌های نمودار باشد، سری‌های اضافی با همان نوع آخرین سری در مجموعه فعلی به انتهای مجموعه اضافه می‌شوند.

```python
def set_range(self, formula):
    ...
```

| پارامتر | نوع | توضیح |
| :- | :- | :- |
| formula | **str** | فرمول محدوده داده سلول‌ها. به عنوان مثال: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### استثناها

| استثنا | توضیح |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | فرمول None است. |
| **RuntimeError(Proxy error(ArgumentException))** | فرمول دارای قالب نادرست است. |

### موارد مرتبط
* کلاس [`IChartData`](/slides/python-net/fa/aspose.slides.charts/ichartdata)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)