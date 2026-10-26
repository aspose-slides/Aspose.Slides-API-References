---
title: Behavior
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt het basisklassen gedrag van het effect voor.
type: docs
url: /nl/com.aspose.slides/behavior/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Stelt het basisklassen gedrag van het effect voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Stelt voor of animatiegedragingen worden opgeteld. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Stelt voor of animatiegedragingen worden opgeteld. |
| [getAdditive()](#getAdditive--) | Stelt voor of het huidige animatiegedrag wordt gecombineerd met andere lopende animaties. |
| [setAdditive(int value)](#setAdditive-int-) | Stelt voor of het huidige animatiegedrag wordt gecombineerd met andere lopende animaties. |
| [getProperties()](#getProperties--) | Stelt eigenschappen van gedrag voor. |
| [getTiming()](#getTiming--) | Stelt timingeigenschappen voor het effectgedrag voor. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Stelt timingeigenschappen voor het effectgedrag voor. |
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


Stelt voor of animatiegedragingen worden opgeteld. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


Stelt voor of animatiegedragingen worden opgeteld. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


Stelt voor of het huidige animatiegedrag wordt gecombineerd met andere lopende animaties. Lezen/Schrijven [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Retourneert:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


Stelt voor of het huidige animatiegedrag wordt gecombineerd met andere lopende animaties. Lezen/Schrijven [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```


Stelt eigenschappen van gedrag voor. Alleen-lezen [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Retourneert:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Stelt timingeigenschappen voor het effectgedrag voor. Lezen/Schrijven [ITiming](../../com.aspose.slides/itiming).

**Retourneert:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Stelt timingeigenschappen voor het effectgedrag voor. Lezen/Schrijven [ITiming](../../com.aspose.slides/itiming).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |