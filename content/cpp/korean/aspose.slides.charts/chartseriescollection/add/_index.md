---
title: Add()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 차트 시리즈를 생성하고 컬렉션에 추가합니다.
type: docs
weight: 53
url: /ko/aspose.slides.charts/chartseriescollection/add/
---
## ChartSeriesCollection::Add(ChartType) 메서드

새 차트 시리즈를 생성하고 컬렉션에 추가합니다.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(ChartType type) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| type | [ChartType](../../charttype/) | 시리즈 유형 |

### 반환 값

새 차트 시리즈.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartDataCell\>, ChartType) 메서드

[ChartDataCell](../../chartdatacell/)에서 새 차트 시리즈를 생성하고 컬렉션에 추가합니다.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartDataCell> cellWithSeriesName, ChartType type) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cellWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartDataCell](../../ichartdatacell/)\> | [Cell](../../../aspose.slides/cell/) 시리즈 이름을 포함하는 |
| type | [ChartType](../../charttype/) | 시리즈 유형을 설정하는 유형 |

### 반환 값

컬렉션에 이미 있는 시리즈이거나 추가된 차트 시리즈.

## 참고

같은 셀에서 생성된 차트 시리즈가 이미 컬렉션에 있는 경우, 메서드는 아무것도 추가하지 않고 해당 인덱스를 반환합니다.

## ChartSeriesCollection::Add(System::SharedPtr\<IChartCellCollection\>, ChartType) 메서드

[ChartCellCollection](../../chartcellcollection/)에서 새 차트 시리즈를 생성하고 컬렉션에 추가합니다.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::SharedPtr<IChartCellCollection> cellsWithSeriesName, ChartType type) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| cellsWithSeriesName | [System::SharedPtr](../../../system/sharedptr/)\<[IChartCellCollection](../../ichartcellcollection/)\> | 시리즈 이름을 포함하는 셀 |
| type | [ChartType](../../charttype/) | 시리즈 유형을 설정하는 유형 |

### 반환 값

컬렉션에 이미 있는 시리즈이거나 추가된 차트 시리즈.

## 참고

같은 셀에서 생성된 차트 시리즈가 이미 컬렉션에 있는 경우, 메서드는 아무것도 추가하지 않고 해당 인덱스를 반환합니다.

## ChartSeriesCollection::Add(System::String, ChartType) 메서드

값에서 새 차트 시리즈를 생성하고 컬렉션에 추가합니다.

```cpp
System::SharedPtr<IChartSeries> Aspose::Slides::Charts::ChartSeriesCollection::Add(System::String name, ChartType type) override
```

### 인수

| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| name | [System::String](../../../system/string/) | 시리즈 이름 |
| type | [ChartType](../../charttype/) | 시리즈 유형을 설정하는 유형 |

### 반환 값

추가된 차트 시리즈.

## 참조

* Enum [ChartType](../../charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChartSeries](../../ichartseries/)
* Class [ChartSeriesCollection](../)
* Class [IChartDataCell](../../ichartdatacell/)
* Class [IChartCellCollection](../../ichartcellcollection/)
* Class [String](../../../system/string/)
* Namespace [Aspose::Slides::Charts](../../)
* Library [Aspose.Slides](../../../)