---
title: add_effect method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides.animation/textanimation/add_effect/
weight: 20
---
## add_effect(self, effect_type, subtype, trigger_type) {#effecttype-effectsubtype-effecttriggertype}
Добавить новый эффект в конец текущей последовательности до конца группы анимаций текста.
            Действительно только если количество абзацев текста равно или больше количества эффектов этой группы!

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
* перечисление [`EffectSubtype`](/slides/python-net/ru/aspose.slides.animation/effectsubtype)
* перечисление [`EffectTriggerType`](/slides/python-net/ru/aspose.slides.animation/effecttriggertype)
* перечисление [`EffectType`](/slides/python-net/ru/aspose.slides.animation/effecttype)
* класс [`IEffect`](/slides/python-net/ru/aspose.slides.animation/ieffect)
* класс [`TextAnimation`](/slides/python-net/ru/aspose.slides.animation/textanimation)
* модуль [`aspose.slides.animation`](/slides/python-net/ru/aspose.slides.animation)
* библиотека [`Aspose.Slides`](/slides/python-net)