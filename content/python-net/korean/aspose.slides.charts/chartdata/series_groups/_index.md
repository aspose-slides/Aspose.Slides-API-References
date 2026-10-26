---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.charts/chartdata/series_groups/
weight: 140
---
## series_groups 속성
Gets the groups of series.
            읽기 전용 [`IChartSeriesGroupCollection`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroupcollection).

### 비고

1) 각 시리즈 그룹은 조합 가능한 유형의 시리즈를 포함합니다. 조합 가능한 시리즈 유형 그룹은 
            CombinableSeriesTypesGroup enum으로 정의 및 설명됩니다.
            또한 각 시리즈 그룹은 기본 축 또는 보조 축에 플롯되는 시리즈를 포함합니다(한 그룹에서 두 경우를 모두 포함하지 않음).
            따라서 시리즈 그룹화의 원칙은 위에서 언급한 유형 그룹과 기본/보조 플롯 유형에 따라 그룹화하는 것입니다.

2) 시리즈 그룹은 그룹 내 각 시리즈에 공통적인 일부 시리즈 속성(“series group properties”)을 포함합니다.
            "Series group properties" in ChartSeriesGroup class는 읽기/쓰기 가능합니다.
            각 "series group properties"는 ChartSeries class에서 읽기 전용 투영을 가질 수 있습니다.

### 정의:
```python
@property
def series_groups(self):
    ...
```

### 또 보기
* 클래스 [`ChartData`](/slides/python-net/ko/aspose.slides.charts/chartdata)
* 클래스 [`IChartSeriesGroupCollection`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroupcollection)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)