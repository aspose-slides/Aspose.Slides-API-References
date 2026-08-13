---
title: AddDataPointForDoughnutSeries()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. 차트 유형이 Doughnut 하위 유형 중 하나인 시리즈에 적용됩니다 (ChartTypeCharacterizer::IsChartTypeDoughnut(ChartType) 메서드도 참조하십시오)."
type: docs
weight: 300
url: /ko/aspose.slides.charts/chartdatapointcollection/adddatapointfordoughnutseries/
---
## ChartDataPointCollection::AddDataPointForDoughnutSeries(System::SharedPtr\<IChartDataCell\>) 메서드

새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. 차트 유형이 Doughnut 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer::IsChartTypeDoughnut(ChartType)](../../charttypecharacterizer/ischarttypedoughnut/) 메서드도 참조하십시오).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForDoughnutSeries(System::SharedPtr<IChartDataCell> value) override
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 데이터 포인트 값 |

### 반환 값

새 데이터 포인트.

## ChartDataPointCollection::AddDataPointForDoughnutSeries(double) 메서드

새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. 차트 유형이 Doughnut 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer::IsChartTypeDoughnut(ChartType)](../../charttypecharacterizer/ischarttypedoughnut/) 메서드도 참조하십시오).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForDoughnutSeries(double value) override
```

### 매개변수

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | 데이터 포인트 값 |

### 반환 값

새 데이터 포인트.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataPoint](../../ichartdatapoint/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [ChartDataPointCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)