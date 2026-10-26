---
title: get_SeriesGroups()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시리즈 그룹을 가져옵니다. 읽기 전용 IChartSeriesGroupCollection.
type: docs
weight: 27
url: /ko/aspose.slides.charts/ichartdata/get_seriesgroups/
---
## IChartData::get_SeriesGroups() 메서드

시리즈 그룹을 가져옵니다. 읽기 전용 [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
virtual System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::IChartData::get_SeriesGroups()=0
```

## 비고

1) 각 시리즈 그룹은 결합 가능한 유형의 시리즈를 포함합니다. 결합 가능한 시리즈 유형 그룹은 CombinableSeriesTypesGroup enum으로 정의되고 설명됩니다. 또한 각 시리즈 그룹은 주축에 플롯되거나 보조 축에 플롯되는 시리즈를 포함합니다(하나의 그룹에 두 경우가 모두 포함되지는 않습니다). 따라서 시리즈 그룹화 원칙은 앞에서 언급한 유형 그룹과 주/보조 플롯 유형에 따라 그룹화하는 것입니다.

2) 시리즈 그룹에는 그룹 내 각 시리즈에 공통적인 일부 시리즈 속성("series group properties")이 포함됩니다. [ChartSeriesGroup](../../chartseriesgroup/) 클래스의 "Series group properties"는 읽기/쓰기 가능합니다. 각 "series group properties"는 [ChartSeries](../../chartseries/) 클래스에서 읽기 전용 프로젝션을 가질 수 있습니다.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* 클래스 [IChartData](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)