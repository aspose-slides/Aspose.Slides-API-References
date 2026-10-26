---
title: get_Rewind()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 이 속성은 효과 재생이 끝났을 때 되감기 할지 여부를 지정합니다. 읽기 bool.
type: docs
weight: 313
url: /ko/aspose.slides.animation/itiming/get_rewind/
---
## ITiming::get_Rewind() 메서드


이 속성은 효과가 재생이 끝났을 때 되감기 될지 여부를 지정합니다. 읽기 **bool**.

```cpp
virtual bool Aspose::Slides::Animation::ITiming::get_Rewind()=0
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