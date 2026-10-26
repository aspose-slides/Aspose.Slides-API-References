---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Stock 하위 유형 중 하나인 시리즈에 적용됩니다(ChartTypeCharacterizer.IsChartTypeStock(ChartType) 메서드도 참고).
type: docs
weight: 144
url: /ko/aspose.slides.charts/ichartdatapointcollection/adddatapointforstockseries/
---
## IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) method

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Stock 하위 유형 중 하나인 시리즈에 적용됩니다([ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) 메서드도 참고).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 데이터 포인트 값. |

### 반환 값

새 데이터 포인트.

## IChartDataPointCollection::AddDataPointForStockSeries(double) method

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Stock 하위 유형 중 하나인 시리즈에 적용됩니다([ChartTypeCharacterizer.IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) 메서드도 참고).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForStockSeries(double value)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **double** | 데이터 포인트 값. |

### 반환 값

새 데이터 포인트.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataPoint](../../ichartdatapoint/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [IChartDataPointCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)