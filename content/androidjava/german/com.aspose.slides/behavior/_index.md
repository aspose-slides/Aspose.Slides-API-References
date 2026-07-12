---
title: Behavior
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt das Basisklassenverhalten des Effekts dar.
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

Stellt das Basisklassenverhalten des Effekts dar.

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Stellt dar, ob Animationsverhalten akkumuliert werden. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Stellt dar, ob Animationsverhalten akkumuliert werden. |
| [getAdditive()](#getAdditive--) | Stellt dar, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. |
| [setAdditive(int value)](#setAdditive-int-) | Stellt dar, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. |
| [getProperties()](#getProperties--) | Stellt die Eigenschaften des Verhaltens dar. |
| [getTiming()](#getTiming--) | Stellt die Timing-Eigenschaften für das Effektverhalten dar. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Stellt die Timing-Eigenschaften für das Effektverhalten dar. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Gibt das Parent_Immediate-Objekt zurück. Nur lesbar IDOMObject.

**Rückgabewert:**
com.aspose.slides.IDOMObject

### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

Stellt dar, ob Animationsverhalten akkumuliert werden. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Rückgabewert:**
byte

### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

Stellt dar, ob Animationsverhalten akkumuliert werden. Lesen/Schreiben [NullableBool](../../com.aspose.slides/nullablebool).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

Stellt dar, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. Lesen/Schreiben [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Rückgabewert:**
int

### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

Stellt dar, ob das aktuelle Animationsverhalten mit anderen laufenden Animationen kombiniert wird. Lesen/Schreiben [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

Stellt die Eigenschaften des Verhaltens dar. Nur lesbar [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Rückgabewert:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Stellt die Timing-Eigenschaften für das Effektverhalten dar. Lesen/Schreiben [ITiming](../../com.aspose.slides/itiming).

**Rückgabewert:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Stellt die Timing-Eigenschaften für das Effektverhalten dar. Lesen/Schreiben [ITiming](../../com.aspose.slides/itiming).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |