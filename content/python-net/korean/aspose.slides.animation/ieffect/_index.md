---
title: IEffect class
second_title: Aspose.Slides for Python via .NET API 참조
description: 
type: docs
url: /ko/aspose.slides.animation/ieffect/
---
## IEffect 클래스

애니메이션 효과를 나타냅니다.

IEffect 유형은 다음 멤버를 노출합니다:

## 속성

| Property | Description |
| :- | :- |
| [`sequence`](/slides/python-net/ko/aspose.slides.animation/ieffect/sequence/) | 효과에 대한 시퀀스를 반환합니다.<br/>            읽기 전용 [`ISequence`](/slides/python-net/ko/aspose.slides.animation/isequence). |
| [`text_animation`](/slides/python-net/ko/aspose.slides.animation/ieffect/text_animation/) | 텍스트 애니메이션을 반환합니다.<br/>            읽기 전용 [`ITextAnimation`](/slides/python-net/ko/aspose.slides.animation/itextanimation). |
| [`preset_class_type`](/slides/python-net/ko/aspose.slides.animation/ieffect/preset_class_type/) | 효과의 클래스를 정의합니다.<br/>            읽기/쓰기 [`EffectPresetClassType`](/slides/python-net/ko/aspose.slides.animation/effectpresetclasstype). |
| [`type`](/slides/python-net/ko/aspose.slides.animation/ieffect/type/) | 효과의 유형을 정의합니다.<br/>            읽기/쓰기 [`EffectType`](/slides/python-net/ko/aspose.slides.animation/effecttype). |
| [`subtype`](/slides/python-net/ko/aspose.slides.animation/ieffect/subtype/) | 효과의 하위 유형을 정의합니다.<br/>            읽기/쓰기 [`EffectSubtype`](/slides/python-net/ko/aspose.slides.animation/effectsubtype). |
| [`behaviors`](/slides/python-net/ko/aspose.slides.animation/ieffect/behaviors/) | 효과에 대한 동작 컬렉션을 반환합니다.<br/>            읽기/쓰기 [`IBehaviorCollection`](/slides/python-net/ko/aspose.slides.animation/ibehaviorcollection). |
| [`timing`](/slides/python-net/ko/aspose.slides.animation/ieffect/timing/) | 효과의 타이밍 값을 정의합니다.<br/>            읽기/쓰기 [`ITiming`](/slides/python-net/ko/aspose.slides.animation/itiming). |
| [`target_shape`](/slides/python-net/ko/aspose.slides.animation/ieffect/target_shape/) | 효과의 대상 셰이프를 반환합니다.<br/>            읽기 전용 [`IShape`](/slides/python-net/ko/aspose.slides/ishape). |
| [`sound`](/slides/python-net/ko/aspose.slides.animation/ieffect/sound/) | 효과에 대한 임베디드 사운드를 정의합니다.<br/>            읽기/쓰기 [`IAudio`](/slides/python-net/ko/aspose.slides/iaudio). |
| [`stop_previous_sound`](/slides/python-net/ko/aspose.slides.animation/ieffect/stop_previous_sound/) | 이 속성은 애니메이션 효과가 이전 사운드를 중지하는지 여부를 지정합니다.<br/>            읽기/쓰기 **bool**. |
| [`after_animation_type`](/slides/python-net/ko/aspose.slides.animation/ieffect/after_animation_type/) | 효과에 대한 후속 애니메이션 유형을 정의합니다.<br/>            읽기/쓰기 [`IEffect.after_animation_type`](/slides/python-net/ko/aspose.slides.animation/ieffect/after_animation_type). |
| [`after_animation_color`](/slides/python-net/ko/aspose.slides.animation/ieffect/after_animation_color/) | 효과에 대한 후속 애니메이션 색상을 정의합니다.<br/>            읽기/쓰기 [`IColorFormat`](/slides/python-net/ko/aspose.slides/icolorformat). |
| [`animate_text_type`](/slides/python-net/ko/aspose.slides.animation/ieffect/animate_text_type/) | 효과에 대한 텍스트 애니메이션 유형을 정의합니다. <br/>            형태 텍스트를 문자별, 단어별 또는 전체를 한 번에 애니메이션할 수 있습니다.<br/>            읽기/쓰기 [`IEffect.animate_text_type`](/slides/python-net/ko/aspose.slides.animation/ieffect/animate_text_type). |
| [`delay_between_text_parts`](/slides/python-net/ko/aspose.slides.animation/ieffect/delay_between_text_parts/) | 효과가 애니메이션된 텍스트 부분(단어 또는 문자) 사이의 지연을 정의합니다.<br/>            양수 값은 효과 지속 시간의 백분율을 지정합니다.<br/>            음수 값은 지연을 초 단위로 지정합니다.<br/>            읽기/쓰기 **float**. |

### 참고
* 모듈 [`aspose.slides.animation`](/slides/python-net/ko/aspose.slides.animation)
* 라이브러리 [`Aspose.Slides`](/slides/python-net)