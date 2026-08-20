---
title: PortionCollection
second_title: Aspose.Slides for Java API 參考
description: 表示一個 Portion 的集合。
type: docs
url: /zh-hant/com.aspose.slides/portioncollection/
---
**繼承:**  
java.lang.Object, com.aspose.slides.DomObject

**所有已實作介面:**  
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)  
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

表示一個 Portion 的集合。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getCount()](#getCount--) | 取得實際包含於集合中的元素數量。 |
| [isReadOnly()](#isReadOnly--) | 取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否唯讀的值。 |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | 取得指定索引處的元素。 |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | 將 Portion 新增到集合的末端。 |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | 確定 List 中特定項目的索引。 |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | 在指定索引處將 Portion 插入集合。 |
| [clear()](#clear--) | 移除集合中的所有元素。 |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | 確定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | 複製 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素到陣列，從指定的陣列索引開始。 |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | 從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除首個出現的特定物件。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的元素。 |
| [iterator()](#iterator--) | 傳回遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |

### getCount() {#getCount--}
```
public final int getCount()
```

取得實際包含於集合中的元素數量。唯讀 int。

**返回:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否唯讀的值。唯讀 boolean。

**返回:**  
boolean - 如果 [IGenericCollection](../../com.aspose.slides/igenericcollection) 為唯讀則為 true；否則為 false。

### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```

取得指定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回:**  
[IPortion](../../com.aspose.slides/iportion)

### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```

取得指定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```

將 Portion 新增到集合的末端。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | 要新增至集合末端的 Portion。 |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```

確定 List 中特定項目的索引。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要在 List 中定位的物件。 |

**返回:**  
int - 若在列表中找到 item，則返回其索引；否則返回 -1。

### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```

在指定索引處將 Portion 插入集合。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入 Portion 的零基索引位置。 |
| value | [IPortion](../../com.aspose.slides/iportion) | 要插入的 Portion。 |

### clear() {#clear--}
```
public final void clear()
```

移除集合中的所有元素。

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```

確定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的物件。 |

**返回:**  
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到 item 則返回 true；否則返回 false。

### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```

將 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素複製到一維陣列，從指定的陣列索引開始。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | 從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 複製元素的目標一維陣列。該陣列必須使用零基索引。 |
| arrayIndex | int | 開始複製的陣列零基索引位置。 |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```

從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除首個出現的特定物件。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除的物件。 |

**返回:**  
boolean - 如果成功從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除 item，則返回 true；否則返回 false。如果在原始 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中未找到 item，亦返回 false。

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

移除集合中指定索引處的元素。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```

傳回遍歷集合的列舉器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```

傳回整個集合的 java 迭代器。

**返回:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - 用於遍歷整個集合的 java.util.Iterator。