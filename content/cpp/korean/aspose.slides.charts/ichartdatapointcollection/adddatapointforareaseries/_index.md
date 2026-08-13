---
title: AddDataPointForAreaSeries()
second_title: Aspose.Slides for C++ API 참조
description: 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. chartType이 Area 하위 유형 중 하나인 시리즈에 적용됩니다 (ChartTypeCharacterizer.IsChartTypeArea(ChartType) 메서드도 참조).
type: docs
weight: 209
url: /ko/aspose.slides.charts/ichartdatapointcollection/adddatapointforareaseries/
---
## IChartDataPointCollection::AddDataPointForAreaSeries(System::SharedPtr\<IChartDataCell\>) 메서드

새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. chartType이 Area 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.IsChartTypeArea(ChartType)](../../charttypecharacterizer/ischarttypearea/) 메서드도 참조).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForAreaSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 데이터 포인트 값 |

### 반환 값

새 데이터 포인트.

## IChartDataPointCollection::AddDataPointForAreaSeries(double) 메서드

새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. chartType이 Area 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.IsChartTypeArea(ChartType)](../../charttypecharacterizer/ischarttypearea/) 메서드도 참조).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForAreaSeries(double value)=0
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | 데이터 포인트 값 |

### 반환 값

새 데이터 포인트.

## 관련 항목

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataPoint](../../ichartdatapoint/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [IChartDataPointCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)