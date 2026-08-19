---
title: IBehavior
second_title: Aspose.Slides for Java API Reference
description: Representerar basklassens beteende för en effekt.
type: docs
url: /sv/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Representerar basklassens beteende för en effekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Anger om animationsbeteenden ackumuleras. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Anger om animationsbeteenden ackumuleras. |
| [getAdditive()](#getAdditive--) | Anger om det aktuella animationsbeteendet kombineras med andra pågående animationer. |
| [setAdditive(int value)](#setAdditive-int-) | Anger om det aktuella animationsbeteendet kombineras med andra pågående animationer. |
| [getProperties()](#getProperties--) | Anger egenskaper för beteendet. |
| [getTiming()](#getTiming--) | Anger tidsegenskaper för effektbeteendet. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Anger tidsegenskaper för effektbeteendet. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Anger om animationsbeteenden ackumuleras. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Anger om animationsbeteenden ackumuleras. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Anger om det aktuella animationsbeteendet kombineras med andra pågående animationer. Läs/skriv [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Returnerar:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Anger om det aktuella animationsbeteendet kombineras med andra pågående animationer. Läs/skriv [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Anger egenskaper för beteendet. Endast läsning [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Returnerar:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Anger tidsegenskaper för effektbeteendet. Läs/skriv [ITiming](../../com.aspose.slides/itiming).

**Returnerar:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Anger tidsegenskaper för effektbeteendet. Läs/skriv [ITiming](../../com.aspose.slides/itiming).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |