---
title: GetByType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 지정된 유형의 첫 번째 레이아웃 슬라이드를 반환합니다.
type: docs
weight: 14
url: /ko/aspose.slides/ilayoutslidecollection/getbytype/
---
## ILayoutSlideCollection::GetByType(SlideLayoutType) 메서드

Returns the first layout slide of specified type.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::ILayoutSlideCollection::GetByType(SlideLayoutType type)=0
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| type | [SlideLayoutType](../../slidelayouttype/) | 찾을 레이아웃 슬라이드의 유형. |

### 반환 값

[ILayoutSlide](../../ilayoutslide/) 지정된 유형과 함께 반환되며, 레이아웃이 없으면 null을 반환합니다.

## 관련 항목

* 열거형 [SlideLayoutType](../../slidelayouttype/)
* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [ILayoutSlide](../../ilayoutslide/)
* 클래스 [ILayoutSlideCollection](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)