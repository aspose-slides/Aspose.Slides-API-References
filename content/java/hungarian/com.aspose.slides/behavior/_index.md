---
title: Behavior
second_title: Aspose.Slides Java API referencia
description: Az effektus alaposztályának viselkedését ábrázolja.
type: docs
url: /hu/com.aspose.slides/behavior/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Ábrázolja az effektus alaposztály viselkedését.

## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Jélzi, hogy az animációs viselkedések felhalmozódnak-e. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Jélzi, hogy az animációs viselkedések felhalmozódnak-e. |
| [getAdditive()](#getAdditive--) | Jélzi, hogy a jelenlegi animációs viselkedés egyesül-e más futó animációkkal. |
| [setAdditive(int value)](#setAdditive-int-) | Jélzi, hogy a jelenlegi animációs viselkedés egyesül-e más futó animációkkal. |
| [getProperties()](#getProperties--) | Jélzi a viselkedés tulajdonságait. |
| [getTiming()](#getTiming--) | Jélzi az effektus viselkedés időzítési tulajdonságait. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Jélzi az effektus viselkedés időzítési tulajdonságait. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszatér a Parent_Immediate objektummal. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject

### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

Jélzi, hogy az animációs viselkedések felhalmozódnak-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

Jélzi, hogy az animációs viselkedések felhalmozódnak-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

Jélzi, hogy a jelenlegi animációs viselkedés egyesül-e más futó animációkkal. Olvasás/írás [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Visszatér:**
int

### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

Jélzi, hogy a jelenlegi animációs viselkedés egyesül-e más futó animációkkal. Olvasás/írás [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

Jélzi a viselkedés tulajdonságait. Csak olvasható [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Visszatér:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Jélzi az effektus viselkedés időzítési tulajdonságait. Olvasás/írás [ITiming](../../com.aspose.slides/itiming).

**Visszatér:**
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Jélzi az effektus viselkedés időzítési tulajdonságait. Olvasás/írás [ITiming](../../com.aspose.slides/itiming).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |