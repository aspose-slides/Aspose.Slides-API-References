---
title: MotionPath
second_title: Aspose.Sildes 用于 PHP 的 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/motionpath/
---
## MotionPath 类

表示运动路径。

### MotionPath {#MotionPath}

| 名称 | 描述 |
| --- | --- |
| MotionPath() |  |

**返回：**
MotionPath


---


### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (int, java.awt.geom.Point2D.Float[], int, boolean) | 向路径添加新命令 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| type | int | MotionCommandPathType |
| pts | java.awt.geom.Point2D.Float[] | 点的数组 |
| ptsType | int | MotionPathPointsType |
| bRelativeCoord | boolean | 相对坐标布尔值 |

**返回：**
[MotionCmdPath](../motioncmdpath)


---


### clear {#clear}

| 名称 | 描述 |
| --- | --- |
| clear () | 从集合中移除所有命令。 |

**返回：**
void


---


### getCount {#getCount}

| 名称 | 描述 |
| --- | --- |
| getCount () | 返回集合中路径的数量。只读 int。 |

**返回：**
int


---


### get_Item {#get_Item}

| 名称 | 描述 |
| --- | --- |
| get_Item (int) | 返回指定索引处的命令。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 元素的索引。 |

**返回：**
[MotionCmdPath](../motioncmdpath)


---


### insert {#insert}

| 名称 | 描述 |
| --- | --- |
| insert (int, int, java.awt.geom.Point2D.Float[], int, boolean) | 向路径插入新命令 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 插入项的零基索引。 |
| type | int | MotionCommandPathType |
| pts | java.awt.geom.Point2D.Float[] | 点的数组 |
| ptsType | int | MotionPathPointsType |
| bRelativeCoord | boolean | 相对坐标布尔值 |

**返回：**
void


---


### iterator {#iterator}

| 名称 | 描述 |
| --- | --- |
| iterator () | 返回一个遍历集合的枚举器。 |

**返回：**



---


### iteratorJava {#iteratorJava}

| 名称 | 描述 |
| --- | --- |
| iteratorJava () | 返回整个集合的 java 迭代器。 |

**返回：**



---


### remove {#remove}

| 名称 | 描述 |
| --- | --- |
| remove ([MotionCmdPath](../motioncmdpath)) | 从集合中移除指定的命令。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| item | [MotionCmdPath](../motioncmdpath) | 要移除的运动路径。 |

**返回：**
void


---


### removeAt {#removeAt}

| 名称 | 描述 |
| --- | --- |
| removeAt (int) | 移除指定索引处的命令。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 应删除的命令的索引。 |

**返回：**
void


---