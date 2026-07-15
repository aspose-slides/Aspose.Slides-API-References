---
title: Behavior
second_title: Aspose.Slides for Android via Java API 參考
description: 表示效果的基礎類別行為。
type: docs
url: /zh-hant/com.aspose.slides/behavior/
---
**繼承:**  
java.lang.Object

**所有已實作的介面:**  
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject  
```
public abstract class Behavior implements IBehavior, IDOMObject
```

表示效果的基礎類別行為。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | 表示動畫行為是否累積。 |
| [setAccumulate(byte value)](#setAccumulate-byte-) | 表示動畫行為是否累積。 |
| [getAdditive()](#getAdditive--) | 表示當前動畫行為是否與其他正在執行的動畫結合。 |
| [setAdditive(int value)](#setAdditive-int-) | 表示當前動畫行為是否與其他正在執行的動畫結合。 |
| [getProperties()](#getProperties--) | 表示行為的屬性。 |
| [getTiming()](#getTiming--) | 表示效果行為的時間屬性。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 表示效果行為的時間屬性。 |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

返回 Parent_Immediate 物件。唯讀 IDOMObject。

**回傳:**  
com.aspose.slides.IDOMObject

### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

表示動畫行為是否累積。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**回傳:**  
byte

### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

表示動畫行為是否累積。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

表示當前動畫行為是否與其他正在執行的動畫結合。可讀寫 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**回傳:**  
int

### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

表示當前動畫行為是否與其他正在執行的動畫結合。可讀寫 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

表示行為的屬性。唯讀 [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)。

**回傳:**  
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

表示效果行為的時間屬性。可讀寫 [ITiming](../../com.aspose.slides/itiming)。

**回傳:**  
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

表示效果行為的時間屬性。可讀寫 [ITiming](../../com.aspose.slides/itiming)。

**參數:**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |