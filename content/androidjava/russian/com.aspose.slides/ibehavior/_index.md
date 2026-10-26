---
title: IBehavior
second_title: Aspose.Slides для Android через Java API Reference
description: Представляет поведение базового класса эффекта.
type: docs
url: /ru/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Представляет поведение базового класса эффекта.
## Методы

| Метод | Описание |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Представляет, аккумулируются ли анимационные поведения. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Представляет, аккумулируются ли анимационные поведения. |
| [getAdditive()](#getAdditive--) | Представляет, комбинируется ли текущее анимационное поведение с другими запущенными анимациями. |
| [setAdditive(int value)](#setAdditive-int-) | Представляет, комбинируется ли текущее анимационное поведение с другими запущенными анимациями. |
| [getProperties()](#getProperties--) | Представляет свойства поведения. |
| [getTiming()](#getTiming--) | Представляет свойства тайминга для поведения эффекта. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Представляет свойства тайминга для поведения эффекта. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Представляет, аккумулируются ли анимационные поведения. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Представляет, аккумулируются ли анимационные поведения. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Представляет, комбинируется ли текущее анимационное поведение с другими запущенными анимациями. Чтение/запись [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Returns:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Представляет, комбинируется ли текущее анимационное поведение с другими запущенными анимациями. Чтение/запись [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Представляет свойства поведения. Только для чтения [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Returns:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Представляет свойства тайминга для поведения эффекта. Чтение/запись [ITiming](../../com.aspose.slides/itiming).

**Returns:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Представляет свойства тайминга для поведения эффекта. Чтение/запись [ITiming](../../com.aspose.slides/itiming).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |