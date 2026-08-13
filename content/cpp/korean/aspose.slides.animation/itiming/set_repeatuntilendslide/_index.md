---
title: set_RepeatUntilEndSlide()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 속성은 효과가 슬라이드가 끝날 때까지 반복되는지를 지정합니다. bool 형식으로 작성합니다.
type: docs
weight: 144
url: /ko/aspose.slides.animation/itiming/set_repeatuntilendslide/
---
## ITTiming::set_RepeatUntilEndSlide(bool) 메서드


이 속성은 효과가 슬라이드가 끝날 때까지 반복되는지를 지정합니다. 작성 형식은 **bool**입니다.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_RepeatUntilEndSlide(bool value)=0
```

## 참고



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// 첫 번째 슬라이드의 효과 시퀀스를 가져옵니다
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// 메인 시퀀스의 첫 번째 효과를 가져옵니다.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// 효과 타이밍/반복을 "슬라이드 끝까지" 로 변경합니다
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## 관련 항목

* 클래스 [ITiming](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)