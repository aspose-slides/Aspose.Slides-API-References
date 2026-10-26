---
title: IControlPropertiesCollection
second_title: Aspose.Slides for Android 透過 Java API 參考
description: ActiveX 控制項的集合。
type: docs
url: /zh-hant/com.aspose.slides/icontrolpropertiescollection/
---
**所有已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

ActiveX 控制項的集合。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getCount()](#getCount--) | 傳回集合中屬性的數量。 |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 將屬性新增至集合中。 |
| [remove(String name)](#remove-java.lang.String-) | 移除具有指定名稱的屬性。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 傳回或設定屬性。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | 傳回或設定屬性。 |
| [getNamesOfProperties()](#getNamesOfProperties--) | 傳回集合中屬性的數量。 |
| [clear()](#clear--) | 移除所有屬性。 |
### getCount() {#getCount--}
```
public abstract int getCount()
```

傳回集合中屬性的數量。唯讀 int.

**返回：**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

將屬性新增至集合中。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 屬性的名稱。 |
| value | java.lang.String | 屬性的值。 |
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

移除具有指定名稱的屬性。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 要移除的屬性名稱。 |
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

傳回或設定屬性。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 屬性的名稱。 |
**返回：**
java.lang.String - 屬性。
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

傳回或設定屬性。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | java.lang.String | 屬性的名稱。 |
| value | java.lang.String |  |
### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

傳回集合中屬性的數量。唯讀 [IGenericCollection](../../com.aspose.slides/igenericcollection)。

**返回：**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```

移除所有屬性。