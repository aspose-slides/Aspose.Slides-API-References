---
title: SetExternalWorkbook()
second_title: Aspose.Slides for C++ API 참조
description: 차트에 대한 데이터 원본으로 외부 워크북을 설정합니다. 차트 데이터는 대상 워크북에서 업데이트됩니다.
type: docs
weight: 183
url: /ko/aspose.slides.charts/chartdata/setexternalworkbook/
---
## ChartData::SetExternalWorkbook(System::String) 메서드

차트에 대한 데이터 원본으로 외부 워크북을 설정합니다. [Chart](../../chart/) 데이터는 대상 워크북에서 업데이트됩니다.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 대상 워크북의 경로 |
## 비고

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"../../workbook.xlsx");
```

## ChartData::SetExternalWorkbook(System::String, bool) 메서드

차트에 대한 데이터 원본으로 외부 워크북을 설정합니다.

```cpp
void Aspose::Slides::Charts::ChartData::SetExternalWorkbook(System::String workbookPath, bool updateChartData) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| workbookPath | [System::String](../../../system/string/) | 대상 워크북의 경로 |
| updateChartData | **bool** | 값이 false인 경우 워크북 경로만 업데이트됩니다. [Chart](../../chart/) 데이터는 로드 및 대상 워크북에서 업데이트되지 않습니다. 대상 워크북이 없거나 사용할 수 없을 때 사용할 수 있습니다. 값이 true인 경우 차트 데이터가 대상 워크북에서 업데이트됩니다. |
## 비고

```cpp
auto pres = System::MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Aspose::Slides::Charts::ChartType::Pie, 50.0f, 50.0f, 400.0f, 600.0f, true);
auto chartData = chart->get_ChartData();
(System::AsCast<Aspose::Slides::Charts::ChartData>(chartData))->SetExternalWorkbook(u"http://path/doesnt/exists", false);
```

## 참고

* 클래스 [String](../../../system/string/)
* 클래스 [ChartData](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)