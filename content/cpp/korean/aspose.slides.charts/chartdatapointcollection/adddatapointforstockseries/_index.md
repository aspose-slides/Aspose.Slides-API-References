---
title: AddDataPointForStockSeries()
second_title: Aspose.Slides for C++ API 참조
description: "새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Stock 하위 유형 중 하나인 시리즈에 적용됩니다 (또한 ChartTypeCharacterizer::IsChartTypeStock(ChartType) 메서드 참조)."
type: docs
weight: 209
url: /ko/aspose.slides.charts/chartdatapointcollection/adddatapointforstockseries/
---
## ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr\<IChartDataCell\>) 메서드

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Stock 하위 유형 중 하나인 시리즈에 적용됩니다 (또한 [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) 메서드).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(System::SharedPtr<IChartDataCell> value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 데이터 포인트 값. |

### 반환 값

새 데이터 포인트.

## ChartDataPointCollection::AddDataPointForStockSeries(double) 메서드

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 Stock 하위 유형 중 하나인 시리즈에 적용됩니다 (또한 [ChartTypeCharacterizer::IsChartTypeStock(ChartType)](../../charttypecharacterizer/ischarttypestock/) 메서드).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForStockSeries(double value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **double** | 데이터 포인트 값. |

### 반환 값

새 데이터 포인트.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataPoint](../../ichartdatapoint/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [ChartDataPointCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)