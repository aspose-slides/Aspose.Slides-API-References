---
title: SetExternalWorkbook()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 차트의 데이터 소스로 외부 워크북을 설정합니다. 차트 데이터는 대상 워크북에서 업데이트됩니다.
type: docs
weight: 196
url: /ko/aspose.slides.charts/ichartdata/setexternalworkbook/
---
## IChartData::SetExternalWorkbook(System::String) method

차트의 데이터 소스로 외부 워크북을 설정합니다. [Chart](../../chart/) 데이터는 대상 워크북에서 업데이트됩니다.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath)=0
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 대상 워크북의 경로 |
## Remarks

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## IChartData::SetExternalWorkbook(System::String, bool) method

차트의 데이터 소스로 외부 워크북을 설정합니다.

```cpp
virtual void Aspose::Slides::Charts::IChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData)=0
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 대상 워크북의 경로 |
| updateChartData | **bool** | 값이 false이면 워크북 경로만 업데이트됩니다. [Chart](../../chart/) 데이터는 로드되거나 대상 워크북에서 업데이트되지 않습니다. 대상 워크북이 존재하지 않거나 사용할 수 없을 때 사용할 수 있습니다. 값이 true이면 차트 데이터가 대상 워크북에서 업데이트됩니다. |
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