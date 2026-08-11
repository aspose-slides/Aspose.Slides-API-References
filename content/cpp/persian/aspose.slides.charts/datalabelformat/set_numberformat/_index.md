---
title: set_NumberFormat()
second_title: مرجع API Aspose.Slides برای C++
description: "نمایانگر رشته قالب برای شی DataLabels است. بنویسید System::String."
type: docs
weight: 40
url: /fa/aspose.slides.charts/datalabelformat/set_numberformat/
---
## DataLabelFormat::set_NumberFormat(System::String) متد

نمایانگر رشته قالب برای شی DataLabels است. بنویسید [System::String](../../../system/string/).

```cpp
void Aspose::Slides::Charts::DataLabelFormat::set_NumberFormat(System::String value) override
```

## توضیحات

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

اگر والد این شی [DataLabelFormat](../) یک مجموعه [DataLabelCollection](../../datalabelcollection/) از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی NumberFormat را برای برچسب‌های داده جدید در مجموعه [DataLabelCollection](../../datalabelcollection/) دریافت یا تنظیم می‌کند. هنگامی که این ویژگی با مقداری تنظیم می‌شود، آن مقدار همچنین برای ویژگی NumberFormat برای تمام برچسب‌های داده در مجموعه [DataLabelCollection](../../datalabelcollection/) تنظیم می‌شود (به عنوان مثال "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" باعث می‌شود همه DataLabels[i].NumberFormat برابر با val باشد).

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [DataLabelFormat](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)