---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 차트 시리즈를 생성하고 컬렉션에 추가합니다.
type: docs
weight: 14
url: /ko/aspose.slides.charts/ichartseriescollection/add/
---
## IChartSeriesCollection::Add(ChartType) 메서드

새 차트 시리즈를 만들고 컬렉션에 추가합니다.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(ChartType type)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | 시리즈 유형 |

### 반환값

새 차트 시리즈.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) 메서드

새 차트 시리즈를 [IChartDataCell](../../ichartdatacell/)에서 만들고 컬렉션에 추가합니다.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) 은 시리즈 이름을 포함합니다. |
| type | [ChartType](../../charttype/) | 시리즈 유형을 설정하는 타입 |

### 반환값

컬렉션에 이미 존재하는 차트 시리즈 또는 시리즈를 추가합니다.

## 비고

컬렉션에 이미 동일한 셀에서 생성된 차트 시리즈가 있으면 메서드는 아무 것도 추가하지 않고 해당 인덱스를 반환합니다.

## IChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) 메서드

새 차트 시리즈를 [IChartCellCollection](../../ichartcellcollection/)에서 만들고 컬렉션에 추가합니다.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | 시리즈 이름을 포함하는 셀 |
| type | [ChartType](../../charttype/) | 시리즈 유형을 설정하는 타입 |

### 반환값

컬렉션에 이미 존재하는 차트 시리즈 또는 시리즈를 추가합니다.

## 비고

컬렉션에 이미 동일한 셀에서 생성된 차트 시리즈가 있으면 메서드는 아무 것도 추가하지 않고 해당 인덱스를 반환합니다.

## IChartSeriesCollection::Add(System::String, ChartType) 메서드

값에서 새 차트 시리즈를 만들고 컬렉션에 추가합니다.

```cpp
virtual System::SharedPtr<IChartSeries> Aspose::Slides::Charts::IChartSeriesCollection::Add(System::String name, ChartType type)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | 시리즈 이름 |
| type | [ChartType](../../charttype/) | 시리즈 유형을 설정하는 타입 |

### 반환값

추가된 차트 시리즈.

## 참고

* 열거형 [ChartType](../../charttype/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartSeries](../../ichartseries/)
* 클래스 [IChartSeriesCollection](../)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [IChartCellCollection](../../ichartcellcollection/)
* 클래스 [String](../../../system/string/)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)