---
title: InsertClone()
second_title: Aspose.Slides for C++ API 참조
description: 지정된 레이아웃 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다.
type: docs
weight: 14
url: /ko/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) 메서드

지정된 레이아웃 슬라이드의 복사본을 컬렉션의 지정된 위치에 삽입합니다.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 새 슬라이드의 인덱스. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) 복제할 대상. |

### 반환 값

삽입된 슬라이드.

## 비고

새 레이아웃은 이 레이아웃 슬라이드 컬렉션의 부모 마스터 슬라이드와 연결됩니다. 따라서 PowerPoint의 "Use Destination Theme" 옵션을 사용한 복사/붙여넣기와 동일합니다.

## 참조

* typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [ILayoutSlide](../../ilayoutslide/)
* 클래스 [MasterLayoutSlideCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)