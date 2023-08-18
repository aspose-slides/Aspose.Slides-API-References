---
title: IGradientStopCollection
second_title: Aspose.Slides for Android via Java API Reference
description: Represnts a collection of gradient stops.
type: docs
weight: 811
url: /com.aspose.slides/igradientstopcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IGradientStopCollection extends IGenericCollection<IGradientStop>
```

Represnts a collection of gradient stops.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the gradient stop by index. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Creates the new gradient stop and adds it to the end of collection. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Creates the new gradient stop and adds it to the end of collection. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Creates the new gradient stop and adds it to the end of collection. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Creates the new gradient stop and inserts it at the specified index to the collection. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Creates the new gradient stop and inserts it at the specified index to the collection. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Creates the new gradient stop and inserts it at the specified index to the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a gradient stop at the specified index. |
| [clear()](#clear--) | Removes all gradient stops from a collection. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IGradientStop get_Item(int index)
```


Returns the gradient stop by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public abstract IGradientStop add(float position, Integer color)
```


Creates the new gradient stop and adds it to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | Position of the new gradient stop. |
| color | java.lang.Integer | Color of the new gradient stop. |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index of the new gradient stop in the collection.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public abstract IGradientStop addPresetColor(float position, int presetColor)
```


Creates the new gradient stop and adds it to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | Position of the new gradient stop. |
| presetColor | int | Color of the new gradient stop. |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index of the new gradient stop in the collection.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public abstract IGradientStop addSchemeColor(float position, int schemeColor)
```


Creates the new gradient stop and adds it to the end of collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| position | float | Position of the new gradient stop. |
| schemeColor | int | Color of the new gradient stop. |

**Returns:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Index of the new gradient stop in the collection.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public abstract void insert(int index, float position, Integer color)
```


Creates the new gradient stop and inserts it at the specified index to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index in the collection where new gradient stop will be inserted. |
| position | float | Position of the new gradient stop. |
| color | java.lang.Integer | Color of the new gradient stop. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public abstract void insertPresetColor(int index, float position, int presetColor)
```


Creates the new gradient stop and inserts it at the specified index to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index in the collection where new gradient stop will be inserted. |
| position | float | Position of the new gradient stop. |
| presetColor | int | Color of the new gradient stop. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public abstract void insertSchemeColor(int index, float position, int schemeColor)
```


Creates the new gradient stop and inserts it at the specified index to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index in the collection where new gradient stop will be inserted. |
| position | float | Position of the new gradient stop. |
| schemeColor | int | Color of the new gradient stop. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes a gradient stop at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a gradient stop that should be deleted. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all gradient stops from a collection.

