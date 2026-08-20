---
title: IPortionCollection
second_title: Aspose.Slides for Java API 參考
description: 表示部分的集合。
type: docs
url: /zh-hant/com.aspose.slides/iportioncollection/
---
**已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

表示一個部分的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getCount()](#getCount--) | 取得集合中實際包含的元素數量。 |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | 將 Portion 加到集合的末端。 |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | 確定集合中特定 portion 的索引。 |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | 在指定索引處將 Portion 插入集合。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | 確定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | 從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除特定物件的首次出現。 |
| [removeAt(int index)](#removeAt-int-) | 從集合中移除指定索引處的元素。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

取得指定索引處的元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int |  |

**返回值：**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

取得集合中實際包含的元素數量。唯讀 int。

**返回值：**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

將 Portion 加到集合的末端。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | 要加入集合末端的 Portion。 |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

確定集合中特定 portion 的索引。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要在集合中定位的 portion。 |

**返回值：**
int - 若在集合中找到 item 則返回其索引；否則返回 -1。
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

在指定索引處將 Portion 插入集合。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要插入 Portion 的零基索引。 |
| value | [IPortion](../../com.aspose.slides/iportion) | 要插入的 Portion。 |

### clear() {#clear--}
```
public abstract void clear()
```

從集合中移除所有元素。

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

確定 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的物件。 |

**返回值：**
boolean - 若在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到 item 則為 true；否則為 false。 
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除特定物件的首次出現。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除的物件。 |

**返回值：**
boolean - 若成功從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除 item 則為 true；否則為 false。若在原始 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中未找到 item，此方法亦返回 false。 
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

從集合中移除指定索引處的元素。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |