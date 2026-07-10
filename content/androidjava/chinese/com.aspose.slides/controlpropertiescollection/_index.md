---
title: ControlPropertiesCollection
second_title: Aspose.Slides for Android via Java API 参考
description: ActiveX 属性的集合。
type: docs
url: /zh/com.aspose.slides/controlpropertiescollection/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)  
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

ActiveX属性的集合。

## 方法

| 方法 | 描述 |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | 向集合中添加属性。 |
| [remove(String name)](#remove-java.lang.String-) | 删除具有指定名称的属性。 |
| [get_Item(String name)](#get-Item-java.lang.String-) | 返回或设置属性。 |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | 返回或设置属性。 |
| [getNamesOfProperties()](#getNamesOfProperties--) | 返回属性名称的集合。 |
| [clear()](#clear--) | 删除所有属性。 |
| [getCount()](#getCount--) | 返回集合中属性的数量。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |

### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```

向集合中添加属性。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 属性的名称。 |
| value | java.lang.String | 属性的值。 |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```

删除具有指定名称的属性。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 要删除的属性的名称。 |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```

返回或设置属性。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 属性的名称。 |

**返回:**
java.lang.String - 属性。

### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```

返回或设置属性。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 属性的名称。 |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```

返回属性名称的集合。只读 [IGenericCollection](../../com.aspose.slides/igenericcollection)。

**返回:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)

### clear() {#clear--}
```
public final void clear()
```

删除所有属性。

### getCount() {#getCount--}
```
public final int getCount()
```

返回集合中属性的数量。只读 int。

**返回:**
int

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```

返回遍历集合的枚举器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - 一个可用于遍历集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```

返回整个集合的 java 迭代器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - 一个用于整个集合的 java.util.Iterator。