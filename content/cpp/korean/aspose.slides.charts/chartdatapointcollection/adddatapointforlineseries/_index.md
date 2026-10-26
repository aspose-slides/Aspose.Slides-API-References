---
title: AddDataPointForLineSeries()
second_title: Aspose.Slides for C++ API 레퍼런스
description: "새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 라인 하위 유형 중 하나인 시리즈에 적용됩니다 (또한 ChartTypeCharacterizer::IsChartTypeLine(ChartType) 메서드)."
type: docs
weight: 222
url: /ko/aspose.slides.charts/chartdatapointcollection/adddatapointforlineseries/
---
## ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr\<IChartDataCell\>) 메서드

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 라인 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) 메서드도 참조).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(System::SharedPtr<IChartDataCell> value) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 데이터 포인트 값. |

### 반환 값

새 데이터 포인트.

## ChartDataPointCollection::AddDataPointForLineSeries(double) 메서드

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 라인 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer::IsChartTypeLine(ChartType)](../../charttypecharacterizer/ischarttypeline/) 메서드도 참조).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForLineSeries(double value) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | **double** | 데이터 포인트 값. |

### 반환 값

새 데이터 포인트.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataPoint](../../ichartdatapoint/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [ChartDataPointCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)