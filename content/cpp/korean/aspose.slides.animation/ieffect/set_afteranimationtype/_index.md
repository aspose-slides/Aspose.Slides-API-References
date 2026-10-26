---
title: set_AfterAnimationType()
second_title: Aspose.Slides for C++ API 참조
description: 효과에 대한 애프터 애니메이션 유형을 정의합니다. AfterAnimationType을 작성하십시오.
type: docs
weight: 235
url: /ko/aspose.slides.animation/ieffect/set_afteranimationtype/
---
## IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType) 메서드


효과에 대한 애프터 애니메이션 유형을 정의합니다. [AfterAnimationType](../../afteranimationtype/)를 작성하십시오.

```cpp
virtual void Aspose::Slides::Animation::IEffect::set_AfterAnimationType(Aspose::Slides::Animation::AfterAnimationType value)=0
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 효과 애프터 애니메이션을 "다음 마우스 클릭 시 숨기기"로 변경합니다.
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## 참고

* 열거형 [AfterAnimationType](../../afteranimationtype/)
* 클래스 [IEffect](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* 라이브러리 [Aspose.Slides](../../../)