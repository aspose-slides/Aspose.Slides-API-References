---
title: IBehavior
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt das Basisklassenverhalten des Effekts dar.
type: docs
url: /de/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Stellt das Basisklassenverhalten des Effekts dar.
## Methoden

| Method | Description |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Stellt dar, ob Animationsverhalten akkumuliert wird. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Stellt dar, ob Animationsverhalten akkumuliert wird. |
| [getAdditive()](#getAdditive--) | Stellt dar, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. |
| [setAdditive(int value)](#setAdditive-int-) | Stellt dar, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. |
| [getProperties()](#getProperties--) | Stellt die Eigenschaften des Verhaltens dar. |
| [getTiming()](#getTiming--) | Stellt die Zeiteigenschaften für das Effektverhalten dar. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Stellt die Zeiteigenschaften für das Effektverhalten dar. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Stellt dar, ob Animationsverhalten akkumuliert wird. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabe:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Stellt dar, ob Animationsverhalten akkumuliert wird. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Stellt dar, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. Lesen/Schreiben [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Rückgabe:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Stellt dar, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. Lesen/Schreiben [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Stellt die Eigenschaften des Verhaltens dar. Nur Lesen [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Rückgabe:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Stellt die Zeiteigenschaften für das Effektverhalten dar. Lesen/Schreiben [ITiming](../../com.aspose.slides/itiming).

**Rückgabe:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Stellt die Zeiteigenschaften für das Effektverhalten dar. Lesen/Schreiben [ITiming](../../com.aspose.slides/itiming).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |