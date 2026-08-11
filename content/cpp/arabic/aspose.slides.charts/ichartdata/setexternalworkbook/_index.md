---
title: SetExternalWorkbook()
second_title: مرجع API Aspose.Slides للغة C++
description: يضبط دفتر عمل خارجي كمصدر بيانات للمخطط. سيتم تحديث بيانات المخطط من دفتر العمل الهدف.
type: docs
weight: 196
url: /ar/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) method

يضبط دفتر عمل خارجي كمصدر بيانات للمخطط. ستتم تحديث بيانات [Chart](../../chart/) من دفتر العمل الهدف.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | مسار دفتر العمل الهدف |
## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) method

يضبط دفتر عمل خارجي كمصدر بيانات للمخطط.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | مسار دفتر العمل الهدف |
| updateChartData | **bool** | إذا كانت القيمة false سيتم تحديث مسار دفتر العمل فقط. ستظل بيانات [Chart](../../chart/) غير محملة وغير محدثة من دفتر العمل الهدف. يمكن استخدامها عندما لا يكون دفتر العمل الهدف موجودًا أو غير متاح. إذا كانت القيمة true سيتم تحديث بيانات المخطط من دفتر العمل الهدف. |
## ملاحظات

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## انظر أيضًا

* الفئة [String](../../../system/string/)
* الفئة [IChartData](../)
* مساحة الاسم [Aspose::Slides::Charts](../../)
* المكتبة [Aspose.Slides](../../../)