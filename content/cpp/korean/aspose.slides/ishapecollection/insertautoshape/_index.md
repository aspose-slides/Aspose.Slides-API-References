---
title: InsertAutoShape()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 새 자동 도형을 생성하고 지정된 인덱스에 삽입하여 기본 템플릿 서식을 적용합니다.
type: docs
weight: 339
url: /ko/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) 메서드


새 자동 도형을 생성하고 지정된 인덱스에 삽입하여 기본 템플릿 서식을 적용합니다.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 새 자동 도형을 삽입할 0 기반 인덱스. |
| shapeType | [ShapeType](../../shapetype/) | 삽입할 자동 도형의 [ShapeType](../../shapetype/). |
| x | **float** | 도형 프레임의 x좌표(포인트 단위). |
| y | **float** | 도형 프레임의 y좌표(포인트 단위). |
| width | **float** | 도형 프레임의 너비(포인트 단위). |
| height | **float** | 도형 프레임의 높이(포인트 단위). |

### 반환값

새로 생성된 [IAutoShape](../../iautoshape/).

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) 메서드


새 자동 도형을 생성하고 지정된 인덱스에 삽입합니다. 옵션으로 기본 템플릿 스타일을 초기화할 수 있습니다.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 새 자동 도형을 삽입할 0 기반 인덱스. |
| shapeType | [ShapeType](../../shapetype/) | 삽입할 자동 도형의 [ShapeType](../../shapetype/). |
| x | **float** | 도형 프레임의 x좌표(포인트 단위). |
| y | **float** | 도형 프레임의 y좌표(포인트 단위). |
| width | **float** | 도형 프레임의 너비(포인트 단위). |
| height | **float** | 도형 프레임의 높이(포인트 단위). |
| createFromTemplate | **bool** | true이면 기본 템플릿 스타일을 적용합니다(비어 있지 않은 이름, 간단한 스타일, 가운데 정렬 텍스트 포함). false이면 모든 속성을 기본값으로 설정하여 도형을 생성합니다. |

### 반환값

새로 생성된 [IAutoShape](../../iautoshape/).

## 관련 항목

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)