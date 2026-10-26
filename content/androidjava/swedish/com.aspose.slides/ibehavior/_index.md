---
title: IBehavior
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar basklassens beteende för effekt.
type: docs
url: /sv/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

Representerar basklassens beteende för effekt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Representerar huruvida animationsbeteenden ackumuleras. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Representerar huruvida animationsbeteenden ackumuleras. |
| [getAdditive()](#getAdditive--) | Representerar huruvida det aktuella animationsbeteendet kombineras med andra pågående animationer. |
| [setAdditive(int value)](#setAdditive-int-) | Representerar huruvida det aktuella animationsbeteendet kombineras med andra pågående animationer. |
| [getProperties()](#getProperties--) | Representerar egenskaper för beteendet. |
| [getTiming()](#getTiming--) | Representerar tidsinställningsegenskaper för effektbeteendet. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Representerar tidsinställningsegenskaper för effektbeteendet. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

Representerar huruvida animationsbeteenden ackumuleras. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**  
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

Representerar huruvida animationsbeteenden ackumuleras. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

Representerar huruvida det aktuella animationsbeteendet kombineras med andra pågående animationer. Läs/skriv [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Returnerar:**  
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

Representerar huruvida det aktuella animationsbeteendet kombineras med andra pågående animationer. Läs/skriv [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

Representerar egenskaper för beteendet. Endast läsning [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Returnerar:**  
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

Representerar tidsinställningsegenskaper för effektbeteendet. Läs/skriv [ITiming](../../com.aspose.slides/itiming).

**Returnerar:**  
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

Representerar tidsinställningsegenskaper för effektbeteendet. Läs/skriv [ITiming](../../com.aspose.slides/itiming).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |