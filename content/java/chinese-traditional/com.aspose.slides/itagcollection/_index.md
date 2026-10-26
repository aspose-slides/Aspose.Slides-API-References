---
title: ITagCollection
second_title: Aspose.Slides for Java API 參考文件
description: 表示標籤的集合（使用者自訂的字串對）
type: docs
url: /zh-hant/com.aspose.slides/itagcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ITagCollection extends IGenericCollection<System.Collections.Generic.KeyValuePair<String,String>>
```

Represents the collection of tags (user defined pairs of strings)
## 方法

| 方法 | 說明 |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 將新標籤新增至集合中。 |
| [remove(String name)](#remove-java.lang.String-) | 從集合中移除具有指定名稱的標籤。 |
| [indexOfName(String name)](#indexOfName-java.lang.String-) | 傳回集合中指定鍵的零基索引。 |
| [contains(String name)](#contains-java.lang.String-) | 判斷集合是否包含特定名稱。 |
| [removeAt(int index)](#removeAt-int-) | 移除位於指定索引的標籤。 |
| [clear()](#clear--) | 從集合中移除所有標籤。 |
| [getValueByIndex(int index)](#getValueByIndex-int-) | 傳回位於指定索引的標籤的值。 |
| [getNameByIndex(int index)](#getNameByIndex-int-) | 傳回位於指定索引的標籤的鍵。 |
| [getNamesOfTags()](#getNamesOfTags--) | 傳回標籤的名稱。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 取得或設定標籤的鍵和值組合。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | 取得或設定標籤的鍵和值組合。 |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract int add(String name, String value)
```

Adds a new tag to collection.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 標籤的名稱。 |
| value | java.lang.String | 標籤的值。 |

**回傳值：**
int - 新增標籤的索引。
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

Removes the tag with a specified name from the collection.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要移除的標籤之名稱。 |
### indexOfName(String name) {#indexOfName-java.lang.String-}
```
public abstract int indexOfName(String name)
```

Returns the zero-based index of the specified key in the collection.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要在集合中定位的名稱。 |

**回傳值：**
int - 鍵的零基索引；如果在集合中找到鍵，則回傳該索引；否則回傳 -1。
### contains(String name) {#contains-java.lang.String-}
```
public abstract boolean contains(String name)
```

Determines whether the collection contains a specific name.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要定位的鍵。 |

**回傳值：**
boolean - 若集合包含具有指定鍵的標籤則為 true；否則為 false。
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Removes the tag at the specified index.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除的標籤之零基索引。 |
### clear() {#clear--}
```
public abstract void clear()
```

Removes all tags from the collection.
### getValueByIndex(int index) {#getValueByIndex-int-}
```
public abstract String getValueByIndex(int index)
```

Returns value of a tag at the specified index.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要回傳之標籤的索引。 |

**回傳值：**
java.lang.String - 標籤的值。
### getNameByIndex(int index) {#getNameByIndex-int-}
```
public abstract String getNameByIndex(int index)
```

Returns key of a tag at the specified index.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要回傳之標籤的索引。 |

**回傳值：**
java.lang.String - 標籤的鍵。
### getNamesOfTags() {#getNamesOfTags--}
```
public abstract String[] getNamesOfTags()
```

Returns names of tags.

**回傳值：**
java.lang.String[] - 標籤的名稱。
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

Returns or sets a key and a value pair of a tag.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 標籤的鍵。 |

**回傳值：**
java.lang.String - 標籤的值。
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

Returns or sets a key and a value pair of a tag.

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 標籤的鍵。 |
| value | java.lang.String |  |