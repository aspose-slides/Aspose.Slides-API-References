---
title: set_DelayBetweenTextParts()
second_title: Aspose.Slides for C++ API 참조
description: 애니메이션 텍스트 파트(단어나 문자) 사이의 지연을 정의합니다. 양수 값은 효과 지속 시간의 백분율을 지정합니다. 음수 값은 초 단위 지연을 지정합니다. float 형식으로 작성합니다.
type: docs
weight: 313
url: /ko/aspose.slides.animation/effect/set_delaybetweentextparts/
---
## Effect::set_DelayBetweenTextParts(float) 메서드

애니메이션 텍스트 파트(단어나 문자) 사이의 지연을 정의합니다. 양수 값은 효과 지속 시간의 백분율을 지정합니다. 음수 값은 초 단위 지연을 지정합니다. **float** 형식으로 작성합니다.

```cpp
void Aspose::Slides::Animation::Effect::set_DelayBetweenTextParts(float value) override
```

## 비고



```cpp
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 첫 슬라이드의 첫 번째 효과를 가져옵니다.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 효과 Animate 텍스트 유형을 "By word"(단어별)로 변경합니다.
firstSlideEffect->set_AnimateTextType(AnimateTextType::ByWord);

// 애니메이션 텍스트 파트 사이의 지연을 효과 지속 시간의 20%로 설정합니다.
firstSlideEffect->set_DelayBetweenTextParts(20.0f);
```

## 참조

* 클래스 [Effect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)