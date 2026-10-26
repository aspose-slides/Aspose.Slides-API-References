---
title: Behavior
second_title: Aspose.Slides för Java API-referens
description: Representerar basklassens beteende för en effekt.
type: docs
url: /sv/com.aspose.slides/behavior/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Representerar basklassens beteende för effekten.

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Representerar huruvida animationsbeteenden ackumuleras. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Representerar huruvida animationsbeteenden ackumuleras. |
| [getAdditive()](#getAdditive--) | Representerar huruvida det aktuella animationsbeteendet kombineras med andra pågående animationer. |
| [setAdditive(int value)](#setAdditive-int-) | Representerar huruvida det aktuella animationsbeteendet kombineras med andra pågående animationer. |
| [getProperties()](#getProperties--) | Representerar egenskaper för beteendet. |
| [getTiming()](#getTiming--) | Representerar tidsrelaterade egenskaper för effektbeteendet. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Representerar tidsrelaterade egenskaper för effektbeteendet. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Returnerar Parent_Immediate-objekt. Skrivskyddad IDOMObject.

**Returnerar:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

Representerar huruvida animationsbeteenden ackumuleras. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

Representerar huruvida animationsbeteenden ackumuleras. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

Representerar huruvida det aktuella animationsbeteendet kombineras med andra pågående animationer. Läs/skriv [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Returnerar:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

Representerar huruvida det aktuella animationsbeteendet kombineras med andra pågående animationer. Läs/skriv [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

Representerar egenskaper för beteendet. Skrivskyddad [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Returnerar:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

Representerar tidsrelaterade egenskaper för effektbeteendet. Läs/skriv [ITiming](../../com.aspose.slides/itiming).

**Returnerar:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

Representerar tidsrelaterade egenskaper för effektbeteendet. Läs/skriv [ITiming](../../com.aspose.slides/itiming).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |