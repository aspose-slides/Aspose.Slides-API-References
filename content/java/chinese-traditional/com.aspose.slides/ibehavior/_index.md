---
title: IBehavior
second_title: Aspose.Slides for Java API 參考說明
description: 表示效果的基礎類別行為。
type: docs
url: /zh-hant/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

表示效果的基礎類別行為。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | 表示是否累積動畫行為。 |
| [setAccumulate(byte value)](#setAccumulate-byte-) | 表示是否累積動畫行為。 |
| [getAdditive()](#getAdditive--) | 表示目前的動畫行為是否與其他正在執行的動畫結合。 |
| [setAdditive(int value)](#setAdditive-int-) | 表示目前的動畫行為是否與其他正在執行的動畫結合。 |
| [getProperties()](#getProperties--) | 表示行為的屬性。 |
| [getTiming()](#getTiming--) | 表示效果行為的時序屬性。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 表示效果行為的時序屬性。 |

### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

表示是否累積動畫行為。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**返回值:**  
byte

### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

表示是否累積動畫行為。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

表示目前的動畫行為是否與其他正在執行的動畫結合。可讀寫 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**返回值:**  
int

### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

表示目前的動畫行為是否與其他正在執行的動畫結合。可讀寫 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

表示行為的屬性。唯讀 [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)。

**返回值:**  
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)

### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

表示效果行為的時序屬性。可讀寫 [ITiming](../../com.aspose.slides/itiming)。

**返回值:**  
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

表示效果行為的時序屬性。可讀寫 [ITiming](../../com.aspose.slides/itiming)。

**參數:**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |