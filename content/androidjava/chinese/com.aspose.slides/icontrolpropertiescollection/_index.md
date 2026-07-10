---
title: IControlPropertiesCollection
second_title: Aspose.Slides for Android via Java API 参考
description: ActiveX 控件的集合。
type: docs
url: /zh/com.aspose.slides/icontrolpropertiescollection/
---
**所有实现的接口：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

ActiveX 控件的集合。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCount()](#getCount--) | 返回集合中属性的数量。 |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 向集合添加属性。 |
| [remove(String name)](#remove-java.lang.String-) | 删除具有指定名称的属性。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 返回或设置属性。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | 返回或设置属性。 |
| [getNamesOfProperties()](#getNamesOfProperties--) | 返回集合中属性的数量。 |
| [clear()](#clear--) | 删除所有属性。 |
### getCount() {#getCount--}
```
public abstract int getCount()
```

返回集合中属性的数量。只读 int。

**返回：**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```

向集合添加属性。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 属性的名称。 |
| value | java.lang.String | 属性的值。 |
### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```

删除具有指定名称的属性。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要删除的属性名称。 |
### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
```

返回或设置属性。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 属性的名称。 |

**返回：**
java.lang.String - 属性。
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public abstract void set_Item(String name, String value)
```

返回或设置属性。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 属性的名称。 |
| value | java.lang.String |  |
### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

返回集合中属性的数量。只读 [IGenericCollection](../../com.aspose.slides/igenericcollection)。

**返回：**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```

删除所有属性。