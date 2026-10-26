---
title: IBehavior
second_title: Aspose.Slides для Java API Reference
description: Представляет базовое поведение класса эффекта.
type: docs
url: /ru/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Представляет базовое поведение класса эффекта.
## Методы

| Метод | Описание |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Представляет, являются ли анимационные поведения накопленными. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Представляет, являются ли анимационные поведения накопленными. |
| [getAdditive()](#getAdditive--) | Представляет, комбинируется ли текущее анимационное поведение с другими запущенными анимациями. |
| [setAdditive(int value)](#setAdditive-int-) | Представляет, комбинируется ли текущее анимационное поведение с другими запущенными анимациями. |
| [getProperties()](#getProperties--) | Представляет свойства поведения. |
| [getTiming()](#getTiming--) | Представляет свойства времени для поведения эффекта. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Представляет свойства времени для поведения эффекта. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Представляет, являются ли анимационные поведения накопленными. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Представляет, являются ли анимационные поведения накопленными. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Представляет, комбинируется ли текущее анимационное поведение с другими запущенными анимациями. Чтение/запись [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Возвращаемое значение:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Представляет, комбинируется ли текущее анимационное поведение с другими запущенными анимациями. Чтение/запись [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Представляет свойства поведения. Только чтение [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Возвращаемое значение:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Представляет свойства времени для поведения эффекта. Чтение/запись [ITiming](../../com.aspose.slides/itiming).

**Возвращаемое значение:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Представляет свойства времени для поведения эффекта. Чтение/запись [ITiming](../../com.aspose.slides/itiming).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |