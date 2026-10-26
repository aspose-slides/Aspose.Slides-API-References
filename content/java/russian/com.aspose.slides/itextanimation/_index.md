---
title: ITextAnimation
second_title: Aspose.Slides for Java API Reference
description: Represent text animation.
type: docs
url: /ru/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

Представляет анимацию текста.
## Методы

| Method | Description |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Добавить новый эффект в конец текущей последовательности к концу групповых анимаций текста. |
| [getBuildType()](#getBuildType--) | Список типов построения (для прим. |
| [setBuildType(int value)](#setBuildType-int-) | Список типов построения (для прим. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Связанный эффект формы с группой или без (null) Чтение/запись [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Связанный эффект формы с группой или без (null) Чтение/запись [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```


Добавить новый эффект в конец текущей последовательности к концу групповых анимаций текста. Действительно только если количество абзацев текста равно или превышает количество эффектов в этой группе!

**Параметры:**
| Parameter | Type | Description |
| --- | --- | --- |
| effectType | int | Тип анимационного эффекта [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Подтипы анимационного эффекта [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Тип триггера эффекта [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Возвращаемое значение:**
[IEffect](../../com.aspose.slides/ieffect) - Новый объект эффекта [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```


Список типов построения (для прим. Paragraph 1,2,3, All at Once) текстовой анимации. Чтение/запись \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Возвращаемое значение:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```


Список типов построения (для прим. Paragraph 1,2,3, All at Once) текстовой анимации. Чтение/запись \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**Параметры:**
| Parameter | Type | Description |
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
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |