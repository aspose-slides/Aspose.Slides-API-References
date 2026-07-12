---
title: Behavior
second_title: Aspose.Slides Androidhoz a Java API hivatkozás
description: Az effektus alaposztályának viselkedését reprezentálja.
type: docs
url: /hu/com.aspose.slides/behavior/
---
**Öröklés:**
java.lang.Object

**Minden implementált interfész:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Az effektus alaposztály viselkedését reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Azt jelzi, hogy az animációs viselkedések felhalmozottak-e. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Azt jelzi, hogy az animációs viselkedések felhalmozottak-e. |
| [getAdditive()](#getAdditive--) | Azt jelzi, hogy a jelenlegi animációs viselkedés más futó animációkkal kombinálva van-e. |
| [setAdditive(int value)](#setAdditive-int-) | Azt jelzi, hogy a jelenlegi animációs viselkedés más futó animációkkal kombinálva van-e. |
| [getProperties()](#getProperties--) | A viselkedés tulajdonságait reprezentálja. |
| [getTiming()](#getTiming--) | Az effektus viselkedés időzítési tulajdonságait reprezentálja. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Az effektus viselkedés időzítési tulajdonságait reprezentálja. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatér:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

Azt jelzi, hogy az animációs viselkedések felhalmozottak-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

Azt jelzi, hogy az animációs viselkedések felhalmozottak-e. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

Azt jelzi, hogy a jelenlegi animációs viselkedés más futó animációkkal kombinálva van-e. Olvasás/írás [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Visszatér:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

Azt jelzi, hogy a jelenlegi animációs viselkedés más futó animációkkal kombinálva van-e. Olvasás/írás [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

A viselkedés tulajdonságait reprezentálja. Csak olvasható [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Visszatér:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Az effektus viselkedés időzítési tulajdonságait reprezentálja. Olvasás/írás [ITiming](../../com.aspose.slides/itiming).

**Visszatér:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Az effektus viselkedés időzítési tulajdonságait reprezentálja. Olvasás/írás [ITiming](../../com.aspose.slides/itiming).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |