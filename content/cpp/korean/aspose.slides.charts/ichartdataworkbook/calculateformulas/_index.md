---
title: CalculateFormulas()
second_title: Aspose.Slides for C++ API 참조
description: 워크북의 모든 수식을 계산하고 해당 셀 값들을 업데이트합니다.
type: docs
weight: 14
url: /ko/aspose.slides.charts/ichartdataworkbook/calculateformulas/
---
## IChartDataWorkbook::CalculateFormulas() 메서드

워크북의 모든 수식을 계산하고 해당 셀 값들을 업데이트합니다.

```cpp
virtual void Aspose::Slides::Charts::IChartDataWorkbook::CalculateFormulas()=0
```

## 비고

예제는 셀에 수식을 할당하고 값을 계산하는 방법을 보여줍니다. \"B4\" 셀의 값이 5로 설정됩니다.

```cpp
auto pres = System::MakeObject<Presentation>();

auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(ChartType::Pie, 100.0f, 100.0f, 300.0f, 400.0f);
auto wb = chart->get_ChartData()->get_ChartDataWorkbook();
wb->GetCell(0, u"B2", ObjectExt::Box<int32_t>(2));
wb->GetCell(0, u"B3", ObjectExt::Box<int32_t>(3));
wb->GetCell(0, u"B4")->set_Formula(u"B2+B3");
wb->CalculateFormulas();
//...
```

## 참조

* 클래스 [IChartDataWorkbook](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)