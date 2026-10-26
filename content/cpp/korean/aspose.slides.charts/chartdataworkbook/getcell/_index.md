---
title: GetCell()
second_title: Aspose.Slides for C++ API 참조
description: 차트 시리즈 또는 범주에 사용할 수 있는 셀을 가져옵니다
type: docs
weight: 27
url: /ko/aspose.slides.charts/chartdataworkbook/getcell/
---
## ChartDataWorkbook::GetCell(System::String, int32_t, int32_t) 메서드

차트 시리즈 또는 범주에 사용할 수 있는 셀을 가져옵니다

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 워크시트 이름입니다. |
| row | **int32_t** | 행입니다. |
| column | **int32_t** | 열입니다. |

### 반환값

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) 메서드

차트 시리즈 또는 범주에 사용할 수 있는 셀을 가져옵니다

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 워크시트 인덱스입니다. |
| row | **int32_t** | 행입니다. |
| column | **int32_t** | 열입니다. |

### 반환값

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String) 메서드

차트 시리즈 또는 범주에 사용할 수 있는 셀을 가져옵니다

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 워크시트 인덱스입니다. |
| cellName | [System::String](../../../system/string/) | 셀 이름입니다. |

### 반환값

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) 메서드

차트 시리즈 또는 범주에 사용할 수 있는 셀을 가져옵니다

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 워크시트 인덱스입니다. |
| cellName | [System::String](../../../system/string/) | 셀 이름입니다. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 값입니다. |

### 반환값

[Cell](../../../aspose.slides/cell/) object

## ChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) 메서드

차트 시리즈 또는 범주에 사용할 수 있는 셀을 가져옵니다

```cpp
System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::ChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 워크시트 인덱스입니다. |
| row | **int32_t** | 행입니다. |
| column | **int32_t** | 열입니다. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 값입니다. |

### 반환값

[Cell](../../../aspose.slides/cell/) object

## 또 보기

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [String](../../../system/string/)
* 클래스 [ChartDataWorkbook](../)
* 클래스 [Object](../../../system/object/)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)