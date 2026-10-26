---
title: IBehavior
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示效果的基礎類別行為。
type: docs
url: /zh-hant/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

表示效果的基礎類別行為。
## Methods

| Method | Description |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | 表示動畫行為是否會累積。 |
| [setAccumulate(byte value)](#setAccumulate-byte-) | 表示動畫行為是否會累積。 |
| [getAdditive()](#getAdditive--) | 表示當前動畫行為是否與其他正在執行的動畫結合。 |
| [setAdditive(int value)](#setAdditive-int-) | 表示當前動畫行為是否與其他正在執行的動畫結合。 |
| [getProperties()](#getProperties--) | 表示行為的屬性。 |
| [getTiming()](#getTiming--) | 表示效果行為的計時屬性。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 表示效果行為的計時屬性。 |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```


表示動畫行為是否會累積。 讀寫 [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```


表示動畫行為是否會累積。 讀寫 [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```


表示當前動畫行為是否與其他正在執行的動畫結合。 讀寫 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Returns:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```


表示當前動畫行為是否與其他正在執行的動畫結合。 讀寫 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```


表示行為的屬性。 唯讀 [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)。

**Returns:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


表示效果行為的計時屬性。 讀寫 [ITiming](../../com.aspose.slides/itiming)。

**Returns:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


表示效果行為的計時屬性。 讀寫 [ITiming](../../com.aspose.slides/itiming)。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |