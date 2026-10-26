---
title: IMotionPath
second_title: Aspose.Slides Java API 参考
description: 表示运动路径。
type: docs
url: /zh/com.aspose.slides/imotionpath/
---
**已实现的接口:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IMotionPath extends System.Collections.Generic.IGenericEnumerable<IMotionCmdPath>
```

表示运动路径。
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | 向路径添加新命令 |
| [getCount()](#getCount--) | 返回集合中路径的数量。 |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | 向路径插入新命令 |
| [clear()](#clear--) | 删除集合中的所有命令。 |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | 删除集合中指定的命令。 |
| [removeAt(int index)](#removeAt-int-) | 删除指定索引处的命令。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的命令。 |
### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

向路径添加新命令

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | 动画运动效果行为的命令类型 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | 点数组 java.awt.geom.Point2D.Float[] |
| ptsType | int | 动画运动路径中点的类型 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 指示是否使用相对坐标 boolean |

**返回：**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - 路径的命令 [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public abstract int getCount()
```

返回集合中路径的数量。只读 int。

**返回：**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public abstract void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```

向路径插入新命令

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 用于插入命令的索引 int |
| type | int | 动画运动效果行为的命令类型 [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | 点数组 java.awt.geom.Point2D.Float[] |
| ptsType | int | 动画运动路径中点的类型 [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 指示是否使用相对坐标 boolean |

### clear() {#clear--}
```
public abstract void clear()
```

删除集合中的所有命令。

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public abstract void remove(IMotionCmdPath item)
```

删除集合中指定的命令

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | 要删除的运动路径 [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

删除指定索引处的命令

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 用于删除命令的索引 int |

### get_Item(int index) {#get-Item-int-}
```
public abstract IMotionCmdPath get_Item(int index)
```

返回指定索引处的命令

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**返回：**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - 指定索引处的命令 [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)