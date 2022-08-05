---
title: ControlPropertiesCollection
second_title: Aspose.Sildes for Java API Reference
description: p
 A collection of AcitveX properties.
type: docs
weight: 138
url: /java/com.aspose.slides/controlpropertiescollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
```
public class ControlPropertiesCollection implements IControlPropertiesCollection
```

A collection of AcitveX properties.
## Methods

| Method | Description |
| --- | --- |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Adds a property to the collection. |
| [remove(String name)](#remove-java.lang.String-) | Removes a property with the specified name. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returns or sets property. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Returns or sets property. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Returns the collection of properties names. |
| [clear()](#clear--) | Removes all properties. |
| [getCount()](#getCount--) | Returns a number of properties in the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public final void add(String name, String value)
```


Adds a property to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the property. |
| value | java.lang.String | The alue of the property. |

### remove(String name) {#remove-java.lang.String-}
```
public final void remove(String name)
```


Removes a property with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of property to remove. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public final String get_Item(String name)
```


Returns or sets property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of property. |

**Returns:**
java.lang.String - Property.
### set_Item(String name, String value) {#set-Item-java.lang.String-java.lang.String-}
```
public final void set_Item(String name, String value)
```


Returns or sets property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of property. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


Returns the collection of properties names. Read-only [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Returns:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public final void clear()
```


Removes all properties.

### getCount() {#getCount--}
```
public final int getCount()
```


Returns a number of properties in the collection. Read-only int.

**Returns:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<System.Collections.Generic.KeyValuePair<String,String>> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,java.lang.String>> - An java.util.Iterator for the entire collection.
