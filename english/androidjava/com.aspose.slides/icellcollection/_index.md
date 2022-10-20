---
title: ICellCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a collection of cells.
type: docs
weight: 676
url: /java/com.aspose.slides/icellcollection/
---
**All Implemented Interfaces:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent), com.aspose.slides.IGenericCollection
```
public interface ICellCollection extends ISlideComponent, IGenericCollection<ICell>
```

Represents a collection of cells.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns a cell by it's position. |
### get_Item(int index) {#get-Item-int-}
```
public abstract ICell get_Item(int index)
```


Returns a cell by it's position. Read-only [ICell](../../com.aspose.slides/icell).

--------------------

One CellEx object can be returned for several indexes in case cell is merged.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ICell](../../com.aspose.slides/icell)
