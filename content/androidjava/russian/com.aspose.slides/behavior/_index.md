---
title: Behavior
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет поведение базового класса эффекта.
type: docs
url: /ru/com.aspose.slides/behavior/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Представляет поведение базового класса эффекта.
## Методы

| Метод | Описание |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Представляет, накапливаются ли анимационные поведения. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Представляет, накапливаются ли анимационные поведения. |
| [getAdditive()](#getAdditive--) | Представляет, объединяется ли текущее анимационное поведение с другими запущенными анимациями. |
| [setAdditive(int value)](#setAdditive-int-) | Представляет, объединяется ли текущее анимационное поведение с другими запущенными анимациями. |
| [getProperties()](#getProperties--) | Представляет свойства поведения. |
| [getTiming()](#getTiming--) | Представляет свойства синхронизации для поведения эффекта. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Представляет свойства синхронизации для поведения эффекта. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращаемое значение:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```


Представляет, накапливаются ли анимационные поведения. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Возвращаемое значение:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


Представляет, накапливаются ли анимационные поведения. Чтение/запись [NullableBool](../../com.aspose.slides/nullablebool).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


Представляет, объединяется ли текущее анимационное поведение с другими запущенными анимациями. Чтение/запись [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Возвращаемое значение:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


Представляет, объединяется ли текущее анимационное поведение с другими запущенными анимациями. Чтение/запись [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```


Представляет свойства поведения. Только для чтения [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Возвращаемое значение:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Представляет свойства синхронизации для поведения эффекта. Чтение/запись [ITiming](../../com.aspose.slides/itiming).

**Возвращаемое значение:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Представляет свойства синхронизации для поведения эффекта. Чтение/запись [ITiming](../../com.aspose.slides/itiming).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |