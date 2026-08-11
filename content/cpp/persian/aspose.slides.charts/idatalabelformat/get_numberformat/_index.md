---
title: get_NumberFormat()
second_title: مرجع API Aspose.Slides برای C++
description: "رشتهٔ قالب را برای شیء DataLabels نشان می‌دهد. بخوانید System::String."
type: docs
weight: 27
url: /fa/aspose.slides.charts/idatalabelformat/get_numberformat/
---
## IDataLabelFormat::get_NumberFormat() متد

نمایانگر رشته قالب برای شیء DataLabels است. بخوانید [System::String](../../../system/string/).

```cpp
virtual System::String Aspose::Slides::Charts::IDataLabelFormat::get_NumberFormat()=0
```

## توضیحات

```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```

اگر والد این شیء [DataLabelFormat](../../datalabelformat/) یک مجموعه [DataLabelCollection](../../datalabelcollection/) از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی NumberFormat را برای برچسب‌های داده جدید در مجموعه [DataLabelCollection](../../datalabelcollection/) دریافت یا تنظیم می‌کند. وقتی این ویژگی با مقداری تنظیم می‌شود، همان مقدار برای ویژگی NumberFormat تمام برچسب‌های داده در مجموعه [DataLabelCollection](../../datalabelcollection/) نیز تنظیم می‌شود (به عنوان مثال "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" باعث می‌شود تمام DataLabels[i].NumberFormat برابر با val باشد).

## مراجع

* کلاس [String](../../../system/string/)
* کلاس [IDataLabelFormat](../)
* فضای نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)