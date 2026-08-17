---
title: Behavior
second_title: Aspose.Slides für Java API Referenz
description: Repräsentiert das Basisklassenverhalten des Effekts.
type: docs
url: /de/com.aspose.slides/behavior/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Repräsentiert das Basisklassenverhalten des Effekts.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Gibt an, ob Animationsverhalten akkumuliert werden. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Gibt an, ob Animationsverhalten akkumuliert werden. |
| [getAdditive()](#getAdditive--) | Gibt an, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. |
| [setAdditive(int value)](#setAdditive-int-) | Gibt an, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. |
| [getProperties()](#getProperties--) | Gibt die Eigenschaften des Verhaltens an. |
| [getTiming()](#getTiming--) | Stellt die Zeiteigenschaften für das Effektverhalten dar. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Stellt die Zeiteigenschaften für das Effektverhalten dar. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Gibt das Parent_Immediate-Objekt zurück. Nur-Lese IDOMObject.

**Rückgabe:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```


Gibt an, ob Animationsverhalten akkumuliert werden. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


Gibt an, ob Animationsverhalten akkumuliert werden. Lese/Schreib [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


Gibt an, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. Lese/Schreib [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Rückgabe:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


Gibt an, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. Lese/Schreib [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```


Gibt die Eigenschaften des Verhaltens an. Nur-Lese [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Rückgabe:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Stellt die Zeiteigenschaften für das Effektverhalten dar. Lese/Schreib [ITiming](../../com.aspose.slides/itiming).

**Rückgabe:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Stellt die Zeiteigenschaften für das Effektverhalten dar. Lese/Schreib [ITiming](../../com.aspose.slides/itiming).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |