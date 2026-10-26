---
title: get_Format()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 데이터 포인트 레벨의 서식 속성을 나타냅니다. IFormat을 읽어보십시오.
type: docs
weight: 1
url: /ko/aspose.slides.charts/ichartdatapointlevel/get_format/
---
## IChartDataPointLevel::get_Format() 메서드


데이터 포인트 레벨의 서식 속성을 나타냅니다. [IFormat](../../iformat/)를 읽어보십시오.

```cpp
virtual System::SharedPtr<IFormat> Aspose::Slides::Charts::IChartDataPointLevel::get_Format()=0
```

## 비고






```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Treemap, 50.0f, 50.0f, 500.0f, 400.0f);
auto series = chart->get_ChartData()->get_Series()->idx_get(0);

auto dataPointLevel = series->get_DataPoints()->idx_get(7)->get_DataPointLevels()->idx_get(2);
dataPointLevel->get_Format()->get_Fill()->set_FillType(FillType::Solid);
dataPointLevel->get_Format()->get_Fill()->get_SolidFillColor()->set_Color(Color::get_Red());
```

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IFormat](../../iformat/)
* 클래스 [IChartDataPointLevel](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)