---
title: ControlPropertiesCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: AcitveX 屬性的集合。
type: docs
url: /zh-hant/com.aspose.slides/controlpropertiescollection/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

AcitveX 屬性的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 將屬性新增到集合中。 |
| [remove(String name)](#remove-java.lang.String-) | 移除具有指定名稱的屬性。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 取得或設定屬性。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | 取得或設定屬性。 |
| [getNamesOfProperties()](#getNamesOfProperties--) | 取得屬性名稱的集合。 |
| [clear()](#clear--) | 移除所有屬性。 |
| [getCount()](#getCount--) | 返回集合中屬性的數量。 |
| [iterator()](#iterator--) | 返回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 返回整個集合的 java 迭代器。 |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```


將屬性新增到集合中。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 屬性的名稱。 |
| value | java.lang.String | 屬性的值。 |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


移除具有指定名稱的屬性。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要移除的屬性名稱。 |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


取得或設定屬性。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 屬性名稱。 |

**返回:**
java.lang.String - Property.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


取得或設定屬性。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 屬性名稱。 |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


取得屬性名稱的集合。唯讀 [IGenericCollection](../../com.aspose.slides/igenericcollection)。

**返回:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```


移除所有屬性。

### getCount() {#getCount--}
```
public final int getCount()
```


取得集合中屬性的數量。唯讀 int。

**返回:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```


返回可遍歷集合的列舉器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```


返回整個集合的 java 迭代器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.