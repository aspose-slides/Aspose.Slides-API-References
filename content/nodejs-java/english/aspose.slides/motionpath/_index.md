---
title: MotionPath
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/motionpath/
---

## MotionPath class

 Represent motion path.
 
| [MotionPath]() |  |

### Result
MotionPath


---


| [add] ([int], [java.awt.geom.Point2D.Float[]], [int], [boolean]) | Add new command to path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| type | [int] | MotionCommandPathType |
| pts | [java.awt.geom.Point2D.Float[]] | Array of points |
| ptsType | [int] | MotionPathPointsType |
| bRelativeCoord | [boolean] | Relative coordinates boolean |

### Result
[MotionCmdPath]


---


| [clear] () | Removes all commands from the collection. |


---


| [getCount] () | Returns the number of paths in the collection. Read-only int. |

### Result
int


---


| [get_Item] ([int]) | Returns a command at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of element. |

### Result
[MotionCmdPath]


---


| [insert] ([int], [int], [java.awt.geom.Point2D.Float[]], [int], [boolean]) | Insert new command to path |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | The zero-based index at which item should be inserted. |
| type | [int] | MotionCommandPathType |
| pts | [java.awt.geom.Point2D.Float[]] | Array of points |
| ptsType | [int] | MotionPathPointsType |
| bRelativeCoord | [boolean] | Relative coordinates boolean |


---


| [iterator] () | Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava] () | Returns a java iterator for the entire collection. |

### Result



---


| [remove] ([MotionCmdPath]) | Removes specified commans from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [MotionCmdPath] | Motion path to remove. |


---


| [removeAt] ([int]) | Removes a command at the specified index. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of a command that should be deleted. |


---


