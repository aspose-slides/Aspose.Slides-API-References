---
title: Behavior
second_title: Aspose.Slides voor Java API-referentie
description: Stelt het gedrag van de basisklasse van het effect voor.
type: docs
url: /nl/com.aspose.slides/behavior/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Stelt het gedrag van de basisklasse van het effect voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Geeft aan of animatiegedragingen worden opgeteld. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Geeft aan of animatiegedragingen worden opgeteld. |
| [getAdditive()](#getAdditive--) | Geeft aan of het huidige animatiegedrag wordt gecombineerd met andere lopende animaties. |
| [setAdditive(int value)](#setAdditive-int-) | Geeft aan of het huidige animatiegedrag wordt gecombineerd met andere lopende animaties. |
| [getProperties()](#getProperties--) | Geeft eigenschappen van gedrag weer. |
| [getTiming()](#getTiming--) | Geeft timingeigenschappen voor het effectgedrag weer. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Geeft timingeigenschappen voor het effectgedrag weer. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Retourneert Parent_Immediate object. Alleen-lezen IDOMObject.

**Retourneert:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```


Geeft aan of animatiegedragingen worden opgeteld. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


Geeft aan of animatiegedragingen worden opgeteld. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


Geeft aan of het huidige animatiegedrag wordt gecombineerd met andere lopende animaties. Lezen/Schrijven [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Retourneert:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


Geeft aan of het huidige animatiegedrag wordt gecombineerd met andere lopende animaties. Lezen/Schrijven [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```


Geeft eigenschappen van gedrag weer. Alleen-lezen [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Retourneert:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Geeft timingeigenschappen voor het effectgedrag weer. Lezen/Schrijven [ITiming](../../com.aspose.slides/itiming).

**Retourneert:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Geeft timingeigenschappen voor het effectgedrag weer. Lezen/Schrijven [ITiming](../../com.aspose.slides/itiming).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |