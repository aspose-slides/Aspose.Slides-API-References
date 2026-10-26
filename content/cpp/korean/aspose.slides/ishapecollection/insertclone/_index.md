---
title: InsertClone()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 도형의 복사본을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다.
type: docs
weight: 508
url: /ko/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) 메서드

지정된 도형의 복사본을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 복제된 도형을 삽입할 0 기반 인덱스입니다. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 복제할 [IShape](../../ishape/)입니다. |
| x | **float** | 복제된 도형 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 복제된 도형 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 복제된 도형 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 복제된 도형 프레임의 높이(포인트 단위)입니다. |

### 반환값

새로 생성된 [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) 메서드

지정된 도형의 복사본을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 새 도형은 *sourceShape* 의 너비와 높이를 유지합니다.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 복제된 도형을 삽입할 0 기반 인덱스입니다. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 복제할 [IShape](../../ishape/)입니다. |
| x | **float** | 복제된 도형 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 복제된 도형 프레임의 y 좌표(포인트 단위)입니다. |

### 반환값

새로 생성된 [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) 메서드

지정된 도형의 복사본을 생성하고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 복제된 도형은 원본의 위치와 크기를 유지합니다.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 복제된 도형을 삽입할 0 기반 인덱스입니다. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 복제할 [IShape](../../ishape/)입니다. |

### 반환값

새로 생성된 [IShape](../../ishape/).

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IShape](../../ishape/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)