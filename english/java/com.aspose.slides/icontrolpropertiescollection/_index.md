---
title: IControlPropertiesCollection
second_title: Aspose.Slides for Java API Reference
description: A collection of ActiveX controls.
type: docs
weight: 732
url: /java/com.aspose.slides/icontrolpropertiescollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IControlPropertiesCollection extends System.Collections.Generic.IGenericEnumerable<System.Collections.Generic.KeyValuePair<String,String>>
```

A collection of ActiveX controls.
## Methods

| Method | Description |
| --- | --- |
| [getCount()](#getCount--) | Returns a number of properties in the collection. |
| [add(String name, String value)](#add-java.lang.String-java.lang.String-) | Adds a property to the collection. |
| [remove(String name)](#remove-java.lang.String-) | Removes a property with the specified name. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Returns or sets property. |
| [set_Item(String name, String value)](#set-Item-java.lang.String-java.lang.String-) | Returns or sets property. |
| [getNamesOfProperties()](#getNamesOfProperties--) | Returns a number of properties in the collection. |
| [clear()](#clear--) | Removes all properties. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Returns a number of properties in the collection. Read-only int.

**Returns:**
int
### add(String name, String value) {#add-java.lang.String-java.lang.String-}
```
public abstract void add(String name, String value)
```


Adds a property to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of the property. |
| value | java.lang.String | The alue of the property. |

### remove(String name) {#remove-java.lang.String-}
```
public abstract void remove(String name)
```


Removes a property with the specified name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | The name of property to remove. |

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract String get_Item(String name)
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
public abstract void set_Item(String name, String value)
```


Returns or sets property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of property. |
| value | java.lang.String |  |

### getNamesOfProperties() {#getNamesOfProperties--}
```
public abstract System.Collections.Generic.IGenericCollection<String> getNamesOfProperties()
```


Returns a number of properties in the collection. Read-only [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Returns:**
[IGenericCollection](../../com.aspose.ms.system.collections.generic/igenericcollection)
### clear() {#clear--}
```
public abstract void clear()
```


Removes all properties.

