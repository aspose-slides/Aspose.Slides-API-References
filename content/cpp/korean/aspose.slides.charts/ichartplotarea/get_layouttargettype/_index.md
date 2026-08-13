---
title: get_LayoutTargetType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 플롯 영역의 레이아웃이 수동으로 정의된 경우, 이 속성은 플롯 영역을 내부(축 및 축 레이블 제외)로 레이아웃할지 외부(축 및 축 레이블 포함)로 레이아웃할지를 지정합니다. LayoutTargetType을 읽으세요.
type: docs
weight: 14
url: /ko/aspose.slides.charts/ichartplotarea/get_layouttargettype/
---
## IChartPlotArea::get_LayoutTargetType() 메서드


플롯 영역의 레이아웃이 수동으로 정의된 경우, 이 속성은 플롯 영역을 내부(축 및 축 레이블 제외)로 레이아웃할지 외부(축 및 축 레이블 포함)로 레이아웃할지를 지정합니다. [LayoutTargetType](../../layouttargettype/)를 읽으십시오.

```cpp
virtual Aspose::Slides::Charts::LayoutTargetType Aspose::Slides::Charts::IChartPlotArea::get_LayoutTargetType()=0
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

## 참고

* Enum [LayoutTargetType](../../layouttargettype/)
* 클래스 [IChartPlotArea](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)