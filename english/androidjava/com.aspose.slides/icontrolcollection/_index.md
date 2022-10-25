---
title: IControlCollection
second_title: Aspose.Slides for Android via Java API Reference
description: A collection of ActiveX controls.
type: docs
weight: 731
url: /androidjava/com.aspose.slides/icontrolcollection/
---
**All Implemented Interfaces:**
com.aspose.slides.IGenericCollection
```
public interface IControlCollection extends IGenericCollection<IControl>
```

A collection of ActiveX controls.
## Methods

| Method | Description |
| --- | --- |
| [remove(IControl item)](#remove-com.aspose.slides.IControl-) | Removes an ActiveX control from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes an ActiveX control stored at specified position from the collection. |
| [clear()](#clear--) | Removes all controls from the collection. |
| [get_Item(int index)](#get-Item-int-) | Returns a control at the specified position. |
| [addControl(int controlType, float x, float y, float width, float height)](#addControl-int-float-float-float-float-) | Creates and adds a new control to the collection. |
### remove(IControl item) {#remove-com.aspose.slides.IControl-}
```
public abstract void remove(IControl item)
```


Removes an ActiveX control from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IControl](../../com.aspose.slides/icontrol) | A control to remove. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes an ActiveX control stored at specified position from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a control to remove. |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all controls from the collection.

### get_Item(int index) {#get-Item-int-}
```
public abstract IControl get_Item(int index)
```


Returns a control at the specified position.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of a control. |

**Returns:**
[IControl](../../com.aspose.slides/icontrol)
### addControl(int controlType, float x, float y, float width, float height) {#addControl-int-float-float-float-float-}
```
public abstract IControl addControl(int controlType, float x, float y, float width, float height)
```


Creates and adds a new control to the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| controlType | int | Type of a control to add. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |

**Returns:**
[IControl](../../com.aspose.slides/icontrol) - Created control [IControl](../../com.aspose.slides/icontrol).
