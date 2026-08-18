---
title: IBehavior
second_title: Aspose.Slides Java API referenciája
description: Az effektus alaposztály-viselkedését reprezentálja.
type: docs
url: /hu/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Az effektus alaposztály-viselkedését reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Ábrázolja, hogy a animációs viselkedések felhalmozódnak-e. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Ábrázolja, hogy a animációs viselkedések felhalmozódnak-e. |
| [getAdditive()](#getAdditive--) | Ábrázolja, hogy a jelenlegi animációs viselkedés más futó animációkkal kombinálódik-e. |
| [setAdditive(int value)](#setAdditive-int-) | Ábrázolja, hogy a jelenlegi animációs viselkedés más futó animációkkal kombinálódik-e. |
| [getProperties()](#getProperties--) | Ábrázolja a viselkedés tulajdonságait. |
| [getTiming()](#getTiming--) | Ábrázolja az effektus viselkedés időzítési tulajdonságait. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Ábrázolja az effektus viselkedés időzítési tulajdonságait. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Ábrázolja, hogy a animációs viselkedések felhalmozódnak-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Ábrázolja, hogy a animációs viselkedések felhalmozódnak-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Ábrázolja, hogy a jelenlegi animációs viselkedés más futó animációkkal kombinálódik-e. Olvasás/írás [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Visszatérési érték:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Ábrázolja, hogy a jelenlegi animációs viselkedés más futó animációkkal kombinálódik-e. Olvasás/írás [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Ábrázolja a viselkedés tulajdonságait. Csak olvasható [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Visszatérési érték:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Ábrázolja az effektus viselkedés időzítési tulajdonságait. Olvasás/írás [ITiming](../../com.aspose.slides/itiming).

**Visszatérési érték:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Ábrázolja az effektus viselkedés időzítési tulajdonságait. Olvasás/írás [ITiming](../../com.aspose.slides/itiming).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |