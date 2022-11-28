---
title: IBehaviorPropertyCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents timing properties for the effect behavior.
type: docs
weight: 667
url: /androidjava/com.aspose.slides/ibehaviorpropertycollection/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericList
```
public interface IBehaviorPropertyCollection extends System.Collections.Generic.IGenericList<IBehaviorProperty>
```

Represents timing properties for the effect behavior.
## Methods

| Method | Description |
| --- | --- |
| [add(String propertyValue)](#add-java.lang.String-) | Adds a new property to the collection. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Determines the index of a specific item by property value in the List. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Inserts a new property (with the specified property value) to the collection at the specified index. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Removes specified property from the collection. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value. |
### add(String propertyValue) {#add-java.lang.String-}
```
public abstract void add(String propertyValue)
```


Adds a new property to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Value of the property to add. |

### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public abstract int indexOf(String propertyValue)
```


Determines the index of a specific item by property value in the List.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | value of the property |

**Returns:**
int - The index of the property with the specified value
### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public abstract void insert(int index, String propertyValue)
```


Inserts a new property (with the specified property value) to the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index where a new property should be inserted. |
| propertyValue | java.lang.String | Value of the property to add. |

### remove(String propertyValue) {#remove-java.lang.String-}
```
public abstract boolean remove(String propertyValue)
```


Removes specified property from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Value of the property to remove. |

**Returns:**
boolean - True if a property removed successfully boolean
### contains(String propertyValue) {#contains-java.lang.String-}
```
public abstract boolean contains(String propertyValue)
```


Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Value of the property to locate in the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true if propertyValue is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
