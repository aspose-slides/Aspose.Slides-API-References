---
title: MotionPath
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/motionpath/
---

## MotionPath class

 Represent motion path.
 
### MotionPath {#MotionPath}

| Name | Description |
| --- | --- |
| MotionPath() |  |

 **Result:**
MotionPath


---


### add {#add}

| Name | Description |
| --- | --- |
| add (int, java.awt.geom.Point2D.Float[], int, boolean) | Add new command to path |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| type | int | MotionCommandPathType |
| pts | java.awt.geom.Point2D.Float[] | Array of points |
| ptsType | int | MotionPathPointsType |
| bRelativeCoord | boolean | Relative coordinates boolean |

 **Result:**
[MotionCmdPath](../motioncmdpath)


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all commands from the collection. |


---


### getCount {#getCount}

| Name | Description |
| --- | --- |
| getCount () | Returns the number of paths in the collection. Read-only int. |

 **Result:**
int


---


### get_Item {#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Returns a command at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of element. |

 **Result:**
[MotionCmdPath](../motioncmdpath)


---


### insert {#insert}

| Name | Description |
| --- | --- |
| insert (int, int, java.awt.geom.Point2D.Float[], int, boolean) | Insert new command to path |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | The zero-based index at which item should be inserted. |
| type | int | MotionCommandPathType |
| pts | java.awt.geom.Point2D.Float[] | Array of points |
| ptsType | int | MotionPathPointsType |
| bRelativeCoord | boolean | Relative coordinates boolean |


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Result:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Result:**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([MotionCmdPath](../motioncmdpath)) | Removes specified commans from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [MotionCmdPath](../motioncmdpath) | Motion path to remove. |


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes a command at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of a command that should be deleted. |


---


