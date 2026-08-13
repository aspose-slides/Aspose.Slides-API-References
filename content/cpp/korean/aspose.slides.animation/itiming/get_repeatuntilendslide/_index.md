---
title: get_RepeatUntilEndSlide()
second_title: Aspose.Slides C++용 API 레퍼런스
description: 이 속성은 효과가 슬라이드가 끝날 때까지 반복되는지 여부를 지정합니다. 읽기 bool.
type: docs
weight: 131
url: /ko/aspose.slides.animation/itiming/get_repeatuntilendslide/
---
## ITiming::get_RepeatUntilEndSlide() 메서드

이 속성은 효과가 슬라이드가 끝날 때까지 반복되는지 여부를 지정합니다. 읽기 **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilEndSlide()=0
```

## 비고

```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// 첫 번째 슬라이드에 대한 효과 시퀀스를 가져옵니다
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// 주 시퀀스의 첫 번째 효과를 가져옵니다.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// 효과의 Timing/Repeat을 "슬라이드 끝까지" 로 변경합니다
effect->get_Timing()->set_RepeatUntilEndSlide(true);
```

## 참고

* 클래스 [ITiming](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)