---
title: ControlCollection
second_title: Aspose.Sildes for Node.js via Java API Reference
description: 
type: docs

url: /aspose.slides/controlcollection/
---

## ControlCollection class

 A collection of ActiveX controls.
 
###addControl{#addControl}

| Name | Description |
| --- | --- |
| addControl (int, float, float, float, float) | Creates and adds a new control to the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| controlType | int | Type of a control to add. |
| x | float | The X-coordinate for a left side of shape's frame. |
| y | float | The Y-coordinate for a top side of shape's frame. |
| width | float | The width of shape's frame. |
| height | float | The height of shape's frame. |

 **Result**
[Control](../control)


---


###clear{#clear}

| Name | Description |
| --- | --- |
| clear () | Removes all controls from the collection. |


---


###getSyncRoot{#getSyncRoot}

| Name | Description |
| --- | --- |
| getSyncRoot () | Returns a synchronization root. Read-only Object. |

 **Result**
Object


---


###get_Item{#get_Item}

| Name | Description |
| --- | --- |
| get_Item (int) | Returns a control at the specified position. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of a control. |

 **Result**
[Control](../control)


---


###isSynchronized{#isSynchronized}

| Name | Description |
| --- | --- |
| isSynchronized () | Returns a value indicating whether access to the collection is synchronized (thread-safe). Read-only boolean. |

 **Result**
boolean


---


###iterator{#iterator}

| Name | Description |
| --- | --- |
| iterator () | Returns an enumerator that iterates through the collection. |

 **Result**



---


###iteratorJava{#iteratorJava}

| Name | Description |
| --- | --- |
| iteratorJava () | Returns a java iterator for the entire collection. |

 **Result**



---


###remove{#remove}

| Name | Description |
| --- | --- |
| remove ([Control](../control)) | Removes an ActiveX control from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| item | [Control](../control) | A control to remove. |


---


###removeAt{#removeAt}

| Name | Description |
| --- | --- |
| removeAt (int) | Removes an ActiveX control stored at specified position from the collection. |

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| index | int | Index of a control to remove. |


---


###size{#size}

| Name | Description |
| --- | --- |
| size () | Returns a number of objects in the collection. Read-only int. |

 **Result**
int


---


