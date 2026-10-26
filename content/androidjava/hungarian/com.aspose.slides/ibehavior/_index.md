---
title: IBehavior
second_title: Aspose.Slides Androidra Java API Referencia
description: Az effektus alaposztályának viselkedését reprezentálja.
type: docs
url: /hu/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Az effektus alaposztályának viselkedését reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Jeleníti, hogy az animációs viselkedések összeadódnak-e. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Jeleníti, hogy az animációs viselkedések összeadódnak-e. |
| [getAdditive()](#getAdditive--) | Jeleníti, hogy a jelenlegi animációs viselkedés össze van-e kombinálva más futó animációkkal. |
| [setAdditive(int value)](#setAdditive-int-) | Jeleníti, hogy a jelenlegi animációs viselkedés össze van-e kombinálva más futó animációkkal. |
| [getProperties()](#getProperties--) | Jeleníti a viselkedés tulajdonságait. |
| [getTiming()](#getTiming--) | Jeleníti az effektus viselkedés időzítési tulajdonságait. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Jeleníti az effektus viselkedés időzítési tulajdonságait. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Jelzi, hogy az animációs viselkedések összeadódnak-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatérési érték:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Jelzi, hogy az animációs viselkedések összeadódnak-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Jelzi, hogy a jelenlegi animációs viselkedés össze van-e kombinálva más futó animációkkal. Olvasás/írás [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Visszatérési érték:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Jelzi, hogy a jelenlegi animációs viselkedés össze van-e kombinálva más futó animációkkal. Olvasás/írás [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Jelzi a viselkedés tulajdonságait. Csak olvasható [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Visszatérési érték:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Jelzi az effektus viselkedés időzítési tulajdonságait. Olvasás/írás [ITiming](../../com.aspose.slides/itiming).

**Visszatérési érték:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Jelzi az effektus viselkedés időzítési tulajdonságait. Olvasás/írás [ITiming](../../com.aspose.slides/itiming).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |