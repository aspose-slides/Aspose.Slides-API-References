---
title: AddDataPointForPieSeries()
second_title: Aspose.Slides C++ API 참조
description: "새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 파이 하위 유형 중 하나인 시리즈에 적용됩니다(또한 ChartTypeCharacterizer::IsChartTypePie(ChartType) 메서드 참고)."
type: docs
weight: 287
url: /ko/aspose.slides.charts/chartdatapointcollection/adddatapointforpieseries/
---
## ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr\<IChartDataCell\>) 메서드

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 파이 서브 타입 중 하나인 시리즈에 적용됩니다(또한 [ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) 메서드 참고).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr<IChartDataCell> value) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 데이터 포인트 값 |

### 반환값

새 데이터 포인트.

## ChartDataPointCollection::AddDataPointForPieSeries(double) 메서드

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 파이 서브 타입 중 하나인 시리즈에 적용됩니다(또한 [ChartTypeCharacterizer::IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) 메서드 참고).

```cpp
System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::ChartDataPointCollection::AddDataPointForPieSeries(double value) override
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
* 클래스 [ChartDataPointCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)