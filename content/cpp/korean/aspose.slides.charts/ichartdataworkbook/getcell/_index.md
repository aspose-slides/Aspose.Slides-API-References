---
title: GetCell()
second_title: Aspose.Slides for C++ API 참조
description: 차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다
type: docs
weight: 40
url: /ko/aspose.slides.charts/ichartdataworkbook/getcell/
---
## IChartDataWorkbook::GetCell(System::String, int32_t, int32_t) 메서드

차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(System::String worksheetName, int32_t row, int32_t column)=0
```

### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| worksheetName | [System::String](../../../system/string/) | 워크시트 이름입니다. |
| row | **int32_t** | 행. |
| column | **int32_t** | 열. |

### 반환값

[Cell](../../../aspose.slides/cell/) 객체

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t) 메서드

차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column)=0
```

### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 워크시트 인덱스입니다. |
| row | **int32_t** | 행. |
| column | **int32_t** | 열. |

### 반환값

[Cell](../../../aspose.slides/cell/) 객체

## IChartDataWorkbook::GetCell(int32_t, System::String) 메서드

차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName)=0
```

### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 워크시트 인덱스입니다. |
| cellName | [System::String](../../../system/string/) | 셀 이름입니다. |

### 반환값

[Cell](../../../aspose.slides/cell/) 객체

## IChartDataWorkbook::GetCell(int32_t, System::String, System::SharedPtr\<System::Object\>) 메서드

차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, System::String cellName, System::SharedPtr<System::Object> value)=0
```

### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 워크시트 인덱스입니다. |
| cellName | [System::String](../../../system/string/) | 셀 이름입니다. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 값. |

### 반환값

[Cell](../../../aspose.slides/cell/) 객체

## IChartDataWorkbook::GetCell(int32_t, int32_t, int32_t, System::SharedPtr\<System::Object\>) 메서드

차트 시리즈 또는 카테고리에 사용할 수 있는 셀을 가져옵니다

```cpp
virtual System::SharedPtr<IChartDataCell> Aspose::Slides::Charts::IChartDataWorkbook::GetCell(int32_t worksheetIndex, int32_t row, int32_t column, System::SharedPtr<System::Object> value)=0
```

### 인수

| 매개 변수 | 형식 | 설명 |
| --- | --- | --- |
| worksheetIndex | **int32_t** | 워크시트 인덱스입니다. |
| row | **int32_t** | 행. |
| column | **int32_t** | 열. |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[System::Object](../../../system/object/)\> | 값. |

### 반환값

[Cell](../../../aspose.slides/cell/) 객체

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChartDataCell](../../ichartdatacell/)
* 클래스 [String](../../../system/string/)
* 클래스 [IChartDataWorkbook](../)
* 클래스 [Object](../../../system/object/)
* 네임스페이스 [Aspose::Slides::Charts](../../)
* 라이브러리 [Aspose.Slides](../../../)