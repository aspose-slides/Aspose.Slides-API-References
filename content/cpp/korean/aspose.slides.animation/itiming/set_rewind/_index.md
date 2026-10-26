---
title: set_Rewind()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 속성은 효과가 재생이 끝났을 때 되감기될지를 지정합니다. bool를 씁니다.
type: docs
weight: 326
url: /ko/aspose.slides.animation/itiming/set_rewind/
---
## ITiming::set_Rewind(bool) 메서드


이 속성은 효과가 재생이 끝났을 때 되감기될지를 지정합니다. **bool**를 씁니다.

```cpp
virtual void Aspose::Slides::Animation::ITiming::set_Rewind(bool value)=0
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

* 클래스 [ITiming](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)