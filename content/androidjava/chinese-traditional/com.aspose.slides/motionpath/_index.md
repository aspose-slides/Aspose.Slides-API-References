---
title: MotionPath
second_title: Aspose.Slides for Android via Java API 參考
description: 表示運動路徑。
type: docs
url: /zh-hant/com.aspose.slides/motionpath/
---
**繼承:**
java.lang.Object

**所有已實作的介面:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

表示運動路徑。

## 建構子

| 建構子 | 說明 |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## 方法

| 方法 | 說明 |
| --- | --- |
| [add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#add-int-android.graphics.PointF---int-boolean-) | 將新指令新增至路徑 |
| [getCount()](#getCount--) | 傳回集合中路徑的數量。 |
| [insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-android.graphics.PointF---int-boolean-) | 將新指令插入至路徑 |
| [clear()](#clear--) | 從集合中移除所有指令 |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | 從集合中移除指定的指令 |
| [removeAt(int index)](#removeAt-int-) | 移除指定索引處的指令 |
| [get_Item(int index)](#get-Item-int-) | 傳回指定索引處的指令 |
| [iterator()](#iterator--) | 傳回用於遍歷集合的列舉器 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器 |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#add-int-android.graphics.PointF---int-boolean-}
```
public final IMotionCmdPath add(int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Add new command to path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | 點陣列 |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 相對座標 boolean |

**Returns:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


Returns the number of paths in the collection. Read-only int.

**Returns:**
int
### insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-android.graphics.PointF---int-boolean-}
```
public final void insert(int index, int type, PointF[] pts, int ptsType, boolean bRelativeCoord)
```


Insert new command to path

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 零基索引，用於指定要插入項目的位置。 |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | android.graphics.PointF[] | 點陣列 |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 相對座標 boolean |

### clear() {#clear--}
```
public final void clear()
```


Removes all commands from the collection.

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


Removes specified commans from the collection.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | 要移除的運動路徑。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Removes a command at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 應刪除之指令的索引。 |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


Returns a command at the specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | 元素的索引。 |

**Returns:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - 此 [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) 物件。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


Returns an enumerator that iterates through the collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - 可用於遍歷集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


Returns a java iterator for the entire collection.

**Returns:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - 整個集合的 java.util.Iterator。