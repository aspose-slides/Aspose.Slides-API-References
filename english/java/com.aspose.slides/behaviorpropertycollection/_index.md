---
title: BehaviorPropertyCollection
second_title: Aspose.Slides for Java API Reference
description: Represents timing properties for the effect behavior.
type: docs
weight: 54
url: /java/com.aspose.slides/behaviorpropertycollection/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
```
public class BehaviorPropertyCollection implements IBehaviorPropertyCollection
```

Represents timing properties for the effect behavior.
## Methods

| Method | Description |
| --- | --- |
| [size()](#size--) | Returns the number of properties stored in the collection. |
| [isReadOnly()](#isReadOnly--) | Gets a value indicating whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only. |
| [add(IBehaviorProperty item)](#add-com.aspose.slides.IBehaviorProperty-) | Adds a new property to the collection. |
| [add(String propertyValue)](#add-java.lang.String-) | Adds a new property to the collection. |
| [indexOf(IBehaviorProperty item)](#indexOf-com.aspose.slides.IBehaviorProperty-) | Determines the index of a specific item in the List. |
| [indexOf(String propertyValue)](#indexOf-java.lang.String-) | Determines the index of a specific item by property value in the List. |
| [insert(int index, IBehaviorProperty item)](#insert-int-com.aspose.slides.IBehaviorProperty-) | Inserts a new property to the collection at the specified index. |
| [insert(int index, String propertyValue)](#insert-int-java.lang.String-) | Inserts a new property (with the specified property value) to the collection at the specified index. |
| [copyTo(IBehaviorProperty[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehaviorProperty---int-) | Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index. |
| [remove(IBehaviorProperty item)](#remove-com.aspose.slides.IBehaviorProperty-) | Removes specified property from the collection. |
| [remove(String propertyValue)](#remove-java.lang.String-) | Removes specified property from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes property at the specified index. |
| [clear()](#clear--) | Removes all properties from the collection. |
| [contains(IBehaviorProperty item)](#contains-com.aspose.slides.IBehaviorProperty-) | Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value. |
| [contains(String propertyValue)](#contains-java.lang.String-) | Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value. |
| [get_Item(int index)](#get-Item-int-) | Returns a property at the specified index. |
| [set_Item(int index, IBehaviorProperty value)](#set-Item-int-com.aspose.slides.IBehaviorProperty-) | Sets a property at the specified index. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [indexOfItem(IBehaviorProperty item)](#indexOfItem-com.aspose.slides.IBehaviorProperty-) |  |
| [insertItem(int index, IBehaviorProperty item)](#insertItem-int-com.aspose.slides.IBehaviorProperty-) |  |
| [addItem(IBehaviorProperty item)](#addItem-com.aspose.slides.IBehaviorProperty-) |  |
| [containsItem(IBehaviorProperty item)](#containsItem-com.aspose.slides.IBehaviorProperty-) |  |
| [copyToTArray(IBehaviorProperty[] array, int arrayIndex)](#copyToTArray-com.aspose.slides.IBehaviorProperty---int-) |  |
| [removeItem(IBehaviorProperty item)](#removeItem-com.aspose.slides.IBehaviorProperty-) |  |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
### size() {#size--}
```
public final int size()
```


Returns the number of properties stored in the collection. Read-only int.

**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Gets a value indicating whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only. Read-only boolean.

**Returns:**
boolean - true if the [IGenericCollection](../../com.aspose.slides/igenericcollection) is read-only; otherwise, false.
### add(IBehaviorProperty item) {#add-com.aspose.slides.IBehaviorProperty-}
```
public final void add(IBehaviorProperty item)
```


Adds a new property to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Property to add. |

### add(String propertyValue) {#add-java.lang.String-}
```
public final void add(String propertyValue)
```


Adds a new property to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Value of the property to add. |

### indexOf(IBehaviorProperty item) {#indexOf-com.aspose.slides.IBehaviorProperty-}
```
public final int indexOf(IBehaviorProperty item)
```


Determines the index of a specific item in the List.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | The object to locate in the List. |

**Returns:**
int - The index of item if found in the list; otherwise, -1.
### indexOf(String propertyValue) {#indexOf-java.lang.String-}
```
public final int indexOf(String propertyValue)
```


Determines the index of a specific item by property value in the List.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | value of the property |

**Returns:**
int - The index of the property with the specified value
### insert(int index, IBehaviorProperty item) {#insert-int-com.aspose.slides.IBehaviorProperty-}
```
public final void insert(int index, IBehaviorProperty item)
```


Inserts a new property to the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index where a new property should be inserted. |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Property to add. |

### insert(int index, String propertyValue) {#insert-int-java.lang.String-}
```
public final void insert(int index, String propertyValue)
```


Inserts a new property (with the specified property value) to the collection at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index where a new property should be inserted. |
| propertyValue | java.lang.String | Value of the property to add. |

### copyTo(IBehaviorProperty[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehaviorProperty---int-}
```
public final void copyTo(IBehaviorProperty[] array, int arrayIndex)
```


Copies the elements of the [IGenericCollection](../../com.aspose.slides/igenericcollection) to an Array, starting at a particular Array index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) | The one-dimensional Array that is the destination of the elements copied from [IGenericCollection](../../com.aspose.slides/igenericcollection). The Array must have zero-based indexing. |
| arrayIndex | int | The zero-based index in array at which copying begins. |

### remove(IBehaviorProperty item) {#remove-com.aspose.slides.IBehaviorProperty-}
```
public final boolean remove(IBehaviorProperty item)
```


Removes specified property from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | Property to remove. |

**Returns:**
boolean
### remove(String propertyValue) {#remove-java.lang.String-}
```
public final boolean remove(String propertyValue)
```


Removes specified property from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Value of the property to remove. |

**Returns:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes property at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the property which should be deleted. |

### clear() {#clear--}
```
public final void clear()
```


Removes all properties from the collection.

### contains(IBehaviorProperty item) {#contains-com.aspose.slides.IBehaviorProperty-}
```
public final boolean contains(IBehaviorProperty item)
```


Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) | The property to locate in the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true if item is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
### contains(String propertyValue) {#contains-java.lang.String-}
```
public final boolean contains(String propertyValue)
```


Determines whether the [IGenericCollection](../../com.aspose.slides/igenericcollection) contains a specific value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| propertyValue | java.lang.String | Value of the property to locate in the [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Returns:**
boolean - true if propertyValue is found in the [IGenericCollection](../../com.aspose.slides/igenericcollection); otherwise, false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehaviorProperty get_Item(int index)
```


Returns a property at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a property to return. |

**Returns:**
[IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) - Animation behavior property.
### set_Item(int index, IBehaviorProperty value) {#set-Item-int-com.aspose.slides.IBehaviorProperty-}
```
public final void set_Item(int index, IBehaviorProperty value)
```


Sets a property at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a property to return. |
| value | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - A IGenericEnumerator that can be used to iterate through the collection.
### indexOfItem(IBehaviorProperty item) {#indexOfItem-com.aspose.slides.IBehaviorProperty-}
```
public int indexOfItem(IBehaviorProperty item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Returns:**
int
### insertItem(int index, IBehaviorProperty item) {#insertItem-int-com.aspose.slides.IBehaviorProperty-}
```
public void insertItem(int index, IBehaviorProperty item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### addItem(IBehaviorProperty item) {#addItem-com.aspose.slides.IBehaviorProperty-}
```
public void addItem(IBehaviorProperty item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

### containsItem(IBehaviorProperty item) {#containsItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean containsItem(IBehaviorProperty item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Returns:**
boolean
### copyToTArray(IBehaviorProperty[] array, int arrayIndex) {#copyToTArray-com.aspose.slides.IBehaviorProperty---int-}
```
public void copyToTArray(IBehaviorProperty[] array, int arrayIndex)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [IBehaviorProperty\[\]](../../com.aspose.slides/ibehaviorproperty) |  |
| arrayIndex | int |  |

### removeItem(IBehaviorProperty item) {#removeItem-com.aspose.slides.IBehaviorProperty-}
```
public boolean removeItem(IBehaviorProperty item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IBehaviorProperty](../../com.aspose.slides/ibehaviorproperty) |  |

**Returns:**
boolean
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehaviorProperty> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehaviorProperty> - An java.util.Iterator for the entire collection.
