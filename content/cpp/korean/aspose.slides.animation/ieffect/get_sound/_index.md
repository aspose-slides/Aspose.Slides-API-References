---
title: get_Sound()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 효과에 대한 삽입된 사운드를 정의했습니다. IAudio를 읽으십시오.
type: docs
weight: 170
url: /ko/aspose.slides.animation/ieffect/get_sound/
---
## IEffect::get_Sound() 메서드


효과에 대한 삽입된 사운드를 정의합니다. [IAudio](../../../aspose.slides/iaudio/)를 읽으십시오.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::Animation::IEffect::get_Sound()=0
```

## 참고



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

## 참조

* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IAudio](../../../aspose.slides/iaudio/)
* 클래스 [IEffect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)