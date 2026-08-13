---
title: set_LayoutTargetType()
second_title: Aspose.Slides for C++ API 참조
description: 플롯 영역의 레이아웃이 수동으로 정의된 경우, 이 속성은 플롯 영역을 내부(축 및 축 레이블 제외)로 레이아웃할지 외부(축 및 축 레이블 포함)로 레이아웃할지를 지정합니다. LayoutTargetType을 작성하십시오.
type: docs
weight: 27
url: /ko/aspose.slides.charts/ichartplotarea/set_layouttargettype/
---
## IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType) method

플롯 영역의 레이아웃이 수동으로 정의된 경우, 이 속성은 플롯 영역을 내부(축 및 축 레이블 제외)로 레이아웃할지 외부(축 및 축 레이블 포함)로 레이아웃할지를 지정합니다. [LayoutTargetType](../../layouttargettype/)를 작성하십시오.

```cpp
virtual void Aspose::Slides::Charts::IChartPlotArea::set_LayoutTargetType(Aspose::Slides::Charts::LayoutTargetType value)=0
```

## 비고

```cpp
auto presentation = MakeObject<Presentation>();
auto slide = presentation->get_Slides()->idx_get(0);
auto chart = slide->get_Shapes()->AddChart(ChartType::ClusteredColumn, 20.0f, 100.0f, 600.0f, 400.0f);

chart->get_PlotArea()->set_X(0.2f);
chart->get_PlotArea()->set_Y(0.2f);
chart->get_PlotArea()->set_Width(0.7f);
chart->get_PlotArea()->set_Height(0.7f);

chart->get_PlotArea()->set_LayoutTargetType(LayoutTargetType::Inner);
// ...
```

## 관련 항목

* 열거형 [LayoutTargetType](../../layouttargettype/)
* 클래스 [IChartPlotArea](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)