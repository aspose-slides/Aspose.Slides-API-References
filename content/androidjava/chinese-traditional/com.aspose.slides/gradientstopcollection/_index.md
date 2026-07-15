---
title: GradientStopCollection
second_title: Aspose.Slides for Android via Java API 參考
description: 表示一個漸層停止點的集合。
type: docs
url: /zh-hant/com.aspose.slides/gradientstopcollection/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**所有已實作的介面:**  
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

表示一個漸層停止點的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | 傳回集合中漸層停止點的數量。 |
| [get_Item(int index)](#get-Item-int-) | 依索引傳回漸層停止點。 |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | 建立新的漸層停止點並將其加入集合的末端。 |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | 建立新的漸層停止點並將其加入集合的末端。 |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | 建立新的漸層停止點並將其加入集合的末端。 |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | 建立新的漸層停止點並插入到集合中指定的索引位置。 |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | 建立新的漸層停止點並插入到集合中指定的索引位置。 |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | 建立新的漸層停止點並插入到集合中指定的索引位置。 |
| [removeAt(int index)](#removeAt-int-) | 移除位於指定索引的漸層停止點。 |
| [clear()](#clear--) | 從集合中移除所有漸層停止點。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | 將集合中的所有元素複製到指定的陣列。 |
| [isSynchronized()](#isSynchronized--) | 傳回一個值以指示對集合的存取是否已同步（執行緒安全）。 |
| [getSyncRoot()](#getSyncRoot--) | 傳回同步根。 |

### getVersion() {#getVersion--}
```
public long getVersion()
```

版本。唯讀 long。

**返回：**  
long

### size() {#size--}
```
public final int size()
```

傳回集合中漸層停止點的數量。唯讀 int 。

**返回：**  
int

### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```

依索引傳回漸層停止點。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int |  |

**返回：**  
[IGradientStop](../../com.aspose.slides/igradientstop)

### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```

建立新的漸層停止點並將其加入集合的末端。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| position | float | 新漸層停止點的位置。 |
| color | java.lang.Integer | 新漸層停止點的顏色。 |

**返回：**  
[IGradientStop](../../com.aspose.slides/igradientstop) - 新漸層停止點在集合中的索引。

### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```

建立新的漸層停止點並將其加入集合的末端。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| position | float | 新漸層停止點的位置。 |
| presetColor | int | 新漸層停止點的顏色。 |

**返回：**  
[IGradientStop](../../com.aspose.slides/igradientstop) - 新漸層停止點在集合中的索引。

### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```

建立新的漸層停止點並將其加入集合的末端。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| position | float | 新漸層停止點的位置。 |
| schemeColor | int | 新漸層停止點的顏色。 |

**返回：**  
[IGradientStop](../../com.aspose.slides/igradientstop) - 新漸層停止點在集合中的索引。

### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```

建立新的漸層停止點並插入到集合中指定的索引位置。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 集合中新漸層停止點將被插入的索引。 |
| position | float | 新漸層停止點的位置。 |
| color | java.lang.Integer | 新漸層停止點的顏色。 |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```

建立新的漸層停止點並插入到集合中指定的索引位置。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 集合中新漸層停止點將被插入的索引。 |
| position | float | 新漸層停止點的位置。 |
| presetColor | int | 新漸層停止點的顏色。 |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```

建立新的漸層停止點並插入到集合中指定的索引位置。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 集合中新漸層停止點將被插入的索引。 |
| position | float | 新漸層停止點的位置。 |
| schemeColor | int | 新漸層停止點的顏色。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除位於指定索引的漸層停止點。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 應刪除的漸層停止點的索引。 |

### clear() {#clear--}
```
public final void clear()
```

移除所有漸層停止點。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```

傳回可遍歷集合的列舉器。

**返回：**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```

傳回整個集合的 java 迭代器。

**返回：**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - An java.util.Iterator for the entire collection.

### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

將集合中的所有元素複製到指定的陣列。

**參數：**  
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | 目標陣列。 |
| index | int | 目標陣列中的起始索引。 |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

傳回一個值以指示對集合的存取是否已同步（執行緒安全）。唯讀 boolean 。

**返回：**  
boolean

### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

傳回同步根。唯讀 Object 。

**返回：**  
java.lang.Object