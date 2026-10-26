---
title: MotionPath
second_title: Aspose.Slides for Java API 参考
description: 表示运动路径。
type: docs
url: /zh/com.aspose.slides/motionpath/
---
**继承:**
java.lang.Object

**所有实现的接口:**
[com.aspose.slides.IMotionPath](../../com.aspose.slides/imotionpath)
```
public class MotionPath implements IMotionPath
```

表示运动路径。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [MotionPath()](#MotionPath--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#add-int-java.awt.geom.Point2D.Float---int-boolean-) | 向路径添加新命令 |
| [getCount()](#getCount--) | 返回集合中路径的数量。 |
| [insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)](#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-) | 向路径插入新命令 |
| [clear()](#clear--) | 从集合中移除所有命令。 |
| [remove(IMotionCmdPath item)](#remove-com.aspose.slides.IMotionCmdPath-) | 从集合中移除指定的命令。 |
| [removeAt(int index)](#removeAt-int-) | 在指定索引处移除命令。 |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引处的命令。 |
| [iterator()](#iterator--) | 返回遍历集合的枚举器。 |
| [iteratorJava()](#iteratorJava--) | 返回整个集合的 java 迭代器。 |
### MotionPath() {#MotionPath--}
```
public MotionPath()
```


### add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#add-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final IMotionCmdPath add(int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


向路径添加新命令

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | 点数组 |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 相对坐标布尔值 |

**返回:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath)
### getCount() {#getCount--}
```
public final int getCount()
```


返回集合中路径的数量。只读 int。

**返回:**
int
### insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord) {#insert-int-int-java.awt.geom.Point2D.Float---int-boolean-}
```
public final void insert(int index, int type, Point2D.Float[] pts, int ptsType, boolean bRelativeCoord)
```


向路径插入新命令

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要插入项的零基索引。 |
| type | int | [MotionCommandPathType](../../com.aspose.slides/motioncommandpathtype) |
| pts | java.awt.geom.Point2D.Float[] | 点数组 |
| ptsType | int | [MotionPathPointsType](../../com.aspose.slides/motionpathpointstype) |
| bRelativeCoord | boolean | 相对坐标布尔值 |

### clear() {#clear--}
```
public final void clear()
```


从集合中移除所有命令。

### remove(IMotionCmdPath item) {#remove-com.aspose.slides.IMotionCmdPath-}
```
public final void remove(IMotionCmdPath item)
```


从集合中移除指定的命令。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) | 要移除的运动路径。 |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


在指定索引处移除命令。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 要删除的命令的索引。 |

### get_Item(int index) {#get-Item-int-}
```
public final IMotionCmdPath get_Item(int index)
```


返回指定索引处的命令。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**返回:**
[IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) - [IMotionCmdPath](../../com.aspose.slides/imotioncmdpath) 对象。
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iterator()
```


返回遍历集合的枚举器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - 可用于遍历集合的 IGenericEnumerator。
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IMotionCmdPath> iteratorJava()
```


返回整个集合的 java 迭代器。

**返回:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IMotionCmdPath> - 整个集合的 java.util.Iterator。