---
title: get_ErrorBarsYFormat()
second_title: Aspose.Slides for C++ API 참조
description: Y 방향의 시리즈 ErrorBars를 나타냅니다.
type: docs
weight: 235
url: /ko/aspose.slides.charts/chartseries/get_errorbarsyformat/
---
## ChartSeries::get_ErrorBarsYFormat() 메서드


Y 방향의 시리즈 ErrorBars를 나타냅니다.

```cpp
System::SharedPtr<IErrorBarsFormat> Aspose::Slides::Charts::ChartSeries::get_ErrorBarsYFormat() override
```

## 비고


Y 방향의 ErrorBars는 area, bar, line, scatter, bubble 유형의 시리즈에 사용할 수 있습니다. 다른 차트 유형에 대해서는 이 속성이 null을 반환합니다(3D 차트 포함). 사용자 지정 값을 사용하는 경우 DataPoints 컬렉션을 사용하여 값을 지정하십시오([IChartDataPoint::get_ErrorBarsCustomValues()](../../ichartdatapoint/get_errorbarscustomvalues/) 속성 사용). 

읽기 전용 [IErrorBarsFormat](../../ierrorbarsformat/). 
## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IErrorBarsFormat](../../ierrorbarsformat/)
* 클래스 [ChartSeries](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)