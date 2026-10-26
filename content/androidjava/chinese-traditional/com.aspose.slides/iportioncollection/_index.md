---
title: IPortionCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示一組 portions。
type: docs
url: /zh-hant/com.aspose.slides/iportioncollection/
---
**已實作的所有介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

表示一組 portions。

## 方法

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 取得指定索引處的元素。 |
| [getCount()](#getCount--) | 取得集合實際包含的元素數量。 |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | 將 Portion 新增至集合尾端。 |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | 決定集合中特定 portion 的索引。 |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | 在指定索引處將 Portion 插入集合。 |
| [clear()](#clear--) | 從集合中移除所有元素。 |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | 判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定的值。 |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | 從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除第一個出現的特定物件。 |
| [removeAt(int index)](#removeAt-int-) | 移除集合中指定索引處的元素。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

取得指定索引處的元素。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int |  |

**傳回值：**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

取得集合實際包含的元素數量。唯讀 int。

**傳回值：**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

將 Portion 新增至集合尾端。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | 要新增至集合尾端的 Portion。 |
### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

決定集合中特定 portion 的索引。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要在集合中定位的 portion。 |

**傳回值：**
int - 若在集合中找到項目，則返回其索引；否則返回 -1。
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

在指定索引處將 Portion 插入集合。

**參數：**
| 參數 | 類型 | 描述 |
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

判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定的值。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的物件。 |

**傳回值：**
boolean - 若在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到項目則為 true；否則為 false。
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除第一個出現的特定物件。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | 要從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中移除的物件。 |

**傳回值：**
boolean - 若項目已成功從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 移除則為 true；否則為 false。如果在原始的 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中未找到項目，該方法亦返回 false。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除集合中指定索引處的元素。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| index | int | 要移除之元素的零基索引。 |