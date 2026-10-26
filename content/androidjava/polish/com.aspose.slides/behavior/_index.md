---
title: Behavior
second_title: Aspose.Slides dla Androida za pośrednictwem Java API Reference
description: Reprezentuje zachowanie klasy bazowej efektu.
type: docs
url: /pl/com.aspose.slides/behavior/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Reprezentuje zachowanie klasy bazowej efektu.
## Metody

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Reprezentuje, czy zachowania animacji są kumulowane. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Reprezentuje, czy zachowania animacji są kumulowane. |
| [getAdditive()](#getAdditive--) | Reprezentuje, czy bieżące zachowanie animacji jest łączone z innymi trwającymi animacjami. |
| [setAdditive(int value)](#setAdditive-int-) | Reprezentuje, czy bieżące zachowanie animacji jest łączone z innymi trwającymi animacjami. |
| [getProperties()](#getProperties--) | Reprezentuje właściwości zachowania. |
| [getTiming()](#getTiming--) | Reprezentuje właściwości czasu dla zachowania efektu. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Reprezentuje właściwości czasu dla zachowania efektu. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

Reprezentuje, czy zachowania animacji są kumulowane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

Reprezentuje, czy zachowania animacji są kumulowane. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

Reprezentuje, czy bieżące zachowanie animacji jest łączone z innymi trwającymi animacjami. Odczyt/zapis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Zwraca:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

Reprezentuje, czy bieżące zachowanie animacji jest łączone z innymi trwającymi animacjami. Odczyt/zapis [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

Reprezentuje właściwości zachowania. Tylko do odczytu [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Zwraca:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Reprezentuje właściwości czasu dla zachowania efektu. Odczyt/zapis [ITiming](../../com.aspose.slides/itiming).

**Zwraca:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Reprezentuje właściwości czasu dla zachowania efektu. Odczyt/zapis [ITiming](../../com.aspose.slides/itiming).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |