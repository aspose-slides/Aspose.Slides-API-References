---
title: IColorOperationCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a collection of color transform operations.
type: docs
weight: 717
url: /java/com.aspose.slides/icoloroperationcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCloneable, com.aspose.slides.IGenericCollection
```
public interface IColorOperationCollection extends IGenericCloneable<IColorOperationCollection>, IGenericCollection<IColorOperation>
```

Represents a collection of color transform operations.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns or sets the operation at the specified index. |
| [set_Item(int index, IColorOperation value)](#set-Item-int-com.aspose.slides.IColorOperation-) | Returns or sets the operation at the specified index. |
| [add(int operation, float parameter)](#add-int-float-) | Adds a new operation to the end of collection. |
| [add(int operation)](#add-int-) | Adds a new operation to the end of collection. |
| [insert(int position, int operation, float parameter)](#insert-int-int-float-) | Inserts the new operation to a collection. |
| [insert(int position, int operation)](#insert-int-int-) | Inserts the new operation to a collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the color operation from a collection. |
| [clear()](#clear--) | Removes all color operations. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColorOperation get_Item(int index)
```


Returns or sets the operation at the specified index. Read/write [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation)
### set_Item(int index, IColorOperation value) {#set-Item-int-com.aspose.slides.IColorOperation-}
```
public abstract void set_Item(int index, IColorOperation value)
```


Returns or sets the operation at the specified index. Read/write [IColorOperation](../../com.aspose.slides/icoloroperation).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |
| value | [IColorOperation](../../com.aspose.slides/icoloroperation) |  |

### add(int operation, float parameter) {#add-int-float-}
```
public abstract IColorOperation add(int operation, float parameter)
```


Adds a new operation to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | int | Operation type. |
| parameter | float | Operation's parameter. |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Added operation.
### add(int operation) {#add-int-}
```
public abstract IColorOperation add(int operation)
```


Adds a new operation to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| operation | int | Operation type. |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Added operation.
### insert(int position, int operation, float parameter) {#insert-int-int-float-}
```
public abstract IColorOperation insert(int position, int operation, float parameter)
```


Inserts the new operation to a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | The index at which the operation will be inserted. |
| operation | int | Operation type. |
| parameter | float | Operation's parameter. |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Inserted operation.
### insert(int position, int operation) {#insert-int-int-}
```
public abstract IColorOperation insert(int position, int operation)
```


Inserts the new operation to a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | int | The index at which the operation will be inserted. |
| operation | int | Operation type. |

**Returns:**
[IColorOperation](../../com.aspose.slides/icoloroperation) - Inserted operation.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes the color operation from a collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a color operation to remove. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all color operations.

