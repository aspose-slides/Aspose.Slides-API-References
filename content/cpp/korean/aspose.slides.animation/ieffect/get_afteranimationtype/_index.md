---
title: get_AfterAnimationType()
second_title: C++용 Aspose.Slides API 레퍼런스
description: 효과에 대한 이후 애니메이션 유형을 정의합니다. AfterAnimationType을 읽으십시오.
type: docs
weight: 222
url: /ko/aspose.slides.animation/ieffect/get_afteranimationtype/
---
## IEffect::get_AfterAnimationType() 메서드


효과에 대한 이후 애니메이션 유형을 정의합니다. [AfterAnimationType](../../afteranimationtype/).

```cpp
virtual Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::IEffect::get_AfterAnimationType()=0
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// Get the first effect of the first slide.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// Change the effect After animation to "Hide on Next Mouse Click"
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## 참조

* 열거형 [AfterAnimationType](../../afteranimationtype/)
* 클래스 [IEffect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)