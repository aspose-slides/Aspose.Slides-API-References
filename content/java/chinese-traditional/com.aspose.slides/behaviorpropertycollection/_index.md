---
title: BehaviorPropertyCollection
second_title: Aspose.Slides for Java API 參考
description: 表示效果行為的時間屬性。
type: docs
url: /zh-hant/com.aspose.slides/behaviorpropertycollection/
---
**繼承關係:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

表示效果行為的時間屬性。

## 方法

| Method | Description |
| --- | --- |
| [size()](#size--) | 返回集合中儲存的屬性數量。 |
| [isReadOnly()](#isReadOnly--) | 取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否為唯讀的值。 |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | 將新屬性新增至集合中。 |
| [add(String propertyValue)](#add-java.lang.String-) | 將新屬性新增至集合中。 |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | 確定 List 中特定項目的索引。 |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | 依屬性值確定 List 中特定項目的索引。 |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | 在指定索引處將新屬性插入集合。 |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | 在指定索引處將新屬性（具有指定的屬性值）插入集合。 |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | 將 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素複製到陣列，從特定的陣列索引開始。 |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | 從集合中移除指定的屬性。 |
| [remove(String propertyValue)](#remove-java.lang.String-) | 從集合中移除指定的屬性。 |
| [removeAt(int index)](#removeAt-int-) | 從指定索引處移除屬性。 |
| [clear()](#clear--) | 從集合中移除所有屬性。 |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | 判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [contains(String propertyValue)](#contains-java.lang.String-) | 判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引處的屬性。 |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | 在指定索引處設定屬性。 |
| [iterator()](#iterator--) | 返回一個遍歷集合的列舉器。 |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |

### size() {#size--}
```
public final int size()
```

返回集合中儲存的屬性數量。只讀 int。

**回傳:**  
int

### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```

取得指示 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否為唯讀的值。只讀 boolean。

**回傳:**  
boolean - true if the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only; otherwise, false.

### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```

將新屬性新增至集合中。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 要新增的屬性。 |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```

將新屬性新增至集合中。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | 要新增的屬性值。 |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```

確定 List 中特定項目的索引。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 要在 List 中定位的物件。 |

**回傳:**  
int - 如果在列表中找到項目則返回其索引；若未找到則返回 -1。

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```

依屬性值確定 List 中特定項目的索引。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | 屬性值 |

**回傳:**  
int - 具有指定值的屬性的索引

### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```

在指定索引處將新屬性插入集合。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 應插入新屬性的索引位置。 |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 要新增的屬性。 |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```

在指定索引處將新屬性（具有指定的屬性值）插入集合。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 應插入新屬性的索引位置。 |
| propertyValue | java.lang.String | 要新增的屬性值。 |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```

將 [IGenericCollection](../../com.aspose.slides/igenericcollection) 的元素複製到陣列，從特定的陣列索引開始。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | 從 [IGenericCollection](../../com.aspose.slides/igenericcollection) 複製元素的目的地一維陣列。此陣列必須使用零基索引。 |
| arrayIndex | int | 複製開始的零基索引位置。 |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```

從集合中移除指定的屬性。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 要移除的屬性。 |

**回傳:**  
boolean

### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```

從集合中移除指定的屬性。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | 要移除的屬性值。 |

**回傳:**  
boolean

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

從指定索引處移除屬性。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 應刪除的屬性索引。 |

### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有屬性。

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```

判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的屬性。 |

**回傳:**  
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到 item 則返回 true；否則返回 false。

### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```

判斷 [IGenericCollection](../../com.aspose.slides/igenericcollection) 是否包含特定值。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | 要在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中定位的屬性值。 |

**回傳:**  
boolean - 如果在 [IGenericCollection](../../com.aspose.slides/igenericcollection) 中找到 propertyValue 則返回 true；否則返回 false。

### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```

返回指定索引處的屬性。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要返回的屬性索引。 |

**回傳:**  
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - 動畫行為屬性。

### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```

在指定索引處設定屬性。

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要返回的屬性索引。 |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```

返回一個遍歷集合的列舉器。

**回傳:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - 可用於遍歷集合的 IGenericEnumerator。

### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**回傳:**  
int

### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**回傳:**  
boolean

### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```

**參數:**  
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**回傳:**  
boolean

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```

返回整個集合的 java 迭代器。

**回傳:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - 整個集合的 java.util.Iterator。