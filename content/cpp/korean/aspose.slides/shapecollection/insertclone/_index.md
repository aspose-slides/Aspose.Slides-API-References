---
title: InsertClone()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 도형의 복사본을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다.
type: docs
weight: 560
url: /ko/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) 메서드

지정된 도형의 복사본을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 복제된 도형을 삽입할 0 기반 인덱스입니다. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 복제할 [IShape](../../ishape/)입니다. |
| x | **float** | 복제된 도형\\u2019s 프레임의 x 좌표이며, 단위는 포인트입니다. |
| y | **float** | 복제된 도형\\u2019s 프레임의 y 좌표이며, 단위는 포인트입니다. |
| width | **float** | 복제된 도형\\u2019s 프레임의 너비이며, 단위는 포인트입니다. |
| height | **float** | 복제된 도형\\u2019s 프레임의 높이며, 단위는 포인트입니다. |

### 반환 값

새로 생성된 [IShape](../../ishape/)입니다.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) 메서드

지정된 도형의 복사본을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 새 도형은 *sourceShape* 의 너비와 높이를 유지합니다.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 복제된 도형을 삽입할 0 기반 인덱스입니다. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 복제할 [IShape](../../ishape/)입니다. |
| x | **float** | 복제된 도형\\u2019s 프레임의 x 좌표이며, 단위는 포인트입니다. |
| y | **float** | 복제된 도형\\u2019s 프레임의 y 좌표이며, 단위는 포인트입니다. |

### 반환 값

새로 생성된 [IShape](../../ishape/)입니다.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) 메서드

지정된 도형의 복사본을 만들고 지정된 인덱스에 도형 컬렉션에 삽입합니다. 복제된 도형은 원본\\u2019s 위치와 크기를 유지합니다.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 복제된 도형을 삽입할 0 기반 인덱스입니다. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 복제할 [IShape](../../ishape/)입니다. |

### 반환 값

새로 생성된 [IShape](../../ishape/)입니다.

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IShape](../../ishape/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)