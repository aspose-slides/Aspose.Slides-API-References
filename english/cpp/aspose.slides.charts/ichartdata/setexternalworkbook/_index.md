---
title: SetExternalWorkbook()
second_title: Aspose.Slides for C++ API Reference
description: Sets external workbook as a data source for the chart. Chart data will be updated from the target workbook.
type: docs
weight: 183
url: /cpp/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook([System::String](../../../system/string/)) method


Sets external workbook as a data source for the chart. [Chart](../../chart/) data will be updated from the target workbook.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Path to the target workbook |
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## See Also

* Class [String](../../../system/string/)
* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
## IChartData::SetExternalWorkbook([System::String](../../../system/string/), **bool**) method


Sets external workbook as a data source for the chart.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | Path to the target workbook |
| updateChartData | **bool** | If value is false only workbook path will be updated. [Chart](../../chart/) data won't be loaded and updated from the target workbook. Can be used when target workbook doesn't exist or it's not available. If value is true chart data will be updated from the target workbook. |
## Remarks




```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## See Also

* Class [String](../../../system/string/)
* Class [IChartData](../)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)
