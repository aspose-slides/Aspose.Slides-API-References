---
title: Reorder()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 모양을 모양 컬렉션 내의 새로운 위치로 이동합니다.
type: docs
weight: 339
url: /ko/aspose.slides/shapecollection/reorder/
---
## ShapeCollection::Reorder(int32_t, System::SharedPtr\<IShape\>) 메서드

지정된 모양을 모양 컬렉션 내에서 새로운 위치로 이동합니다.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, System::SharedPtr<IShape> shape) override
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 모양이 배치될 0부터 시작하는 대상 인덱스입니다. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 컬렉션 내에서 이동할 [IShape](../../ishape/)입니다. |

## ShapeCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<IShape\>\>\&) 메서드

지정된 모양들을 모양 컬렉션 내에서 이동시키며, 지정된 인덱스부터 배치합니다.

```cpp
void Aspose::Slides::ShapeCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<IShape>> &shapes) override
```

### 인수

| 매개변수 | 타입 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 첫 번째 지정된 모양이 배치될 0부터 시작하는 대상 인덱스이며, 이후 모양들은 제공된 순서대로 따라갑니다. |
| shapes | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\>\>\& | 컬렉션 내에서 이동할 하나 이상의 [IShape](../../ishape/) 인스턴스입니다. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [IShape](../../ishape/)
* 클래스 [ShapeCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)