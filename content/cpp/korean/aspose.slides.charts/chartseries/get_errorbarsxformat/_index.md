---
title: get_ErrorBarsXFormat()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시리즈의 X 방향 ErrorBars를 나타냅니다.
type: docs
weight: 222
url: /ko/aspose.slides.charts/chartseries/get_errorbarsxformat/
---
## ChartSeries::get_ErrorBarsXFormat() 메서드


시리즈의 X 방향 ErrorBars를 나타냅니다.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsXFormat() override
```

## 비고


X 방향 ErrorBars는 area, bar, scatter, bubble 유형의 시리즈에 대해 사용할 수 있습니다. 다른 모든 차트 유형에서는 이 속성이 null을 반환합니다 (3D 차트 포함). 사용자 정의 값을 지정하려면 DataPoints 컬렉션을 사용하여 값을 지정하십시오 ([IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) 속성 사용). 

읽기 전용 [IErrorBarsFormat](../../ierrorbarsformat/). 
## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IErrorBarsFormat](../../ierrorbarsformat/)
* 클래스 [ChartSeries](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)