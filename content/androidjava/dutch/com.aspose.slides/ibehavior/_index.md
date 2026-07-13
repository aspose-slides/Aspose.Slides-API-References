---
title: IBehavior
second_title: Aspose.Slides voor Android via Java API-referentie
description: Vertegenwoordigt het basisgedrag van een effect.
type: docs
url: /nl/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Vertegenwoordigt het basisgedrag van een effect.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Geeft aan of animatiegedragingen worden opgehoopt. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Geeft aan of animatiegedragingen worden opgehoopt. |
| [getAdditive()](#getAdditive--) | Geeft aan of het huidige animatiegedrag wordt gecombineerd met andere lopende animaties. |
| [setAdditive(int value)](#setAdditive-int-) | Geeft aan of het huidige animatiegedrag wordt gecombineerd met andere lopende animaties. |
| [getProperties()](#getProperties--) | Geeft de eigenschappen van gedrag weer. |
| [getTiming()](#getTiming--) | Geeft de timingeigenschappen voor het effectgedrag weer. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Geeft de timingeigenschappen voor het effectgedrag weer. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Geeft aan of animatiegedragingen worden opgehoopt. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Geeft aan of animatiegedragingen worden opgehoopt. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

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

Geeft de eigenschappen van gedrag weer. Alleen-lezen [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Retour:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Geeft de timingeigenschappen voor het effectgedrag weer. Lezen/Schrijven [ITiming](../../com.aspose.slides/itiming).

**Retour:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Geeft de timingeigenschappen voor het effectgedrag weer. Lezen/Schrijven [ITiming](../../com.aspose.slides/itiming).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |