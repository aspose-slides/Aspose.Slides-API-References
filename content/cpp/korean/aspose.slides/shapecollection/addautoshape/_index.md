---
title: AddAutoShape()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 기본 서식이 적용된 새 자동 도형을 생성하고 도형 컬렉션의 끝에 추가합니다.
type: docs
weight: 352
url: /ko/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) 메서드

기본 서식이 적용된 새로운 자동 도형을 생성하고 도형 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 추가할 자동 도형의 [ShapeType](../../shapetype/). |
| x | **float** | 도형 프레임의 x 좌표(포인트 단위). |
| y | **float** | 도형 프레임의 y 좌표(포인트 단위). |
| width | **float** | 도형 프레임의 너비(포인트 단위). |
| height | **float** | 도형 프레임의 높이(포인트 단위). |

### 반환 값

새로 만든 [IAutoShape](../../iautoshape/).

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) 메서드

새로운 자동 도형을 생성하고 도형 컬렉션의 끝에 추가합니다. 옵션으로 기본 템플릿 서식을 적용할 수 있습니다.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 추가할 자동 도형의 [ShapeType](../../shapetype/). |
| x | **float** | 도형 프레임의 x 좌표(포인트 단위). |
| y | **float** | 도형 프레임의 y 좌표(포인트 단위). |
| width | **float** | 도형 프레임의 너비(포인트 단위). |
| height | **float** | 도형 프레임의 높이(포인트 단위). |
| createFromTemplate | **bool** | true이면 새 도형에 기본 템플릿 스타일(단순 스타일, 중앙 정렬 텍스트, 비어 있지 않은 이름)을 적용하고, false이면 모든 속성을 기본값으로 설정하여 도형을 생성합니다. |

### 반환 값

새로 만든 [IAutoShape](../../iautoshape/).

## 또 보기

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)