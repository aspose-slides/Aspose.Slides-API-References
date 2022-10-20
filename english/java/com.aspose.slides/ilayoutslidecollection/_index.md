---
title: ILayoutSlideCollection
second_title: Aspose.Slides for Java API Reference
description: Represents a base class for collection of a layout slides.
type: docs
weight: 842
url: /java/com.aspose.slides/ilayoutslidecollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Represents a base class for collection of a layout slides.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the layout slide by index. |
| [getByType(byte type)](#getByType-byte-) | Returns the first layout slide of specified type. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Removes a layout from the collection. |
| [removeUnused()](#removeUnused--) | Removes unused layout slides (layout slides whose HasDependingSlides is false). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


Returns the layout slide by index. Read-only [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```


Returns the first layout slide of specified type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | byte | A type of layout slide to find. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) with specified type or null if no layouts found.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


Removes a layout from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | The layout slide to remove from the collection.

--------------------

1) To avoid throwing of the PptxEditException check layout's HasDependingSlides property before. 2) You can use also [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) method to simplify code. |

### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


Removes unused layout slides (layout slides whose HasDependingSlides is false).

