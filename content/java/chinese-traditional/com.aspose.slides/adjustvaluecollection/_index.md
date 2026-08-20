---
title: AdjustValueCollection
second_title: Aspose.Slides Java API 參考
description: 表示形狀調整的集合。
type: docs
url: /zh-hant/com.aspose.slides/adjustvaluecollection/
---
**繼承：**
java.lang.Object, com.aspose.slides.DomObject

**所有已實作的介面：**
[com.aspose.slides.IAdjustValueCollection](../../com.aspose.slides/iadjustvaluecollection)
```
public final class AdjustValueCollection extends DomObject<GeometryShape> implements IAdjustValueCollection
```

表示形狀調整的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [size()](#size--) | 傳回調整項的數量。 |
| [get_Item(int index)](#get-Item-int-) | 傳回指定索引的調整項。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回指示集合存取是否同步（執行緒安全）的值。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |
| [iterator()](#iterator--) | 傳回整個集合的列舉器。 |

### size() {#size--}
```
public final int size()
```

傳回調整項的數量。唯讀 int。

**返回：**
int

### get_Item(int index) {#get-Item-int-}
```
public final IAdjustValue get_Item(int index)
```

傳回指定索引的調整項。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 調整項的索引。 |

**返回：**
[IAdjustValue](../../com.aspose.slides/iadjustvalue) - [AdjustValue](../../com.aspose.slides/adjustvalue)。

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回指示集合存取是否同步（執行緒安全）的值。唯讀 boolean。

**返回：**
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object。

**返回：**
java.lang.Object

### iterator() {#iterator--}
```
public final System.Collections.IEnumerator iterator()
```

傳回整個集合的列舉器。

**返回：**
com.aspose.ms.System.Collections.IEnumerator