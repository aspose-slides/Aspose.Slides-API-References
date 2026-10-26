---
title: InsertAutoShape()
second_title: Aspose.Slides for C++ API 참조
description: 새 자동 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며 기본 템플릿 서식을 적용합니다.
type: docs
weight: 378
url: /ko/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) method

새 자동 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며 기본 템플릿 서식을 적용합니다.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 새 자동 도형을 삽입할 0 기반 인덱스입니다. |
| shapeType | [ShapeType](../../shapetype/) | 삽입할 자동 도형의 [ShapeType](../../shapetype/)입니다. |
| x | **float** | 도형 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 도형 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 도형 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 도형 프레임의 높이(포인트 단위)입니다. |

### 반환값

새로 생성된 [IAutoShape](../../iautoshape/).

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) method

새 자동 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며, 선택적으로 기본 템플릿 스타일을 적용하여 초기화합니다.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 자동 도형을 삽입할 0 기반 인덱스입니다. |
| shapeType | [ShapeType](../../shapetype/) | 삽입할 자동 도형의 [ShapeType](../../shapetype/)입니다. |
| x | **float** | 도형 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 도형 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 도형 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 도형 프레임의 높이(포인트 단위)입니다. |
| createFromTemplate | **bool** | true이면 기본 템플릿 스타일(비어 있지 않은 이름, 단순 스타일, 가운데 정렬 텍스트 포함)을 적용합니다; false이면 모든 속성을 기본값으로 설정하여 도형을 생성합니다. |

### 반환값

새로 생성된 [IAutoShape](../../iautoshape/).

## 참조

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)