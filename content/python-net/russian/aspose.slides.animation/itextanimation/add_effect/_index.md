---
title: add_effect method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides.animation/itextanimation/add_effect/
weight: 10
---
## add_effect(self, effect_type, subtype, trigger_type) {#effecttype-effectsubtype-effecttriggertype}
Добавить новый эффект в конец текущей последовательности к концу групповой анимации текста.
Только допустимо, если количество абзацев текста равно или превышает количество эффектов этой группы!

### Возвращаемое значение
Новый объект эффекта [`IEffect`](/slides/python-net/ru/aspose.slides.animation/ieffect)

```python
def add_effect(self, effect_type, subtype, trigger_type):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| effect_type | [`EffectType`](/slides/python-net/ru/aspose.slides.animation/effecttype) | Тип анимационного эффекта [`EffectType`](/slides/python-net/ru/aspose.slides.animation/effecttype) |
| subtype | [`EffectSubtype`](/slides/python-net/ru/aspose.slides.animation/effectsubtype) | Подтипы анимационного эффекта [`EffectSubtype`](/slides/python-net/ru/aspose.slides.animation/effectsubtype) |
| trigger_type | [`EffectTriggerType`](/slides/python-net/ru/aspose.slides.animation/effecttriggertype) | Тип триггера эффекта [`EffectTriggerType`](/slides/python-net/ru/aspose.slides.animation/effecttriggertype) |

### См. также
* enumeration [`EffectSubtype`](/slides/python-net/ru/aspose.slides.animation/effectsubtype)
* enumeration [`EffectTriggerType`](/slides/python-net/ru/aspose.slides.animation/effecttriggertype)
* enumeration [`EffectType`](/slides/python-net/ru/aspose.slides.animation/effecttype)
* class [`IEffect`](/slides/python-net/ru/aspose.slides.animation/ieffect)
* class [`ITextAnimation`](/slides/python-net/ru/aspose.slides.animation/itextanimation)
* module [`aspose.slides.animation`](/slides/python-net/ru/aspose.slides.animation)
* library [`Aspose.Slides`](/slides/python-net)