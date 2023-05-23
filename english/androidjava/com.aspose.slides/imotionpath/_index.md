---
title: IMotionPath
second_title: Aspose.Slides for Android via Java API Reference
description: Represent motion path.
type: docs
weight: 931
url: /androidjava/com.aspose.slides/imotionpath/
---
**All Implemented Interfaces:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

Represent motion path.
## Methods

| Method | Description |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | Add new command to path |
| [getCount()](#getCount--) | Returns the number of paths in the collection. |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | Insert new command to path |
| [clear()](#clear--) | Removes all commands from the collection. |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | Removes specified commans from the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes a command at the specified index. |
| [get_Item(int index)](#get-Item-int-) | Returns a command at the specified index. |
### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public abstract IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Add new command to path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Type of command for animation motion effect behavior [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Points array android.graphics.PointF[] |
| ptsType | int | Type of points in animation motion path [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Indicates whether to use relative coordinates or not boolean |

**Returns:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Command of a path [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```


Returns the number of paths in the collection. Read-only int.

**Returns:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public abstract void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Insert new command to path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index for command insertion int |
| type | int | Type of command for animation motion effect behavior [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | Points array android.graphics.PointF[] |
| ptsType | int | Type of points in animation motion path [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | Indicates whether to use relative coordinates or not boolean |

### clear() {#clear--}
```
public abstract void clear()
```


Removes all commands from the collection.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```


Removes specified commans from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | Motion path to remove [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Removes a command at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index for removing command int |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```


Returns a command at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of element. |

**Returns:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Command at specified index [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
