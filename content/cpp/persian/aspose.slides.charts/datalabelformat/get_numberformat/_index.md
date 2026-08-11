---
title: get_NumberFormat()
second_title: "مرجع API Aspose.Slides برای C++"
description: "نمایانگر رشتهٔ قالب برای شیء DataLabels است. بخوانید System::String."
type: docs
weight: 27
url: /fa/aspose.slides.charts/datalabelformat/get_numberformat/
---
## DataLabelFormat::get_NumberFormat() متد


نمایانگر رشتهٔ قالب برای شیء DataLabels است. بخوانید [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::Charts::DataLabelFormat::get_NumberFormat() override
```

## توضیحات



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```





اگر والد این شیء [DataLabelFormat](../) یک مجموعه [DataLabelCollection](../../datalabelcollection/) از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی NumberFormat را برای برچسب‌های دادهٔ جدید در مجموعه [DataLabelCollection](../../datalabelcollection/) دریافت یا تنظیم می‌کند. وقتی این ویژگی با مقداری تنظیم شود، آن مقدار همچنین برای ویژگی NumberFormat تمام برچسب‌های داده در مجموعه [DataLabelCollection](../../datalabelcollection/) تنظیم می‌شود (به عنوان مثال \"DataLabels.DefaultDataLabelFormat.NumberFormat = val;\" باعث می‌شود همه DataLabels[i].NumberFormat برابر با val شود). 


## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [DataLabelFormat](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)