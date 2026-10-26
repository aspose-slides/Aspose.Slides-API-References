---
title: value_type property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/errorbarsformat/value_type/
weight: 120
---
## value_type 속성
오차 막대의 길이를 결정하는 가능한 방법들을 나타냅니다. 
            사용자 지정 값 유형인 경우, 값을 지정하려면 시리즈의 DataPoints 컬렉션에 있는 특정 데이터 포인트의 [`IChartDataPoint.error_bars_custom_values`](/slides/python-net/ko/aspose.slides.charts/ichartdatapoint/error_bars_custom_values) 속성을 사용합니다.
            Fixed, Percentage 또는 StandardDeviation 값 유형인 경우, 값을 지정하려면 Value 속성을 사용합니다.  
            읽기/쓰기 [`ErrorBarValueType`](/slides/python-net/ko/aspose.slides.charts/errorbarvaluetype).

### 정의:
```python
@property
def value_type(self):
    ...

@value_type.setter
def value_type(self, value):
    ...
```

### 참고
* 클래스 [`ErrorBarsFormat`](/slides/python-net/ko/aspose.slides.charts/errorbarsformat)
* 열거형 [`ErrorBarValueType`](/slides/python-net/ko/aspose.slides.charts/errorbarvaluetype)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)