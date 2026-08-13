---
title: GetRange()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 차트 데이터 범위를 가져옵니다.
type: docs
weight: 157
url: /ko/aspose.slides.charts/chartdata/getrange/
---
## ChartData::GetRange() 메서드


차트 데이터 범위를 가져옵니다.

```cpp
System::String Aspose::Slides::Charts::ChartData::GetRange() override
```


### 반환값

셀 데이터 범위 수식. 예: "Sheet1!$A$1:$C$4"
## 비고




```cpp
auto pres = MakeObject<Presentation>();
auto chart = pres->get_Slides()->idx_get(0)->get_Shapes()->AddChart(Charts::ChartType::PercentsStackedBar, 0.0f, 0.0f, 100.0f, 100.0f);
String result = (AsCast<Charts::ChartData>(chart->get_ChartData()))->GetRange();
```

## 참조

* 클래스 [String](../../../system/string/)
* 클래스 [ChartData](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)