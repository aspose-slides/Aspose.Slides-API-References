---
title: AddChart()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 차트를 만들고 샘플 시리즈 데이터와 설정으로 초기화한 다음, 도형 컬렉션의 끝에 추가합니다.
type: docs
weight: 27
url: /ko/aspose.slides/ishapecollection/addchart/
---
## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float) method

새 차트를 만들고 샘플 시리즈 데이터와 설정으로 초기화한 다음, 도형 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 추가할 차트 유형. |
| x | **float** | 새 차트의 x 좌표(포인트 단위). |
| y | **float** | 새 차트의 y 좌표(포인트 단위). |
| width | **float** | 차트의 너비(포인트 단위). |
| height | **float** | 차트의 높이(포인트 단위). |

### 반환 값

새로 생성된 [Charts::IChart](../../../aspose.slides.charts/ichart/).

## IShapeCollection::AddChart(Charts::ChartType, float, float, float, float, bool) method

새 차트를 만들고 샘플 시리즈 데이터와 설정으로 초기화한 다음, 도형 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<Charts::IChart> Aspose::Slides::IShapeCollection::AddChart(Charts::ChartType type, float x, float y, float width, float height, bool initWithSample)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [Charts::ChartType](../../../aspose.slides.charts/charttype/) | 추가할 차트 유형. |
| x | **float** | 새 차트의 x 좌표(포인트 단위). |
| y | **float** | 새 차트의 y 좌표(포인트 단위). |
| width | **float** | 차트의 너비(포인트 단위). |
| height | **float** | 차트의 높이(포인트 단위). |
| initWithSample | **bool** | True이면 새 차트를 샘플 시리즈 데이터와 설정으로 초기화합니다; false이면 시리즈가 없고 최소 설정만으로 차트를 생성하여 생성 속도를 높입니다. |

### 반환 값

새로 생성된 [Charts::IChart](../../../aspose.slides.charts/ichart/).

## 참고

* Enum [ChartType](../../../aspose.slides.charts/charttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IChart](../../../aspose.slides.charts/ichart/)
* Class [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)