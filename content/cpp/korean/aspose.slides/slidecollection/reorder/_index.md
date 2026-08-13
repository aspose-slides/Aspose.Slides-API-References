---
title: Reorder()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 컬렉션에서 슬라이드를 지정된 위치로 이동합니다.
type: docs
weight: 157
url: /ko/aspose.slides/slidecollection/reorder/
---
## SlideCollection::Reorder(int32_t, System::SharedPtr\<ISlide\>) 메서드

컬렉션에서 슬라이드를 지정된 위치로 이동합니다.

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, System::SharedPtr<ISlide> slide) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 대상 인덱스. |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/)를 이동합니다. |

## SlideCollection::Reorder(int32_t, const System::ArrayPtr\<System::SharedPtr\<ISlide\>\>\&) 메서드

컬렉션에서 슬라이드를 지정된 위치로 이동합니다. [Slides](../../)는 인덱스에서 시작하여 목록에 나타나는 순서대로 배치됩니다.

```cpp
void Aspose::Slides::SlideCollection::Reorder(int32_t index, const System::ArrayPtr<System::SharedPtr<ISlide>> &slides) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 대상 인덱스. |
| slides | const [System::ArrayPtr](../../../system/arrayptr/)\<[System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\>\>\& | [Slides](../../)를 이동합니다. |

## 참고

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 타입정의 [ArrayPtr](../../../system/arrayptr/)
* 클래스 [ISlide](../../islide/)
* 클래스 [SlideCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)