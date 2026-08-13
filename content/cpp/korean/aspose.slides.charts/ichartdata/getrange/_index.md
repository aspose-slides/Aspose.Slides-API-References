---
title: GetRange()
second_title: Aspose.Slides for C++ API 참조
description: 차트 데이터 범위를 가져옵니다.
type: docs
weight: 170
url: /ko/aspose.slides.charts/ichartdata/getrange/
---
## IChartData::GetRange() method

차트 데이터 범위를 가져옵니다.

```cpp
virtual System::String Aspose::Slides::Charts::IChartData::GetRange()=0
```

### 반환값

셀 데이터 범위 수식. 예: \"Sheet1!$A$1:$C$4\"
## 비고

```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 100.0f, 100.0f, 500.0f, 400.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [IChartData](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)