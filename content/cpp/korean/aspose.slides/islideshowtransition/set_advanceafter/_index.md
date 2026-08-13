---
title: set_AdvanceAfter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 속성은 슬라이드쇼가 일정 시간 후에 다음 슬라이드로 이동할지 여부를 지정합니다. bool 형식으로 작성합니다.
type: docs
weight: 118
url: /ko/aspose.slides/islideshowtransition/set_advanceafter/
---
## ISlideShowTransition::set_AdvanceAfter(bool) 메서드


이 속성은 슬라이드쇼가 특정 시간 후에 다음 슬라이드로 이동할지 여부를 지정합니다. **bool** 형식으로 작성합니다.

```cpp
virtual void Aspose::Slides::ISlideShowTransition::set_AdvanceAfter(bool value)=0
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// 첫 번째 슬라이드 전환 가져오기
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Advance Slide After 플래그가 체크되었는지 확인
if (slideTransition->get_AdvanceAfter())
{
    // Advance Slide After 시간 값 가져오기
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## 또한 보기

* 클래스 [ISlideShowTransition](../)
* 네임스페이스 [Aspose::Slides](../../)
* 라이브러리 [Aspose.Slides](../../../)