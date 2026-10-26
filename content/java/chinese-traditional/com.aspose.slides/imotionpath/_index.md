---
title: IMotionPath
second_title: Aspose.Slides for Java API 參考文件
description: 表示運動路徑。
type: docs
url: /zh-hant/com.aspose.slides/imotionpath/
---
**所有已實作的介面：**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

表示運動路徑。

## 方法

| 方法 | 說明 |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | 將新指令新增至路徑 |
| [getCount()](#getCount--) | 返回集合中路徑的數量。 |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | 將新指令插入至路徑 |
| [clear()](#clear--) | 從集合中移除所有指令。 |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | 從集合中移除指定的指令。 |
| [removeAt(int index)](#removeAt-int-) | 在指定的索引處移除指令。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引處的指令。 |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

將新指令新增至路徑

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | int | 動畫運動效果行為的指令類型 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | 點陣列 java.awt.geom.Point2D.Float[] |
| ptsType | int | 動畫運動路徑中點的類型 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 指示是否使用相對座標 boolean |

**返回：**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Command of a path [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

返回集合中路徑的數量。唯讀 int。

**返回：**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

將新指令插入至路徑

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 指令插入的索引 int |
| type | int | 動畫運動效果行為的指令類型 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | 點陣列 java.awt.geom.Point2D.Float[] |
| ptsType | int | 動畫運動路徑中點的類型 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 指示是否使用相對座標 boolean |
### clear() {#clear--}
```
public abstract void clear()
```

從集合中移除所有指令。

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

從集合中移除指定的指令

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | 要移除的運動路徑 [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

在指定的索引處移除指令

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 要移除指令的索引 int |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

返回指定索引處的指令

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**返回：**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - Command at specified index [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)