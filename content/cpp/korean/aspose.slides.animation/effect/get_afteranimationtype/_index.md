---
title: get_AfterAnimationType()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 효과에 대한 사후 애니메이션 유형을 정의합니다. AfterAnimationType을 읽어보세요.
type: docs
weight: 222
url: /ko/aspose.slides.animation/effect/get_afteranimationtype/
---
## Effect::get_AfterAnimationType() 메서드


효과에 대한 사후 애니메이션 유형을 정의합니다. [AfterAnimationType](../../afteranimationtype/)를 읽어보세요.

```cpp
Aspose::Slides::Animation::AfterAnimationType Aspose::Slides::Animation::Effect::get_AfterAnimationType() override
```

## 비고



```cpp
auto presentation = System::MakeObject<Presentation>(u"demo.pptx");

// 첫 번째 슬라이드의 첫 번째 효과를 가져옵니다.
System::SharedPtr<IEffect> firstSlideEffect = presentation->get_Slide(0)->get_Timeline()->get_MainSequenceEffect(0);

// 효과의 사후 애니메이션을 "다음 마우스 클릭 시 숨기기"로 변경합니다.
firstSlideEffect->set_AfterAnimationType(AfterAnimationType::HideOnNextMouseClick);
```

## 참고

* Enum [AfterAnimationType](../../afteranimationtype/)
* Class [Effect](../)
* Namespace [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)