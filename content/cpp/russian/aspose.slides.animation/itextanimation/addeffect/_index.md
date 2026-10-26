---
title: AddEffect()
second_title: Aspose.Slides для C++ справочник API
description: Добавьте новый эффект в конец текущей последовательности группы анимации текста. Действительно только если количество текстовых абзацев равно или превышает количество эффектов этой группы!
type: docs
weight: 53
url: /ru/aspose.slides.animation/itextanimation/addeffect/
---
## ITextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) метод

Добавьте новый эффект в конец текущей последовательности группы анимации текста. Действительно только если количество текстовых абзацев равно или больше количества эффектов этой группы!

```cpp
virtual System::SharedPtr<IEffect> Aspose::Slides::Animation::ITextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Тип анимационного эффекта [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Подтипы анимационного эффекта [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Тип триггера эффекта [EffectTriggerType](../../effecttriggertype/) |

### Возвращаемое значение

Новый объект эффекта [IEffect](../../ieffect/)

## См. также

* Перечисление [EffectType](../../effecttype/)
* Перечисление [EffectSubtype](../../effectsubtype/)
* Перечисление [EffectTriggerType](../../effecttriggertype/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [IEffect](../../ieffect/)
* Класс [ITextAnimation](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Библиотека [Aspose.Slides](../../../)