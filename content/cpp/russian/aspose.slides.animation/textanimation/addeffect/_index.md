---
title: AddEffect()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет новый эффект в конец текущей последовательности группы анимаций текста. Действительно только если количество абзацев текста равно или больше количества эффектов в этой группе!
type: docs
weight: 53
url: /ru/aspose.slides.animation/textanimation/addeffect/
---
## TextAnimation::AddEffect(EffectType, EffectSubtype, EffectTriggerType) метод

Добавляет новый эффект в конец текущей последовательности группы анимаций текста. Действительно только если количество абзацев текста равно или больше количества эффектов в этой группе!

```cpp
System::SharedPtr<IEffect> Aspose::Slides::Animation::TextAnimation::AddEffect(EffectType effectType, EffectSubtype subtype, EffectTriggerType triggerType) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| effectType | [EffectType](../../effecttype/) | Тип анимационного эффекта [EffectType](../../effecttype/) |
| subtype | [EffectSubtype](../../effectsubtype/) | Подтипы анимационного эффекта [EffectSubtype](../../effectsubtype/) |
| triggerType | [EffectTriggerType](../../effecttriggertype/) | Тип триггера эффекта [EffectTriggerType](../../effecttriggertype/) |

### Возвращаемое значение

Новый объект эффекта [IEffect](../../ieffect/)

## Смотрите также

* Enum [EffectType](../../effecttype/)
* Enum [EffectSubtype](../../effectsubtype/)
* Enum [EffectTriggerType](../../effecttriggertype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IEffect](../../ieffect/)
* Класс [TextAnimation](../)
* Пространство имён [Aspose::Slides::Animation](../../)
* Library [Aspose.Slides](../../../)