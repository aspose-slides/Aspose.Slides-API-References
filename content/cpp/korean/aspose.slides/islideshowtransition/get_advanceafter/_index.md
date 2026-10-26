---
title: get_AdvanceAfter()
second_title: Aspose.Slides for C++ API 참조
description: 이 속성은 슬라이드쇼가 일정 시간 후에 다음 슬라이드로 이동하는지 여부를 지정합니다. bool을 읽습니다.
type: docs
weight: 105
url: /ko/aspose.slides/islideshowtransition/get_advanceafter/
---
## ISlideShowTransition::get_AdvanceAfter() 메서드

This attribute specifies if the slideshow will move to the next slide after a certain time. Read **bool**.

```cpp
virtual bool Aspose::Slides::ISlideShowTransition::get_AdvanceAfter()=0
```

## 비고

```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// 첫 번째 슬라이드 전환을 가져옵니다
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Advance Slide After 플래그가 설정되어 있는지 확인합니다
if (slideTransition->get_AdvanceAfter())
{
    // Advance Slide After Time 값을 가져옵니다
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## 참고

* 클래스 [ISlideShowTransition](../)
* 네임스페이스 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)