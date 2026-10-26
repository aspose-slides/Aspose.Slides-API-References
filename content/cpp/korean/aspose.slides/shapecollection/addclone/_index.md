---
title: AddClone()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 도형의 복사본을 생성하고 도형 컬렉션의 끝에 추가합니다.
type: docs
weight: 547
url: /ko/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) 메서드

지정된 도형의 복사본을 생성하고 도형 컬렉션의 끝에 추가합니다.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 복제할 도형입니다. |
| x | **float** | 새 도형 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 도형 프레임의 y 좌표(포인트 단위)입니다. |
| width | **float** | 새 도형 프레임의 너비(포인트 단위)입니다. |
| height | **float** | 새 도형 프레임의 높이(포인트 단위)입니다. |

### 반환 값

새로 생성된 [IShape](../../ishape/)입니다.

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) 메서드

지정된 도형의 복사본을 생성하고 도형 컬렉션의 끝에 추가합니다. 새 도형은 *sourceShape*의 너비와 높이를 유지합니다.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 복제할 도형입니다. |
| x | **float** | 새 도형 프레임의 x 좌표(포인트 단위)입니다. |
| y | **float** | 새 도형 프레임의 y 좌표(포인트 단위)입니다. |

### 반환 값

새로 생성된 [IShape](../../ishape/)입니다.

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) 메서드

지정된 도형의 복사본을 생성하고 도형 컬렉션의 끝에 추가합니다. 복제된 도형은 원본의 위치와 크기를 유지합니다.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### 인수

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 복제할 [IShape](../../ishape/)입니다. |

### 반환 값

새로 생성된 [IShape](../../ishape/)입니다.

## 또한 보기

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IShape](../../ishape/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)