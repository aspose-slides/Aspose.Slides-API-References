---
title: SetExternalWorkbook()
second_title: Aspose.Slides برای C++ API مرجع
description: یک کتاب‌کار خارجی را به‌عنوان منبع داده برای نمودار تنظیم می‌کند. داده‌های نمودار از کتاب‌کار هدف به‌روز خواهند شد.
type: docs
weight: 183
url: /fa/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) متد

یک کاربر کتاب‌کار خارجی را به‌عنوان منبع داده برای نمودار تنظیم می‌کند. [Chart](../../chart/) داده از کتاب‌کار هدف به‌روز خواهد شد.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | مسیر به کتاب‌کار هدف |
## توضیحات




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) متد

یک کاربر کتاب‌کار خارجی را به‌عنوان منبع داده برای نمودار تنظیم می‌کند.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### پارامترها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | مسیر به کتاب‌کار هدف |
| updateChartData | **bool** | اگر مقدار false باشد فقط مسیر کتاب‌کار به‌روز می‌شود. [Chart](../../chart/) داده بارگیری و به‌روز نخواهد شد از کتاب‌کار هدف. می‌توان از این گزینه وقتی کتاب‌کار هدف موجود نیست یا در دسترس نیست استفاده کرد. اگر مقدار true باشد، داده‌های نمودار از کتاب‌کار هدف به‌روز می‌شوند. |
## توضیحات




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## مراجع

* Class [String](../../../system/string/)
* Class [ChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)