---
title: ITagCollection
second_title: Aspose.Slides for Android via Java API 參考文件
description: 表示使用者自訂字串對的標籤集合
type: docs
url: /zh-hant/com.aspose.slides/itagcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

表示標籤集合（使用者自訂的字串對）
## Methods

| Method | Description |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 將新標籤新增至集合。 |
| [remove(String name)](#remove-java.lang.String-) | 從集合中移除具有指定名稱的標籤。 |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | 取得指定鍵在集合中的零基索引。 |
| [contains(String name)](#contains-java.lang.String-) | 判斷集合是否包含特定名稱。 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的標籤。 |
| [clear()](#clear--) | 移除集合中所有標籤。 |
| [getValueByIndex(int index)](#getValueByIndex-int-) | 取得指定索引處標籤的值。 |
| [getNameByIndex(int index)](#getNameByIndex-int-) | 取得指定索引處標籤的鍵。 |
| [getNamesOfTags()](#getNamesOfTags--) | 取得所有標籤的名稱。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 取得或設定標籤的鍵和值。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | 取得或設定標籤的鍵和值。 |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

將新標籤新增至集合。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 標籤的名稱。 |
| value | java.lang.String | 標籤的值。 |

**Returns:**
int - 新增標籤的索引。
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

從集合中移除具有指定名稱的標籤。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 要移除的標籤名稱。 |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

取得指定鍵在集合中的零基索引。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 要在集合中定位的名稱。 |

**Returns:**
int - 鍵的零基索引；若未找到則為 -1。
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

判斷集合是否包含特定名稱。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 要定位的鍵。 |

**Returns:**
boolean - True 表示集合包含具有指定鍵的標籤；否則返回 false。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

移除指定索引處的標籤。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要移除的標籤之零基索引。 |
### clear() {#clear--}
```
public abstract void clear()
```

移除集合中所有標籤。
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

取得指定索引處標籤的值。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要取得的標籤索引。 |

**Returns:**
java.lang.String - 標籤的值。
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

取得指定索引處標籤的鍵。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 要取得的標籤索引。 |

**Returns:**
java.lang.String - 標籤的鍵。
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

取得所有標籤的名稱。

**Returns:**
java.lang.String[] - 標籤名稱陣列。
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

取得或設定標籤的鍵和值。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 標籤的鍵。 |

**Returns:**
java.lang.String - 標籤的值。
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

取得或設定標籤的鍵和值。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | 標籤的鍵。 |
| value | java.lang.String |  |