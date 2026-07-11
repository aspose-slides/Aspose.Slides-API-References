---
title: TextAnimation
second_title: Aspose.Slides для Android через Java API
description: Представляет анимацию текста.
type: docs
url: /ru/com.aspose.slides/textanimation/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

Представляет анимацию текста.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | Добавить новый эффект в конец текущей последовательности к концу групповой анимации текста. |
| [getBuildType()](#getBuildType--) | Список типов построения (для прим. |
| [setBuildType(int value)](#setBuildType-int-) | Список типов построения (для прим. |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | Связанный эффект формы с группой или без (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | Связанный эффект формы с группой или без (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


Добавить новый эффект в конец текущей последовательности к концу групповой анимации текста. Допустимо только если количество текстовых абзацев равно или больше количества эффектов в этой группе!

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| effectType | int | Тип анимационного эффекта [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | Подтипы анимационного эффекта [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | Тип триггера эффекта [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**Возвращаемое значение:**
[IEffect](../../com.aspose.slides/ieffect) - Новый объект эффекта [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


Список типов построения (для прим. Paragraph 1,2,3, All at Once) анимации текста. Чтение/запись [BuildType](../../com.aspose.slides/buildtype).

**Возвращаемое значение:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


Список типов построения (для прим. Paragraph 1,2,3, All at Once) анимации текста. Чтение/запись [BuildType](../../com.aspose.slides/buildtype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


Связанный эффект формы с группой или без (null). Чтение/запись [IEffect](../../com.aspose.slides/ieffect).

**Возвращаемое значение:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


Связанный эффект формы с группой или без (null). Чтение/запись [IEffect](../../com.aspose.slides/ieffect).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |