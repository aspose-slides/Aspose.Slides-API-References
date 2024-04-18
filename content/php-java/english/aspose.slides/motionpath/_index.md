---
title: MotionPath
second_title: Aspose.Sildes for PHP via Java API Reference
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

 **Returns:**
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

 **Returns:**
[MotionCmdPath](../motioncmdpath)


---


### clear {#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all commands from the collection. |

 **Returns:**
void


---


### getCount {#getCount}

| Name | Description |
| --- | --- |
| getCount () | Returns the number of paths in the collection. Read-only int. |

 **Returns:**
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

 **Returns:**
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

 **Returns:**
void


---


### iterator {#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Returns:**



---


### iteratorJava {#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Returns:**



---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove ([MotionCmdPath](../motioncmdpath)) | Removes specified commans from the collection. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| item | [MotionCmdPath](../motioncmdpath) | Motion path to remove. |

 **Returns:**
void


---


### removeAt {#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes a command at the specified index. |

 **Parameters:**

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of a command that should be deleted. |

 **Returns:**
void


---


