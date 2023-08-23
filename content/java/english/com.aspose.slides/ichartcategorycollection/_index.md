---
title: IChartCategoryCollection
second_title: Aspose.Slides for Java API Reference
description: Represents collection of
type: docs
url: /com.aspose.slides/ichartcategorycollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IChartCategoryCollection extends IGenericCollection<IChartCategory>
```

Represents collection of [IChartCategory](../../com.aspose.slides/ichartcategory)
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getUseCells()](#getUseCells--) | If true then worksheet is used for storing categories (this case supports a multi-level categories). |
| [setUseCells(boolean value)](#setUseCells-boolean-) | If true then worksheet is used for storing categories (this case supports a multi-level categories). |
| [getGroupingLevelCount()](#getGroupingLevelCount--) | Returns count of category grouping levels used. |
| [add(IChartDataCell chartDataCell)](#add-com.aspose.slides.IChartDataCell-) | If category exists in collection, return it. |
| [add(Object value)](#add-java.lang.Object-) | Creates new [IChartCategory](../../com.aspose.slides/ichartcategory) from value and adds it to the collection. |
| [indexOf(IChartCategory value)](#indexOf-com.aspose.slides.IChartCategory-) | Searches for the specified [IChartCategory](../../com.aspose.slides/ichartcategory) and returns the zero-based index of the first occurrence within the entire Collection |
| [remove(IChartCategory value)](#remove-com.aspose.slides.IChartCategory-) | Removes the specified value. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the given index. |
| [clear()](#clear--) | Removes all elements from the collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartCategory get_Item(int index)
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
public abstract boolean getUseCells()
```


If true then worksheet is used for storing categories (this case supports a multi-level categories). If false then worksheet is NOT used for storing values (and this case doesn't support a multi-level categories). Read/write boolean.

**Returns:**
boolean
### setUseCells(boolean value) {#setUseCells-boolean-}
```
public abstract void setUseCells(boolean value)
```


If true then worksheet is used for storing categories (this case supports a multi-level categories). If false then worksheet is NOT used for storing values (and this case doesn't support a multi-level categories). Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getGroupingLevelCount() {#getGroupingLevelCount--}
```
public abstract int getGroupingLevelCount()
```


Returns count of category grouping levels used. Is more then one for multilevel categories. Read-only int.

**Returns:**
int
### add(IChartDataCell chartDataCell) {#add-com.aspose.slides.IChartDataCell-}
```
public abstract IChartCategory add(IChartDataCell chartDataCell)
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
public abstract IChartCategory add(Object value)
```


Creates new [IChartCategory](../../com.aspose.slides/ichartcategory) from value and adds it to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object | The value.

--------------------

This method adds worksheet with name AUTO\_DATA and adds all values there. If you use [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook) to add or edit cell values, be sure that you do not use this worksheet Maximum number of values added using this method must not exceed 16711680 |

**Returns:**
[IChartCategory](../../com.aspose.slides/ichartcategory) - Added [IChartCategory](../../com.aspose.slides/ichartcategory).
### indexOf(IChartCategory value) {#indexOf-com.aspose.slides.IChartCategory-}
```
public abstract int indexOf(IChartCategory value)
```


Searches for the specified [IChartCategory](../../com.aspose.slides/ichartcategory) and returns the zero-based index of the first occurrence within the entire Collection

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | Chart category. |

**Returns:**
int - The zero-based index of the first occurrence of value within the entire CollectionBase, if found; otherwise, -1.
### remove(IChartCategory value) {#remove-com.aspose.slides.IChartCategory-}
```
public abstract void remove(IChartCategory value)
```


Removes the specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartCategory](../../com.aspose.slides/ichartcategory) | The value. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the element at the given index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a category to remove. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all elements from the collection.

