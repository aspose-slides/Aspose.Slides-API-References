---
title: IBehavior
second_title: Aspose.Slides für Java API-Referenz
description: Stellt das Basisklassenverhalten des Effekts dar.
type: docs
url: /de/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Stellt das Basisklassenverhalten des Effekts dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Gibt an, ob Animationsverhalten akkumuliert werden. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Gibt an, ob Animationsverhalten akkumuliert werden. |
| [getAdditive()](#getAdditive--) | Gibt an, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. |
| [setAdditive(int value)](#setAdditive-int-) | Gibt an, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. |
| [getProperties()](#getProperties--) | Gibt die Eigenschaften des Verhaltens an. |
| [getTiming()](#getTiming--) | Gibt die Zeiteigenschaften für das Effektverhalten an. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Gibt die Zeiteigenschaften für das Effektverhalten an. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Gibt an, ob Animationsverhalten akkumuliert werden. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Gibt an, ob Animationsverhalten akkumuliert werden. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Gibt an, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. Lesen/Schreiben [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Rückgabe:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Gibt an, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. Lesen/Schreiben [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Gibt die Eigenschaften des Verhaltens an. Nur lesen [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Rückgabe:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Gibt die Zeiteigenschaften für das Effektverhalten an. Lesen/Schreiben [ITiming](../../com.aspose.slides/itiming).

**Rückgabe:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Gibt die Zeiteigenschaften für das Effektverhalten an. Lesen/Schreiben [ITiming](../../com.aspose.slides/itiming).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |