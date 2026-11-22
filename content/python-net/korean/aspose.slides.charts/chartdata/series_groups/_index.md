---
title: series_groups property
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.charts/chartdata/series_groups/
weight: 150
---
## series_groups 속성
시리즈 그룹을 가져옵니다.  
읽기 전용 [`IChartSeriesGroupCollection`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroupcollection).

### 비고

1) 각 시리즈 그룹은 결합 가능한 유형의 시리즈를 포함합니다. 결합 가능한 시리즈 유형의 그룹은 CombinableSeriesTypesGroup enum으로 정의되고 설명됩니다. 또한 각 시리즈 그룹은 주 축 또는 보조 축 중 하나에 플롯되는 시리즈를 포함합니다(하나의 그룹에 두 경우가 동시에 존재하지 않음). 따라서 시리즈 그룹화 원칙은 위에서 언급한 유형 그룹과 주/보조 플롯 유형에 따라 그룹화하는 것입니다.

2) 시리즈 그룹은 그룹 내 모든 시리즈에 공통인 일부 시리즈 속성을 포함합니다("series group properties"). ChartSeriesGroup 클래스의 "Series group properties"는 읽기/쓰기 가능합니다. 각 "series group properties"는 ChartSeries 클래스에서 읽기 전용 투영을 가질 수 있습니다.

### 정의:
```python
@property
def series_groups(self):
    ...
```

### 참고
* 클래스 [`ChartData`](/slides/python-net/ko/aspose.slides.charts/chartdata)
* 클래스 [`IChartSeriesGroupCollection`](/slides/python-net/ko/aspose.slides.charts/ichartseriesgroupcollection)
* 모듈 [`aspose.slides.charts`](/slides/python-net/ko/aspose.slides.charts)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)