---
title: ITextAnimation
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет анимацию текста.
type: docs
url: /ru/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Представляет анимацию текста.
## Методы

| Метод | Описание |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Добавить новый эффект в конец текущей последовательности групповых анимаций текста. |
| [getBuildType()](#getBuildType--) | Список типов построения (например. |
| [setBuildType(int value)](#setBuildType-int-) | Список типов построения (например. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Связанный эффект формы с группой или без (null) Чтение/запись [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Связанный эффект формы с группой или без (null) Чтение/запись [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

Добавить новый эффект в конец текущей последовательности групповых анимаций текста. Действительно только если количество абзацев текста равно или больше количества эффектов этой группы!

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| effectType | int | Тип анимационного эффекта [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Подтип анимационного эффекта [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Тип триггера эффекта [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Возвращаемое значение:**
[IEffect](../../com.aspose.slides/ieffect) - Новый объект эффекта [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

Список типов построения (например Paragraph 1,2,3, All at Once) анимации текста. Чтение/запись \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Возвращаемое значение:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

Список типов построения (например Paragraph 1,2,3, All at Once) анимации текста. Чтение/запись \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |
### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

Связанный эффект формы с группой или без (null) Чтение/запись [IEffect](../../com.aspose.slides/ieffect).

**Возвращаемое значение:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

Связанный эффект формы с группой или без (null) Чтение/запись [IEffect](../../com.aspose.slides/ieffect).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |