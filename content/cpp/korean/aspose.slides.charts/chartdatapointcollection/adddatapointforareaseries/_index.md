---
title: AddDataPointForAreaSeries()
second_title: Aspose.Slides for C++ API 참조
description: "새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. chartType이 Area 하위 유형 중 하나인 시리즈에 적용됩니다 (ChartTypeCharacterizer::IsChartTypeArea(ChartType) 메서드도 참조하십시오)."
type: docs
weight: 274
url: /ko/aspose.slides.charts/chartdatapointcollection/adddatapointforareaseries/
---
## ChartDataPointCollection::AddDataPointForAreaSeries(System::SharedPtr\<IChartDataCell\>) 메서드

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. chartType이 Area 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer::IsChartTypeArea(ChartType)](../../charttypecharacterizer/ischarttypearea/) 메서드도 참조하십시오).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForAreaSeries(System::SharedPtr<IChartDataCell> value) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Data point Value |

### 반환값

새 데이터 포인트.

## ChartDataPointCollection::AddDataPointForAreaSeries(double) 메서드

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. chartType이 Area 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer::IsChartTypeArea(ChartType)](../../charttypecharacterizer/ischarttypearea/) 메서드도 참조하십시오).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForAreaSeries(double value) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | **double** | Data point Value |

### 반환값

새 데이터 포인트.

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataPoint](../../ichartdatapoint/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [ChartDataPointCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)