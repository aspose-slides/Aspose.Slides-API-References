---
title: MotionPath
second_title: Aspose.Slides for Java API 參考文件
description: 表示運動路徑。
type: docs
url: /zh-hant/com.aspose.slides/motionpath/
---
**繼承：**
java.lang.Object

**所有實作的介面：**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

表示運動路徑。

## 建構函式

| 建構子 | 說明 |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |

## 方法

| 方法 | 說明 |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | 將新指令新增到路徑 |
| [getCount()](#getCount--) | 傳回集合中路徑的數量。 |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | 將新指令插入路徑 |
| [clear()](#clear--) | 從集合中移除所有指令。 |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | 從集合中移除指定的指令。 |
| [removeAt(int index)](#removeAt-int-) | 在指定索引處移除指令。 |
| [get_Item(int index)](#get-Item-int-) | 在指定索引處傳回指令。 |
| [iterator()](#iterator--) | 傳回可遍歷集合的列舉器。 |
| [iteratorJava()](#iteratorJava--) | 傳回整個集合的 java 迭代器。 |

### MotionPath() {#MotionPath--}
```
public MotionPath()
```

### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

將新指令新增到路徑

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | 點陣列 |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 相對坐標布林值 |

**傳回值：**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)

### getCount() {#getCount--}
```
public final int getCount()
```

傳回集合中路徑的數量。唯讀 int。

**傳回值：**
int

### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

將新指令插入路徑

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 零基索引，指定項目應插入的位置。 |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | 點陣列 |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 相對坐標布林值 |

### clear() {#clear--}
```
public final void clear()
```

從集合中移除所有指令。

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```

從集合中移除指定的指令。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | 要移除的運動路徑。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

在指定索引處移除指令。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 應刪除的指令索引。 |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```

在指定索引處傳回指令。

**參數：**
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**傳回值：**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) 物件。

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```

傳回可遍歷集合的列舉器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - 可用於遍歷集合的 IGenericEnumerator。

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```

傳回整個集合的 java 迭代器。

**傳回值：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - 整個集合的 java.util.Iterator。