---
title: AddDataPointForSurfaceSeries()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. chartType이 Surface 하위 유형 중 하나인 시리즈에 적용됩니다 (ChartTypeCharacterizer.IsChartTypeSurface(ChartType) 메서드 참고).
type: docs
weight: 261
url: /ko/aspose.slides.charts/ichartdatapointcollection/adddatapointforsurfaceseries/
---
## IChartDataPointCollection::AddDataPointForSurfaceSeries(System::SharedPtr\<IChartDataCell\>) 메서드

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. chartType이 Surface 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.IsChartTypeSurface(ChartType)](../../charttypecharacterizer/ischarttypesurface/) 메서드도 참조).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForSurfaceSeries(System::SharedPtr<IChartDataCell> value)=0
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | 데이터 포인트 값 |

### 반환값

새 데이터 포인트.

## IChartDataPointCollection::AddDataPointForSurfaceSeries(double) 메서드

새 데이터 포인트를 생성하고 컬렉션 끝에 추가합니다. chartType이 Surface 하위 유형 중 하나인 시리즈에 적용됩니다 ([ChartTypeCharacterizer.IsChartTypeSurface(ChartType)](../../charttypecharacterizer/ischarttypesurface/) 메서드도 참조).

```cpp
virtual System::SharedPtr<IChartDataPoint> Aspose::Slides::Charts::IChartDataPointCollection::AddDataPointForSurfaceSeries(double value)=0
```

### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| value | **double** | 데이터 포인트 값 |

### 반환값

새 데이터 포인트.

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataPoint](../../ichartdatapoint/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [IChartDataPointCollection](../)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)