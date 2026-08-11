---
title: set_NumberFormat()
second_title: "مرجع API Aspose.Slides برای C++"
description: "نمایانگر رشتهٔ قالب برای شیء DataLabels است. System::String را بنویسید."
type: docs
weight: 40
url: /fa/aspose.slides.charts/idatalabelformat/set_numberformat/
---
## IDataLabelFormat::set_NumberFormat(System::String) متد


نمایانگر رشتهٔ قالب برای شیء DataLabels است. [System::String](../../../system/string/) را بنویسید.

```cpp
virtual void Aspose::Slides::Charts::IDataLabelFormat::set_NumberFormat(System::String value)=0
```

## توضیحات



```cpp
auto defaultDataLabelFormat = series->get_Labels()->get_DefaultDataLabelFormat();
defaultDataLabelFormat->set_ShowValue(true);
defaultDataLabelFormat->set_IsNumberFormatLinkedToSource(false);
defaultDataLabelFormat->set_NumberFormat(u"0.0%");
```



اگر والد این شیء [DataLabelFormat](../../datalabelformat/) یک مجموعهٔ [DataLabelCollection](../../datalabelcollection/) از برچسب‌های داده باشد، این ویژگی مقدار پیش‌فرض ویژگی NumberFormat را برای برچسب‌های دادهٔ جدید در مجموعهٔ [DataLabelCollection](../../datalabelcollection/) دریافت یا تنظیم می‌کند. هنگامی که این ویژگی با مقداری تنظیم می‌شود، همان مقدار برای ویژگی NumberFormat تمام برچسب‌های داده در مجموعهٔ [DataLabelCollection](../../datalabelcollection/) نیز تنظیم می‌شود (به عنوان مثال "DataLabels.DefaultDataLabelFormat.NumberFormat = val;" باعث می‌شود همهٔ DataLabels[i].NumberFormat برابر با val باشد). 
## همچنین ببینید

* کلاس [String](../../../system/string/)
* کلاس [IDataLabelFormat](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)