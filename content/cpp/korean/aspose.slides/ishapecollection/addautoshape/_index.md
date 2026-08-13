---
title: AddAutoShape()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 기본 서식을 가진 새로운 자동 도형을 생성하고 이를 도형 컬렉션의 끝에 추가합니다.
type: docs
weight: 313
url: /ko/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) 메서드

기본 서식을 가진 새로운 자동 도형을 생성하고 이를 도형 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 추가할 자동 도형의 [ShapeType](../../shapetype/)입니다. |
| x | **float** | 도형 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 도형 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 도형 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 도형 프레임의 높이(포인트 단위)입니다. |

### 반환 값

새로 생성된 [IAutoShape](../../iautoshape/).

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) 메서드

새로운 자동 도형을 생성하고 이를 도형 컬렉션의 끝에 추가합니다. 선택적으로 기본 템플릿 서식으로 초기화할 수 있습니다.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### 매개변수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 추가할 자동 도형의 [ShapeType](../../shapetype/)입니다. |
| x | **float** | 도형 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 도형 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 도형 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 도형 프레임의 높이(포인트 단위)입니다. |
| createFromTemplate | **bool** | 새 도형에 기본 템플릿 스타일(단순 스타일, 가운데 정렬 텍스트, 비어 있지 않은 이름)을 적용하려면 true; 모든 속성을 기본값으로 설정하여 도형을 만들려면 false. |

### 반환 값

새로 생성된 [IAutoShape](../../iautoshape/).

## 관련 항목

* 열거형 [ShapeType](../../shapetype/)
* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAutoShape](../../iautoshape/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)