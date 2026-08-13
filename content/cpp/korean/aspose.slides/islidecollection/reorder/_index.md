---
title: Reorder()
second_title: Aspose.Slides for C++ API 참조
description: 컬렉션에서 슬라이드를 지정된 위치로 이동합니다.
type: docs
weight: 105
url: /ko/aspose.slides/islidecollection/reorder/
---
## ISlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) 메서드

컬렉션에서 슬라이드를 지정된 위치로 이동합니다.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 대상 인덱스. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) 이동할. |

## ISlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) 메서드

컬렉션에서 슬라이드를 지정된 위치로 이동합니다. [Slides](../../)는 인덱스부터 목록에 표시된 순서대로 배치됩니다.

```cpp
virtual void Aspose::Slides::ISlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 대상 인덱스. |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../) 이동할. |

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ISlide](../../islide/)
* 클래스 [ISlideCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)