---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/ichartdata/series_groups/
weight: 140
---
## series_groups 속성
시리즈의 그룹을 가져옵니다.
읽기 전용 [`IChartSeriesGroupCollection`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroupcollection).


### 비고

1) 각 시리즈 그룹은 결합 가능한 유형의 시리즈를 포함합니다. 결합 가능한 시리즈 유형 그룹은 CombinableSeriesTypesGroup 열거형으로 정의 및 설명됩니다. 또한 각 시리즈 그룹은 기본 축이나 보조 축에 플롯되는 시리즈를 포함합니다(한 그룹에 두 경우 모두 포함되지 않음). 따라서 시리즈 그룹화 원칙은 위에서 언급된 유형 그룹과 기본/보조 플롯 유형에 따라 그룹화하는 것입니다.

2) 시리즈 그룹은 그룹 내 각 시리즈에 공통적인 몇몇 시리즈 속성을 포함합니다("series group properties"). ChartSeriesGroup 클래스의 "series group properties"은 읽기/쓰기 가능합니다. 각 "series group properties"은 ChartSeries 클래스에서 읽기 전용 프젝션을 가질 수 있습니다.

### 정의:
```python
@property
def series_groups(self):
    ...
```


### 참조
* 클래스 [`IChartData`](/slides/python-net/ko/aspose.slides.charts/ichartdata)
* 클래스 [`IChartSeriesGroupCollection`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroupcollection)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)