---
title: InsertConnector()
second_title: Aspose.Slides for C++ API 참조
description: 새 연결자 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며 기본 템플릿 스타일을 적용합니다.
type: docs
weight: 391
url: /ko/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) 메서드

새 연결자 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며 기본 템플릿 스타일을 적용합니다.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 연결자 도형을 삽입할 제로 기반 인덱스입니다. |
| shapeType | [ShapeType](../../shapetype/) | 삽입할 연결자 도형의 [ShapeType](../../shapetype/). |
| x | **float** | 포인트 단위의 연결자 프레임의 x 좌표입니다. |
| y | **float** | 포인트 단위의 연결자 프레임의 y 좌표입니다. |
| width | **float** | 포인트 단위의 연결자 프레임의 너비입니다. |
| height | **float** | 포인트 단위의 연결자 프레임의 높이입니다. |

### 반환 값

새로 생성된 [IConnector](../../iconnector/).

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) 메서드

새 연결자 도형을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입하며, 선택적으로 기본 템플릿 스타일을 적용합니다.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 연결자 도형을 삽입할 제로 기반 인덱스입니다. |
| shapeType | [ShapeType](../../shapetype/) | 삽입할 연결자 도형의 [ShapeType](../../shapetype/). |
| x | **float** | 포인트 단위의 연결자 프레임의 x 좌표입니다. |
| y | **float** | 포인트 단위의 연결자 프레임의 y 좌표입니다. |
| width | **float** | 포인트 단위의 연결자 프레임의 너비입니다. |
| height | **float** | 포인트 단위의 연결자 프레임의 높이입니다. |
| createFromTemplate | **bool** | 기본 템플릿 스타일을 적용하려면 true (이름이 비어 있지 않고 간단한 스타일); 기본 속성값으로 연결자를 생성하려면 false. |

### 반환 값

새로 생성된 [IConnector](../../iconnector/).

## 참조

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IConnector](../../iconnector/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)