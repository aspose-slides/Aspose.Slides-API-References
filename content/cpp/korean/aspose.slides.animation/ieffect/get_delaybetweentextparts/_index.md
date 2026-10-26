---
title: get_DelayBetweenTextParts()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 애니메이션 텍스트 부분(단어 또는 문자) 사이의 지연을 정의합니다. 양수 값은 효과 지속 시간의 백분율을 지정합니다. 음수 값은 지연을 초 단위로 지정합니다. float 읽기.
type: docs
weight: 300
url: /ko/aspose.slides.animation/ieffect/get_delaybetweentextparts/
---
## IEffect::get_DelayBetweenTextParts() 메서드

애니메이션 텍스트 부분(단어 또는 문자) 사이의 지연을 정의합니다. 양수 값은 효과 지속 시간의 백분율을 지정합니다. 음수 값은 지연을 초 단위로 지정합니다. 읽기 **float**.

```cpp
virtual float Aspose::Slides::Animation::IEffect::get_DelayBetweenTextParts()=0
```

## 비고



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect Animate text type to "By word"
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// Set the delay between animated text parts to 20% of effect duration.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## 관련 항목

* 클래스 [IEffect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)