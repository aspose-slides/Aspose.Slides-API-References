---
title: AddDataPointForPieSeries()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 파이 서브타입 중 하나인 시리즈에 적용됩니다 (ChartTypeCharacterizer.IsChartTypePie(ChartType) 메서드 참조).
type: docs
weight: 222
url: /ko/aspose.slides.charts/ichartdatapointcollection/adddatapointforpieseries/
---
## IChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr\<IChartDataCell\>) 메서드


새 데이터를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 파이 서브타입 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) 메서드 참고).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForPieSeries(System::SharedPtr<IChartDataCell> value)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 데이터 포인트 값 |

### 반환 값

새 데이터 포인트.

## IChartDataPointCollection::AddDataPointForPieSeries(double) 메서드


새 데이터를 생성하고 컬렉션 끝에 추가합니다. 차트 유형이 파이 서브타입 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.IsChartTypePie(ChartType)](../../charttypecharacterizer/ischarttypepie/) 메서드 참고).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForPieSeries(double value)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **double** | 데이터 포인트 값 |

### 반환 값

새 데이터 포인트.

## 참고

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataPoint](../../ichartdatapoint/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [IChartDataPointCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)