---
title: ChartCategoryCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represents collection of
type: docs
url: /com.aspose.slides/chartcategorycollection/
---
**Inheritance:**
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**
[com.aspose.slides.IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
```
public class ChartCategoryCollection extends DomObject<ChartData> implements IChartCategoryCollection
```

Represents collection of [ChartCategory](../../com.aspose.slides/chartcategory)
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getUseCells()](#getUseCells--) | If true then worksheet is used for storing categories (this case supports a multi-level categories). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | If true then worksheet is used for storing categories (this case supports a multi-level categories). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Returns count of category grouping levels used. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | If category exists in collection, return it. |
| [add(Object value)](#add-java.lang.Object-) | Creates new [ChartCategory](../../com.aspose.slides/chartcategory) from value and adds it to the collection. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Searches for the specified [ChartCategory](../../com.aspose.slides/chartcategory) and returns the zero-based index of the first occurrence within the entire Collection. |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Removes the specified value. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the given index. |
| [clear()](#clear--) | Removes all elements from the collection. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
| [size()](#size--) | Returns a number of elements int the collection. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies all elements of the collection to the specified array. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the List is synchronized (thread safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns an object that can be used to synchronize access to the collection. |
### get_Item(int index) {#get-Item-int-}
```
public final IChartCategory get_Item(int index)
```


Gets the element at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - The element at the specified index.
### getUseCells() {#getUseCells--}
```
public final boolean getUseCells()
```


If true then worksheet is used for storing categories (this case supports a multi-level categories). If false then worksheet is NOT used for storing values (and this case doesn't support a multi-level categories). Read/write boolean.

**Returns:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public final void setUseCells(boolean value)
```


If true then worksheet is used for storing categories (this case supports a multi-level categories). If false then worksheet is NOT used for storing values (and this case doesn't support a multi-level categories). Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public final int getGroupingLevelCount()
```


Returns count of category grouping levels used. Is more then one for multilevel categories. Read-only int.

**Returns:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public final IChartCategory add(IChartDataCell chartDataCell)
```


If category exists in collection, return it. Else creates new chart category from [IChartDataCell](../../com.aspose.slides/ichartdatacell) and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| chartDataCell | [IChartDataCell](../../com.aspose.slides/ichartdatacell) | Cell used to create chart category. |

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Added or existing category.
### add(Object value) {#add-java.lang.Object-}
```
public final IChartCategory add(Object value)
```


Creates new [ChartCategory](../../com.aspose.slides/chartcategory) from value and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The value.

--------------------

This method adds worksheet with name AUTO\_DATA and adds all values there. If you use [ChartDataWorkbook](../../com.aspose.slides/chartdataworkbook) to add or edit cell values, be sure that you do not use this worksheet Maximum number of values added using this method must not exceed 16711680 |

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Added [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public final int indexOf(IChartCategory value)
```


Searches for the specified [ChartCategory](../../com.aspose.slides/chartcategory) and returns the zero-based index of the first occurrence within the entire Collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Chart category. |

**Returns:**
int - The zero-based index of the first occurrence of value within the entire CollectionBase, if found; otherwise, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public final void remove(IChartCategory value)
```


Removes the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | The value. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes the element at the given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a category to remove. |

### clear() {#clear--}
```
public final void clear()
```


Removes all elements from the collection.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IChartCategory> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IChartCategory> - An java.util.Iterator for the entire collection.
### size() {#size--}
```
public final int size()
```


Returns a number of elements int the collection. Read-only int.

**Returns:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copies all elements of the collection to the specified array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Target array. |
| index | int | Starting index in the array. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Returns a value indicating whether access to the List is synchronized (thread safe). Read-only boolean.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Returns an object that can be used to synchronize access to the collection. Read-only Object.

Returns a synchronization root. Read-only Object.

**Returns:**
java.lang.Object
