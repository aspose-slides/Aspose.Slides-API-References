---
title: IBehavior
second_title: Aspose.Slides for Java API Reference
description: 表示效果的基类行为。
type: docs
url: /zh/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

表示效果的基类行为。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | 表示动画行为是否累积。 |
| [setAccumulate(byte value)](#setAccumulate-byte-) | 表示动画行为是否累积。 |
| [getAdditive()](#getAdditive--) | 表示当前动画行为是否与其他正在运行的动画合并。 |
| [setAdditive(int value)](#setAdditive-int-) | 表示当前动画行为是否与其他正在运行的动画合并。 |
| [getProperties()](#getProperties--) | 表示行为的属性。 |
| [getTiming()](#getTiming--) | 表示效果行为的计时属性。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 表示效果行为的计时属性。 |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

表示动画行为是否累积。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回值:**  
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

表示动画行为是否累积。读写 [NullableBool](../../com.aspose.slides/nullablebool)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

表示当前动画行为是否与其他正在运行的动画合并。读写 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**返回值:**  
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

表示当前动画行为是否与其他正在运行的动画合并。读写 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

表示行为的属性。只读 [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)。

**返回值:**  
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

表示效果行为的计时属性。读写 [ITiming](../../com.aspose.slides/itiming)。

**返回值:**  
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

表示效果行为的计时属性。读写 [ITiming](../../com.aspose.slides/itiming)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |