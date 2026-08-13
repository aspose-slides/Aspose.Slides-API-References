---
title: get_Sound()
second_title: Aspose.Slides for C++ API 참조
description: 효과에 대한 내장 사운드를 정의합니다. IAudio를 읽으세요.
type: docs
weight: 170
url: /ko/aspose.slides.animation/effect/get_sound/
---
## Effect::get_Sound() 메서드

효과에 대한 내장 사운드를 정의합니다. [IAudio](../../../aspose.slides/iaudio/)를 읽으세요.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::Animation::Effect::get_Sound() override
```

## 비고

```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");
auto slide = presentation->get_Slides()->idx_get(0);

// 슬라이드에 대한 효과 시퀀스를 가져옵니다
auto effectsSequence = slide->get_Timeline()->get_MainSequence();
for (auto effect : effectsSequence)
{
    if (effect->get_Sound() == nullptr)
    {
        continue;
    }

    // 효과 사운드를 바이트 배열로 추출합니다
    System::ArrayPtr<uint8_t> audio = effect->get_Sound()->get_BinaryData();
}
```

## 참고

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudio](../../../aspose.slides/iaudio/)
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)