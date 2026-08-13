---
title: InsertConnector()
second_title: Aspose.Slides for C++ API 참조
description: 새 연결자 모양을 생성하고 지정된 인덱스에 삽입하여 모양 컬렉션에 추가하며 기본 템플릿 스타일을 적용합니다.
type: docs
weight: 430
url: /ko/aspose.slides/shapecollection/insertconnector/
---
## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) method


새 연결자 모양을 만들고 지정된 인덱스에 삽입하여 모양 컬렉션에 추가하며 기본 템플릿 스타일을 적용합니다.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 연결자 모양을 삽입할 0부터 시작하는 인덱스입니다. |
| shapeType | [ShapeType](../../shapetype/) | 삽입할 연결자 모양의 [ShapeType](../../shapetype/)입니다. |
| x | **float** | 포인트 단위의 연결자 프레임의 x 좌표입니다. |
| y | **float** | 포인트 단위의 연결자 프레임의 y 좌표입니다. |
| width | **float** | 포인트 단위의 연결자 프레임의 너비입니다. |
| height | **float** | 포인트 단위의 연결자 프레임의 높이입니다. |

### 반환값

새로 생성된 [IConnector](../../iconnector/)입니다.

## ShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) method


새 연결자 모양을 만들고 지정된 인덱스에 삽입하여 모양 컬렉션에 추가하며, 선택적으로 기본 템플릿 스타일을 적용합니다.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | 연결자 모양을 삽입할 0부터 시작하는 인덱스입니다. |
| shapeType | [ShapeType](../../shapetype/) | 삽입할 연결자 모양의 [ShapeType](../../shapetype/)입니다. |
| x | **float** | 포인트 단위의 연결자 프레임의 x 좌표입니다. |
| y | **float** | 포인트 단위의 연결자 프레임의 y 좌표입니다. |
| width | **float** | 포인트 단위의 연결자 프레임의 너비입니다. |
| height | **float** | 포인트 단위의 연결자 프레임의 높이입니다. |
| createFromTemplate | **bool** | true이면 기본 템플릿 스타일(비어 있지 않은 이름, 간단한 스타일)을 적용하고, false이면 기본 속성 값으로 연결자를 생성합니다. |

### 반환값

새로 생성된 [IConnector](../../iconnector/)입니다.

## 또 보기

* 열거형 [ShapeType](../../shapetype/)
* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IConnector](../../iconnector/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)