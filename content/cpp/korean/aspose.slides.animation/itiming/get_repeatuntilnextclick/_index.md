---
title: get_RepeatUntilNextClick()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 속성은 효과가 다음 클릭까지 반복될지 여부를 지정합니다. 읽기 bool.
type: docs
weight: 157
url: /ko/aspose.slides.animation/itiming/get_repeatuntilnextclick/
---
## ITiming::get_RepeatUntilNextClick() 메서드


이 속성은 효과가 다음 클릭까지 반복될지 여부를 지정합니다. 읽기 **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_RepeatUntilNextClick()=0
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(path + u"demo.pptx");

// 첫 번째 슬라이드에 대한 효과 시퀀스를 가져옵니다
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slides()->idx_get(0)->get_Timeline()->get_MainSequence();

// 메인 시퀀스의 첫 번째 효과를 가져옵니다.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// 효과 Timing/Repeat을 "슬라이드 끝까지" 로 변경합니다
effect->get_Timing()->set_RepeatUntilNextClick(true);
```

## 참고

* 클래스 [ITiming](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)