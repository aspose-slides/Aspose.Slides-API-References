---
title: Behavior
second_title: Aspose.Sildes for Java API Reference
description: p
 Represent base class behavior of effect.
type: docs
weight: 47
url: /java/com.aspose.slides/behavior/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

Represent base class behavior of effect.
## Constructors

| Constructor | Description |
| --- | --- |
| [Behavior()](#Behavior--) | Creates new instance. |
## Methods

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | Represents whether animation behaviors are accumulated. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Represents whether animation behaviors are accumulated. |
| [getAdditive()](#getAdditive--) | Represents whether the current animation behavior is combined with other running animations. |
| [setAdditive(int value)](#setAdditive-int-) | Represents whether the current animation behavior is combined with other running animations. |
| [getProperties()](#getProperties--) | Represents properties of behavior. |
| [getTiming()](#getTiming--) | Represents timing properties for the effect behavior. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Represents timing properties for the effect behavior. |
### Behavior() {#Behavior--}
```
protected Behavior()
```


Creates new instance.

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Returns Parent\_Immediate object. Read-only IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```


Represents whether animation behaviors are accumulated. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


Represents whether animation behaviors are accumulated. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


Represents whether the current animation behavior is combined with other running animations. Read/write [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Returns:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


Represents whether the current animation behavior is combined with other running animations. Read/write [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```


Represents properties of behavior. Read-only [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Returns:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


Represents timing properties for the effect behavior. Read/write [ITiming](../../com.aspose.slides/itiming).

**Returns:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


Represents timing properties for the effect behavior. Read/write [ITiming](../../com.aspose.slides/itiming).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |

