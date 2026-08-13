---
title: AddConnector()
second_title: Aspose.Slides for C++ API 참조
description: 새 커넥터 모양을 기본 템플릿 스타일로 생성하고 이를 모양 컬렉션의 끝에 추가합니다.
type: docs
weight: 378
url: /ko/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) method

기본 템플릿 스타일을 적용한 새 커넥터 모양을 생성하고 이를 모양 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 추가할 커넥터 모양의 [ShapeType](../../shapetype/). |
| x | **float** | 포인트 단위의 connector\u2019s 프레임의 x 좌표. |
| y | **float** | 포인트 단위의 connector\u2019s 프레임의 y 좌표. |
| width | **float** | 포인트 단위의 connector\u2019s 프레임의 너비. |
| height | **float** | 포인트 단위의 connector\u2019s 프레임의 높이. |

### 반환값

새로 생성된 [IConnector](../../iconnector/).

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) method

새 커넥터 모양을 생성하고 이를 모양 컬렉션의 끝에 추가하며, 선택적으로 기본 템플릿 스타일을 적용합니다.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | 생성할 커넥터 모양의 [ShapeType](../../shapetype/). |
| x | **float** | 포인트 단위의 connector\u2019s 프레임의 x 좌표. |
| y | **float** | 포인트 단위의 connector\u2019s 프레임의 y 좌표. |
| width | **float** | 포인트 단위의 connector\u2019s 프레임의 너비. |
| height | **float** | 포인트 단위의 connector\u2019s 프레임의 높이. |
| createFromTemplate | **bool** | 기본 템플릿 스타일을 적용하려면 true (비어 있지 않은 이름, 단순 스타일); 기본 속성 값으로 커넥터를 생성하려면 false. |

### 반환값

새로 생성된 [IConnector](../../iconnector/).

## 참고

* 열거형 [ShapeType](../../shapetype/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IConnector](../../iconnector/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)