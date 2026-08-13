---
title: set_Rewind()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 속성은 효과가 재생이 끝난 후 되감기될지 여부를 지정합니다. bool 로 작성합니다.
type: docs
weight: 248
url: /ko/aspose.slides.animation/timing/set_rewind/
---
## Timing::set_Rewind(bool) 메서드


이 속성은 효과가 재생이 끝난 후 되감기될지 여부를 지정합니다. **bool** 로 작성합니다.

```cpp
void Aspose::Slides::Animation::Timing::set_Rewind(bool value) override
```

## 비고


```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the effects sequence for the first slide
System::SharedPtr<ISequence> effectsSequence = presentation->get_Slide(0)->get_Timeline()->get_MainSequence();

// Get the first effect of main sequence.
System::SharedPtr<IEffect> effect = effectsSequence->idx_get(0);

// Turn the effect Timing/Rewind on.
effect->get_Timing()->set_Rewind(true);
```

## 참조

* 클래스 [Timing](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)