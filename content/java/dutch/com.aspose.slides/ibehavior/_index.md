---
title: IBehavior
second_title: Aspose.Slides for Java API Reference
description: Geeft het basisgedrag van een effect weer.
type: docs
url: /nl/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Geeft het basisgedrag van een effect weer.
## Methoden

| Method | Description |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Geeft aan of animatiegedrag wordt geaccumuleerd. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Geeft aan of animatiegedrag wordt geaccumuleerd. |
| [getAdditive()](#getAdditive--) | Geeft aan of het huidige animatiegedrag wordt gecombineerd met andere lopende animaties. |
| [setAdditive(int value)](#setAdditive-int-) | Geeft aan of het huidige animatiegedrag wordt gecombineerd met andere lopende animaties. |
| [getProperties()](#getProperties--) | Geeft eigenschappen van het gedrag weer. |
| [getTiming()](#getTiming--) | Geeft timing-eigenschappen voor het effectgedrag weer. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Geeft timing-eigenschappen voor het effectgedrag weer. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Geeft aan of animatiegedrag wordt geaccumuleerd. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Geeft aan of animatiegedrag wordt geaccumuleerd. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Geeft aan of het huidige animatiegedrag wordt gecombineerd met andere lopende animaties. Lezen/Schrijven [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Retour:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Geeft aan of het huidige animatiegedrag wordt gecombineerd met andere lopende animaties. Lezen/Schrijven [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Geeft eigenschappen van het gedrag weer. Alleen-lezen [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Retour:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Geeft timing-eigenschappen voor het effectgedrag weer. Lezen/Schrijven [ITiming](../../com.aspose.slides/itiming).

**Retour:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Geeft timing-eigenschappen voor het effectgedrag weer. Lezen/Schrijven [ITiming](../../com.aspose.slides/itiming).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |