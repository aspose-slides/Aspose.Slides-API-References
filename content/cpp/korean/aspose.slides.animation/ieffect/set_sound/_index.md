---
title: set_Sound()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 효과에 대한 임베디드 사운드를 정의합니다. IAudio를 씁니다.
type: docs
weight: 183
url: /ko/aspose.slides.animation/ieffect/set_sound/
---
## IEffect::set_Sound(System::SharedPtr\<IAudio\>) 메서드

효과에 대한 임베디드 사운드를 정의합니다. [IAudio](../../../aspose.slides/iaudio/)를 씁니다.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_Sound(System::SharedPtr<IAudio> value)=0
```

## 비고

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// 슬라이드에 대한 효과 시퀀스를 가져옵니다.
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // 효과 사운드를 바이트 배열로 추출합니다.
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## 참조

* 타입정의 [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAudio](../../../aspose.slides/iaudio/)
* 클래스 [IEffect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)