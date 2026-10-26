---
title: set_AdvanceAfter()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 속성은 슬라이드쇼가 일정 시간 후에 다음 슬라이드로 이동할지 여부를 지정합니다. bool 형식으로 작성합니다.
type: docs
weight: 118
url: /ko/aspose.slides.slideshow/slideshowtransition/set_advanceafter/
---
## SlideShowTransition::set_AdvanceAfter(bool) 메서드


이 속성은 슬라이드쇼가 일정 시간 후에 다음 슬라이드로 이동할지 여부를 지정합니다. **bool** 형식으로 작성합니다.

```cpp
void Aspose::Slides::SlideShow::SlideShowTransition::set_AdvanceAfter(bool value) override
```

## 비고



```cpp
auto pres = System::MakeObject<Presentation>(u"demo.pptx");
// 첫 번째 슬라이드 전환을 가져옵니다
auto slideTransition = pres->get_Slides()->idx_get(0)->get_SlideShowTransition();
// Advance Slide After 플래그가 설정되어 있는지 확인합니다
if (slideTransition->get_AdvanceAfter())
{
    // Advance Slide After 시간 값을 가져옵니다
    uint32_t advanceAfterTime = slideTransition->get_AdvanceAfterTime();
}
```

## 참조

* 클래스 [SlideShowTransition](../)
* 네임스페이스 [Aspose::Slides::SlideShow](../../)
* 라이브러리 [Aspose.Slides](../../../)