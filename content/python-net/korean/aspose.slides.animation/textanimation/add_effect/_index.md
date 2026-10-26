---
title: add_effect method
second_title: Aspose.Slides for Python via .NET API 레퍼런스
description: 
type: docs
url: /ko/aspose.slides.animation/textanimation/add_effect/
weight: 20
---
## add_effect(self, effect_type, subtype, trigger_type) {#effecttype-effectsubtype-effecttriggertype}
현재 시퀀스의 끝에 새 효과를 추가하여 그룹 텍스트 애니메이션의 끝에 배치합니다.
            텍스트 단락 수가 이 그룹의 효과 개수와 같거나 많을 때만 유효합니다!

### 반환값

새 효과 객체 [`IEffect`](/slides/python-net/ko/aspose.slides.animation/ieffect)



```python
def add_effect(self, effect_type, subtype, trigger_type):
    ...
```


| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| effect_type | [`EffectType`](/slides/python-net/ko/aspose.slides.animation/effecttype) | 애니메이션 효과의 유형 [`EffectType`](/slides/python-net/ko/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ko/aspose.slides.animation/effectsubtype) | 애니메이션 효과의 하위 유형 [`EffectSubtype`](/slides/python-net/ko/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ko/aspose.slides.animation/effecttriggertype) | 효과의 트리거 유형 [`EffectTriggerType`](/slides/python-net/ko/aspose.slides.animation/effecttriggertype) |



### 참조
* 열거형 [`EffectSubtype`](/slides/python-net/ko/aspose.slides.animation/effectsubtype)
* 열거형 [`EffectTriggerType`](/slides/python-net/ko/aspose.slides.animation/effecttriggertype)
* 열거형 [`EffectType`](/slides/python-net/ko/aspose.slides.animation/effecttype)
* 클래스 [`IEffect`](/slides/python-net/ko/aspose.slides.animation/ieffect)
* 클래스 [`TextAnimation`](/slides/python-net/ko/aspose.slides.animation/textanimation)
* 모듈 [`aspose.slides.animation`](/slides/python-net/ko/aspose.slides.animation)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)