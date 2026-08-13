---
title: RemoveAt()
second_title: C++용 Aspose.Slides API 참조
description: 컬렉션에서 지정된 인덱스에 있는 요소를 제거합니다.
type: docs
weight: 53
url: /ko/aspose.slides/masterlayoutslidecollection/removeat/
---
## MasterLayoutSlideCollection::RemoveAt(int32_t) 메서드


지정된 인덱스의 컬렉션에서 요소를 제거합니다.

```cpp
void Aspose::Slides::MasterLayoutSlideCollection::RemoveAt(int32_t index) override
```


### Arguments

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| index | **int32_t** | 제거할 요소의 0부터 시작하는 인덱스. |
## 비고



1) PptxEditException이 발생하는 것을 방지하려면 먼저 레이아웃의 HasDependingSlides 속성을 확인하십시오. 2) 코드를 단순화하기 위해 [ILayoutSlide::Remove](../../ilayoutslide/remove/) 메서드를 사용할 수도 있습니다. 
## 참고

* 클래스 [MasterLayoutSlideCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)