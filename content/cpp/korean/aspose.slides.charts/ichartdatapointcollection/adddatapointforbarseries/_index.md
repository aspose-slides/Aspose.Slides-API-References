---
title: AddDataPointForBarSeries()
second_title: Aspose.Slides for C++ API 참조
description: 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Column 또는 Bar 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer.IsChartTypeColumn(ChartType) 및 ChartTypeCharacterizer.IsChartTypeBar(ChartType) 메서드를 참조하십시오).
type: docs
weight: 196
url: /ko/aspose.slides.charts/ichartdatapointcollection/adddatapointforbarseries/
---
## IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr\<IChartDataCell\>) 메서드

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 [Column](../../../aspose.slides/column/) 중 하나이거나 Bar 하위 유형인 시리즈에 적용됩니다(또한 [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) 및 [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) 메서드를 참조하십시오).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 데이터 포인트 값 |

### 반환값

새 데이터 포인트.

## IChartDataPointCollection::AddDataPointForBarSeries(double) 메서드

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 [Column](../../../aspose.slides/column/) 중 하나이거나 Bar 하위 유형인 시리즈에 적용됩니다(또한 [ChartTypeCharacterizer.IsChartTypeColumn(ChartType)](../../charttypecharacterizer/ischarttypecolumn/) 및 [ChartTypeCharacterizer.IsChartTypeBar(ChartType)](../../charttypecharacterizer/ischarttypebar/) 메서드를 참조하십시오).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForBarSeries(double value)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **double** | 데이터 포인트 값 |

### 반환값

새 데이터 포인트.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataPoint](../../ichartdatapoint/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [IChartDataPointCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)