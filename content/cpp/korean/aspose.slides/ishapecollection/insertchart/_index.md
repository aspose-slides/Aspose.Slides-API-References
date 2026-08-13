---
title: InsertChart()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 차트를 만들고 샘플 시리즈 데이터와 설정을 초기화한 뒤 지정된 인덱스에 shape collection에 삽입합니다.
type: docs
weight: 53
url: /ko/aspose.slides/ishapecollection/insertchart/
---
## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t) 메서드

새 차트를 만들고 샘플 시리즈 데이터와 설정을 초기화한 뒤, 지정된 인덱스에 shape collection에 삽입합니다.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 생성할 차트 유형. |
| x | **float** | 새 차트의 x 좌표(포인트 단위). |
| y | **float** | 새 차트의 y 좌표(포인트 단위). |
| width | **float** | 새 차트의 너비(포인트 단위). |
| height | **float** | 새 차트의 높이(포인트 단위). |
| index | **int32_t** | shape collection에 새 차트를 삽입할 0 기반 인덱스. |

### 반환값

새로 생성된 [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::InsertChart(Charts::ChartType, float, float, float, float, int32_t, bool) 메서드

새 차트를 만들고 샘플 시리즈 데이터와 설정을 초기화한 뒤, 지정된 인덱스에 shape collection에 삽입합니다.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::InsertChart(Charts::ChartType type, float x, float y, float width, float height, int32_t index, bool initWithSample)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 생성할 차트 유형. |
| x | **float** | 새 차트의 x 좌표(포인트 단위). |
| y | **float** | 새 차트의 y 좌표(포인트 단위). |
| width | **float** | 새 차트의 너비(포인트 단위). |
| height | **float** | 새 차트의 높이(포인트 단위). |
| index | **int32_t** | shape collection에 새 차트를 삽입할 0 기반 인덱스. |
| initWithSample | **bool** | 새 차트를 샘플 시리즈 데이터와 설정으로 초기화하려면 true; 시리즈 없이 최소 설정만으로 차트를 생성해 생성 속도를 높이려면 false. |

### 반환값

새로 생성된 [Charts::IChart](../../../aspose.slides.charts/ichart/).

## 또 보기

* 열거형 [ChartType](../../../aspose.slides.charts/charttype/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IChart](../../../aspose.slides.charts/ichart/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)