---
title: Behavior
second_title: Aspose.Slides for Android via Java API 参考
description: 表示效果的基类行为。
type: docs
url: /zh/com.aspose.slides/behavior/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject  
```
public abstract class Behavior implements IBehavior, IDOMObject
```

表示效果的基类行为。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | 表示动画行为是否被累积。 |
| [setAccumulate(byte value)](#setAccumulate-byte-) | 表示动画行为是否被累积。 |
| [getAdditive()](#getAdditive--) | 表示当前动画行为是否与其他正在运行的动画组合。 |
| [setAdditive(int value)](#setAdditive-int-) | 表示当前动画行为是否与其他正在运行的动画组合。 |
| [getProperties()](#getProperties--) | 表示行为的属性。 |
| [getTiming()](#getTiming--) | 表示效果行为的时间属性。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 表示效果行为的时间属性。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 对象。只读 IDOMObject。

**返回:**  
com.aspose.slides.IDOMObject

### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

表示动画行为是否被累积。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回:**  
byte

### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

表示动画行为是否被累积。读/写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

表示当前动画行为是否与其他正在运行的动画组合。读/写 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**返回:**  
int

### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

表示当前动画行为是否与其他正在运行的动画组合。读/写 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

表示行为的属性。只读 [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)。

**返回:**  
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

表示效果行为的时间属性。读/写 [ITiming](../../com.aspose.slides/itiming)。

**返回:**  
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

表示效果行为的时间属性。读/写 [ITiming](../../com.aspose.slides/itiming)。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |