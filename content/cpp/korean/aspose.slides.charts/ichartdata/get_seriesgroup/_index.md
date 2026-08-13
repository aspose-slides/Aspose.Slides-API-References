---
title: get_SeriesGroup()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 
type: docs
weight: 222
url: /ko/aspose.slides.charts/ichartdata/get_seriesgroup/
---
## IChartData::get_SeriesGroup(System::SharedPtr\<IChartSeries\>) 메서드




```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(System::SharedPtr<IChartSeries> ofSeries)=0
```

## IChartData::get_SeriesGroup(int32_t) 메서드


지정된 인덱스에 해당하는 시리즈 그룹을 반환합니다.

```cpp
virtual System::SharedPtr<IChartSeriesGroup> Aspose::Slides::Charts::IChartData::get_SeriesGroup(int32_t index)=0
```

## 비고


1) 각 시리즈 그룹은 결합 가능한 유형의 시리즈를 포함합니다. 결합 가능한 시리즈 유형 그룹은 CombinableSeriesTypesGroup 열거형으로 정의 및 설명됩니다. 또한 각 시리즈 그룹은 기본 축 또는 보조 축에 플롯되는 시리즈를 포함합니다(하나의 그룹에 두 경우가 동시에 있지는 않음). 따라서 시리즈 그룹화 원칙은 앞서 언급한 유형 그룹과 기본/보조 플롯 유형에 따라 그룹화하는 것입니다. 2) 시리즈 그룹은 그룹 내 모든 시리즈에 공통적인 일부 시리즈 속성(\"시리즈 그룹 속성\")을 포함합니다. [ChartSeriesGroup](../../chartseriesgroup/) 클래스의 \"시리즈 그룹 속성\"은 읽기/쓰기 가능하며, [ChartSeries](../../chartseries/) 클래스의 \"시리즈 그룹 속성\"은 읽기 전용 투영을 가질 수 있습니다.
## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartSeriesGroup](../../ichartseriesgroup/)
* 클래스 [IChartSeries](../../ichartseries/)
* 클래스 [IChartData](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)