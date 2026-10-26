---
title: SetExternalWorkbook()
second_title: Aspose.Slides برای C++ مرجع API
description: کتاب کار خارجی را به‌عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های نمودار از کتاب کار هدف به‌روزرسانی خواهند شد.
type: docs
weight: 196
url: /fa/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) متد

Sets external workbook as a data source for the chart. [Chart](../../chart/) داده‌ها از کتاب کار هدف به‌روزرسانی خواهند شد.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | مسیر به کتاب کار هدف |

## توضیحات


```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) متد

Sets external workbook as a data source for the chart.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | مسیر به کتاب کار هدف |
| updateChartData | **bool** | اگر مقدار false باشد فقط مسیر کتاب کار به‌روزرسانی می‌شود. [Chart](../../chart/) داده‌ها بارگیری و به‌روزرسانی نمی‌شوند از کتاب کار هدف. می‌تواند وقتی که کتاب کار هدف وجود ندارد یا در دسترس نیست استفاده شود. اگر مقدار true باشد داده‌های نمودار از کتاب کار هدف به‌روزرسانی می‌شوند. |

## توضیحات


```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## موارد مرتبط

* کلاس [String](../../../system/string/)
* کلاس [IChartData](../)
* فضای‌نام [Aspose::Slides::Charts](../../)
* کتابخانه [Aspose.Slides](../../../)