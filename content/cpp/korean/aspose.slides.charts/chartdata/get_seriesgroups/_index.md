---
title: get_SeriesGroups()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 시리즈 그룹을 가져옵니다. 읽기 전용 IChartSeriesGroupCollection.
type: docs
weight: 27
url: /ko/aspose.slides.charts/chartdata/get_seriesgroups/
---
## ChartData::get_SeriesGroups() 메서드

시리즈 그룹을 가져옵니다. 읽기 전용 [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/).

```cpp
System::SharedPtr<IChartSeriesGroupCollection> Aspose::Slides::Charts::ChartData::get_SeriesGroups() override
```

## 비고

1) 각 시리즈 그룹은 결합 가능한 유형을 갖는 시리즈를 포함합니다. 결합 가능한 시리즈 유형 그룹은 CombinableSeriesTypesGroup 열거형으로 정의 및 설명됩니다. 또한 각 시리즈 그룹은 기본 축이나 보조 축에 플롯되는 시리즈를 포함합니다(한 그룹에 두 경우가 모두 포함되지 않음). 따라서 시리즈 그룹화 원칙은 앞에서 언급한 유형 그룹과 기본/보조 플롯 유형에 따라 그룹화하는 것입니다.

2) 시리즈 그룹은 그룹 내 각 시리즈에 공통적인 일부 시리즈 속성(\"시리즈 그룹 속성\")을 포함합니다. [ChartSeriesGroup](../../chartseriesgroup/) 클래스의 \"시리즈 그룹 속성\"은 읽기/쓰기 가능합니다. \"시리즈 그룹 속성\" 각각은 [ChartSeries](../../chartseries/) 클래스에서 읽기 전용 프로젝션을 가질 수 있습니다.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartSeriesGroupCollection](../../ichartseriesgroupcollection/)
* 클래스 [ChartData](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)