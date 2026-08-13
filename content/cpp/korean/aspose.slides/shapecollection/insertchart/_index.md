---
title: InsertChart()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 차트를 생성하고, 샘플 시리즈 데이터와 설정으로 초기화한 뒤, 지정된 인덱스에 shape 컬렉션에 삽입합니다.
type: docs
weight: 92
url: /ko/aspose.slides/shapecollection/insertchart/
---
## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) method

새 차트를 생성하고, 샘플 시리즈 데이터와 설정으로 초기화한 뒤, 지정된 인덱스에 shape 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 생성할 차트 유형입니다. |
| x | **float** | 새 차트의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 차트의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새 차트의 너비(포인트 단위)입니다. |
| height | **float** | 새 차트의 높이(포인트 단위)입니다. |
| index | **int32_t** | shape 컬렉션에 새 차트를 삽입할 0 기반 인덱스입니다. |

### 반환 값

새로 만든 [Charts::IChart](../../../aspose.slides.charts/ichart/).

## ShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) method

새 차트를 생성하고, 샘플 시리즈 데이터와 설정으로 초기화한 뒤, 지정된 인덱스에 shape 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<Charts::IChart> Aspose::Slides::ShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 생성할 차트 유형입니다. |
| x | **float** | 새 차트의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 차트의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새 차트의 너비(포인트 단위)입니다. |
| height | **float** | 새 차트의 높이(포인트 단위)입니다. |
| index | **int32_t** | shape 컬렉션에 새 차트를 삽입할 0 기반 인덱스입니다. |
| initWithSample | **bool** | true이면 샘플 시리즈 데이터와 설정으로 차트를 초기화하고, false이면 시리즈 없이 최소 설정만으로 차트를 생성하여 생성 속도를 높입니다. |

### 반환 값

새로 만든 [Charts::IChart](../../../aspose.slides.charts/ichart/).

## 또보기

* 열거형 [ChartType](../../../aspose.slides.charts/charttype/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChart](../../../aspose.slides.charts/ichart/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)