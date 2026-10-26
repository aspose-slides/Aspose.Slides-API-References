---
title: AddEffect()
second_title: Aspose.Slides for C++ API 레퍼런스
description: 현재 시퀀스 끝에 새로운 효과를 추가하여 그룹 텍스트 애니메이션의 끝에 배치합니다. 텍스트 단락 수가 이 그룹의 효과 개수와 같거나 많을 경우에만 유효합니다!
type: docs
weight: 53
url: /ko/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) 메서드

현재 시퀀스 끝에 새로운 효과를 추가하여 그룹 텍스트 애니메이션의 끝에 배치합니다. 텍스트 단락 수가 이 그룹의 효과 개수와 같거나 많을 경우에만 유효합니다!

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### 인수

| 매개변수 | 형식 | 설명 |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | 애니메이션 효과의 유형 [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | 애니메이션 효과의 하위 유형 [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | 효과의 트리거 유형 [EffectTriggerType](../../effecttriggertype/) |

### 반환 값

새 효과 객체 [IEffect](../../ieffect/)

## 참조

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* 클래스 [IEffect](../../ieffect/)
* 클래스 [TextAnimation](../)
* 네임스페이스 [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)