---
title: ControlCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/controlcollection/
---

## ControlCollection class

 A collection of ActiveX controls.
 
| [addControl] ([int], [float], [float], [float], [float]) Creates and adds a new control to the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| controlType | [int] | Type of a control to add. |
| x | [float] | The X-coordinate for a left side of shape's frame. |
| y | [float] | The Y-coordinate for a top side of shape's frame. |
| width | [float] | The width of shape's frame. |
| height | [float] | The height of shape's frame. |

### Result
[Control]


---


| [clear] () Removes all controls from the collection. |


---


| [getSyncRoot] () Returns a synchronization root. Read-only Object. |

### Result
Object


---


| [get_Item] ([int]) Returns a control at the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of a control. |

### Result
[Control]


---


| [isSynchronized] () Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

### Result
boolean


---


| [iterator] () Returns an enumerator that iterates through the collection. |

### Result



---


| [iteratorJava] () Returns a java iterator for the entire collection. |

### Result



---


| [remove] ([Control]) Removes an ActiveX control from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Control] | A control to remove. |


---


| [removeAt] ([int]) Removes an ActiveX control stored at specified position from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | [int] | Index of a control to remove. |


---


| [size] () Returns a number of objects in the collection. Read-only int. |

### Result
int


---


