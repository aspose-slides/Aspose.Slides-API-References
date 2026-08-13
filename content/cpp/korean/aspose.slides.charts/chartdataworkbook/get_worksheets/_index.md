---
title: get_Worksheets()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 워크시트 컬렉션을 반환합니다.
type: docs
weight: 1
url: /ko/aspose.slides.charts/chartdataworkbook/get_worksheets/
---
## ChartDataWorkbook::get_Worksheets() 메서드

워크시트 컬렉션을 반환합니다.

```cpp
System::SharedPtr<IChartDataWorksheetCollection> Aspose::Slides::Charts::ChartDataWorkbook::get_Worksheets() override
```

## 비고

예시: 
```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 50.0f, 50.0f, 400.0f, 500.0f);
auto workbook = chart->get_ChartData()->get_ChartDataWorkbook();
for (const auto& worksheet : workbook->get_Worksheets())
{
    System::String worksheetName = worksheet->get_Name();
}
```

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataWorksheetCollection](../../ichartdataworksheetcollection/)
* 클래스 [ChartDataWorkbook](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)