---
title: error_bars_y_format property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/ichartseries/error_bars_y_format/
weight: 120
---
## error_bars_y_format 속성
Represents ErrorBars를 Y 방향으로 시리즈에 적용합니다.

            ErrorBars는 Y 방향이 있는 시리즈 유형 area, bar, line, scatter 및 bubble에 대해 사용할 수 있습니다.
            다른 모든 차트 유형에 대해 이 속성은 None을 반환합니다 (3D 차트를 포함).
            사용자 정의 값을 사용하는 경우 DataPoints 컬렉션을 사용하여 값을 지정합니다
            (with [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 속성).

            읽기 전용 [`IErrorBarsFormat`](/slides/python-net/ko/aspose.slides.charts/ierrorbarsformat).

### 정의:
```python
@property
def error_bars_y_format(self):
    ...
```

### 참고
* 클래스 [`IChartSeries`](/slides/python-net/ko/aspose.slides.charts/ichartseries)
* 클래스 [`IErrorBarsFormat`](/slides/python-net/ko/aspose.slides.charts/ierrorbarsformat)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)