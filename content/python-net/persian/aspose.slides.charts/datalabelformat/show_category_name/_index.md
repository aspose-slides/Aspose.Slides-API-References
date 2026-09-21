---
title: show_category_name property
second_title: Aspose.Slides برای Python از طریق .NET مرجع API
description: 
type: docs
url: /fa/aspose.slides.charts/datalabelformat/show_category_name/
weight: 130
---
## ویژگی show_category_name
نمایانگر رفتار نمایش نام دسته‌بندی برچسب داده برای نمودار مشخص شده است.
True برای نمایش نام دسته‌بندی برچسب‌های داده در یک نمودار. False برای پنهان کردن.
خواندنی/قابل نوشتن **bool**.

### نکات

اگر والد این شیء DataLabelFormat یک مجموعه DataLabelCollection از برچسب‌های داده باشد، این خاصیت مقدار پیش‌فرض خصوصیت ShowCategoryName را برای برچسب‌های داده جدید در مجموعه DataLabelCollection می‌گیرد یا تنظیم می‌کند.
تنظیم این خاصیت با مقدار، همان مقدار را به خصوصیت ShowCategoryName برای تمام برچسب‌های داده در مجموعه DataLabelCollection نیز می‌سپارد.
(i.e. "DataLabels.DefaultDataLabelFormat.ShowCategoryName = val;" باعث می‌شود که تمام DataLabels[i].ShowCategoryName برابر با val باشد.)

### تعریف:
```python
@property
def show_category_name(self):
    ...

@show_category_name.setter
def show_category_name(self, value):
    ...
```

### مراجعات
* کلاس [`DataLabelFormat`](/slides/python-net/fa/aspose.slides.charts/datalabelformat)
* ماژول [`aspose.slides.charts`](/slides/python-net/fa/aspose.slides.charts)
* کتابخانه [`Aspose.Slides`](/slides/python-net)