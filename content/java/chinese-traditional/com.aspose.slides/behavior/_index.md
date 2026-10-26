---
title: Behavior
second_title: Aspose.Slides for Java API 參考
description: 表示效果的基底類別行為。
type: docs
url: /zh-hant/com.aspose.slides/behavior/
---
**繼承:**
java.lang.Object

**全部已實作的介面:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject
```
public abstract class Behavior implements IBehavior, IDOMObject
```

表示效果的基底類別行為。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | 表示動畫行為是否累積。 |
| [setAccumulate(byte value)](#setAccumulate-byte-) | 表示動畫行為是否累積。 |
| [getAdditive()](#getAdditive--) | 表示目前的動畫行為是否與其他執行中的動畫結合。 |
| [setAdditive(int value)](#setAdditive-int-) | 表示目前的動畫行為是否與其他執行中的動畫結合。 |
| [getProperties()](#getProperties--) | 表示行為的屬性。 |
| [getTiming()](#getTiming--) | 表示效果行為的時序屬性。 |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | 表示效果行為的時序屬性。 |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


回傳 Parent_Immediate 物件。唯讀 IDOMObject。

**回傳值:**
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```


表示動畫行為是否累積。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**回傳值:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```


表示動畫行為是否累積。可讀寫 [NullableBool](../../com.aspose.slides/nullablebool)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```


表示目前的動畫行為是否與其他執行中的動畫結合。可讀寫 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**回傳值:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```


表示目前的動畫行為是否與其他執行中的動畫結合。可讀寫 [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```


表示行為的屬性。唯讀 [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)。

**回傳值:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```


表示效果行為的時序屬性。可讀寫 [ITiming](../../com.aspose.slides/itiming)。

**回傳值:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```


表示效果行為的時序屬性。可讀寫 [ITiming](../../com.aspose.slides/itiming)。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |