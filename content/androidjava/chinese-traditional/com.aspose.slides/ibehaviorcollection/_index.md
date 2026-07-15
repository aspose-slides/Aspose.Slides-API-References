---
title: IBehaviorCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 代表行為效果的集合。
type: docs
url: /zh-hant/com.aspose.slides/ibehaviorcollection/
---
**全部已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

代表行為效果的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引處的行為。 |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | 返回指定索引處的行為。 |
| [getCount()](#getCount--) | 返回集合中行為的數量。 |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | 將新行為新增至集合。 |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | 確定 List 中特定項目的索引。 |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | 在指定索引處將新行為插入集合。 |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | 從集合中移除指定的行為。 |
| [removeAt(int index)](#removeAt-int-) | 在指定索引處從集合中移除行為。 |
| [clear()](#clear--) | 從集合中移除所有行為。 |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | 判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```

返回指定索引處的行為。

**參數：**
| 參數 | Type | 說明 |
| --- | --- | --- |
| index | int | 要返回的行為之索引。 |

**返回值：**
[IBehavior](../../com.aspose.slides/ibehavior) - 動畫行為。
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```

返回指定索引處的行為。

**參數：**
| 參數 | Type | 說明 |
| --- | --- | --- |
| index | int | 要返回的行為之索引。 |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```

返回集合中行為的數量。唯讀 int。

**返回值：**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```

將新行為新增至集合。

**參數：**
| 參數 | Type | 說明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要新增的行為。 |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```

確定 List 中特定項目的索引。

**參數：**
| 參數 | Type | 說明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要在 List 中定位的物件。 |

**返回值：**
int - 若在列表中找到項目則返回其索引；否則返回 -1。
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```

在指定索引處將新行為插入集合。

**參數：**
| 參數 | Type | 說明 |
| --- | --- | --- |
| index | int | 新行為應插入的索引。 |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要插入的行為。 |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```

從集合中移除指定的行為。

**參數：**
| 參數 | Type | 說明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要移除的行為。 |

**返回值：**
boolean - 若成功移除行為則返回 true boolean
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

在指定索引處從集合中移除行為。

**參數：**
| 參數 | Type | 說明 |
| --- | --- | --- |
| index | int | 要移除的行為之索引。 |

### clear() {#clear--}
```
public abstract void clear()
```

從集合中移除所有行為。

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```

判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**參數：**
| 參數 | Type | 說明 |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的物件。 |

**返回值：**
boolean - 若在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到項目則返回 true；否則返回 false.