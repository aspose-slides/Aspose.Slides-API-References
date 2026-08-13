---
title: AddDataPointForDoughnutSeries()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. 차트 유형이 Doughnut 서브타입 중 하나인 시리즈에 적용됩니다 (ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType) 메서드도 참조).
type: docs
weight: 235
url: /ko/aspose.slides.charts/ichartdatapointcollection/adddatapointfordoughnutseries/
---
## IChartDataPointCollection::AddDataPointForDoughnutSeries(System::SharedPtr\<IChartDataCell\>) 메서드

새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. 차트 유형이 Doughnut 서브타입 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)](../../charttypecharacterizer/ischarttypedoughnut/) 메서드도 참조).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForDoughnutSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | Data point Value |

### 반환값

New data point.

## IChartDataPointCollection::AddDataPointForDoughnutSeries(double) 메서드

새 데이터 포인트를 생성하고 컬렉션의 끝에 추가합니다. 차트 유형이 Doughnut 서브타입 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.IsChartTypeDoughnut(ChartType)](../../charttypecharacterizer/ischarttypedoughnut/) 메서드도 참조).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForDoughnutSeries(double value)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **double** | Data point Value |

### 반환값

New data point.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataPoint](../../ichartdatapoint/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [IChartDataPointCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)