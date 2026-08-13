---
title: AddClone()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 도형의 복사본을 생성하고 도형 컬렉션의 끝에 추가합니다.
type: docs
weight: 495
url: /ko/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

지정된 도형의 복사본을 생성하고 도형 컬렉션의 끝에 추가합니다.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 복제할 도형. |
| x | **float** | 복제된 도형\\u2019s 프레임의 x 좌표(포인트 단위). |
| y | **float** | 복제된 도형\\u2019s 프레임의 y 좌표(포인트 단위). |
| width | **float** | 복제된 도형\\u2019s 프레임의 너비(포인트 단위). |
| height | **float** | 복제된 도형\\u2019s 프레임의 높이(포인트 단위). |

### 반환 값

새로 생성된 [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method

지정된 도형의 복사본을 생성하고 도형 컬렉션의 끝에 추가합니다. 새 도형은 *sourceShape* 의 너비와 높이를 유지합니다.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 복제할 [IShape](../../ishape/). |
| x | **float** | 복제된 도형\\u2019s 프레임의 x 좌표(포인트 단위). |
| y | **float** | 복제된 도형\\u2019s 프레임의 y 좌표(포인트 단위). |

### 반환 값

새로 생성된 [IShape](../../ishape/).

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) method

지정된 도형의 복사본을 생성하고 도형 컬렉션의 끝에 추가합니다. 복제된 도형은 원본\\u2019s 위치와 크기를 유지합니다.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 복제할 [IShape](../../ishape/). |

### 반환 값

새로 생성된 [IShape](../../ishape/).

## 연관 항목

* 타입 정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IShape](../../ishape/)
* 클래스 [IShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)