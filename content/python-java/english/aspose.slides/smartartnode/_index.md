---
title: SmartArtNode
second_title: Aspose.Sildes for Python via Java API Reference
description: 
type: docs

url: /aspose.slides/smartartnode/
---

## SmartArtNode class

 Represents node of a SmartArt object
 
### getBulletFillFormat {#getBulletFillFormat}

| Name | Description |
| --- | --- |
| getBulletFillFormat() | Returns the FillFormat object that contains fill formatting properties for a node bullet. Note: can return null for certain types of SmartArt layout which does not provide bullets for nodes. Read-only IFillFormat. |

 **Result:**
[FillFormat](../fillformat)


---


### getChildNodes {#getChildNodes}

| Name | Description |
| --- | --- |
| getChildNodes() | Returns collections of all child nodes of the current node. Read-only ISmartArtNodeCollection. |

 **Result:**
[SmartArtNodeCollection](../smartartnodecollection)


---


### getLevel {#getLevel}

| Name | Description |
| --- | --- |
| getLevel() | Returns nesting level of the node. Read-only int. |

 **Result:**
int


---


### getOrganizationChartLayout {#getOrganizationChartLayout}

| Name | Description |
| --- | --- |
| getOrganizationChartLayout() | Returns or sets organization chart layout type associated with current node. Read/write OrganizationChartLayoutType. |

 **Result:**
int


---


### getPosition {#getPosition}

| Name | Description |
| --- | --- |
| getPosition() | Returns or sets zero-based position of node among sibling nodes. Read/write int. |

 **Result:**
int

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | value is less than 0. -or- value is equal to or greater than siblings count |


---


### getShapes {#getShapes}

| Name | Description |
| --- | --- |
| getShapes() | Returns collections of all shapes associated with the node. Read-only ISmartArtShapeCollection. |

 **Result:**
[SmartArtShapeCollection](../smartartshapecollection)


---


### getTextFrame {#getTextFrame}

| Name | Description |
| --- | --- |
| getTextFrame() | Returns or sets text of the node. Read-only ITextFrame. |

 **Result:**
[TextFrame](../textframe)


---


### isAssistant {#isAssistant}

| Name | Description |
| --- | --- |
| isAssistant() | Returns or sets the node as assistant. Read/write boolean. |

 **Result:**
boolean


---


### isHidden {#isHidden}

| Name | Description |
| --- | --- |
| isHidden() | Returns true if this node is a hidden node in the data model. Read-only boolean. |

 **Result:**
boolean


---


### remove {#remove}

| Name | Description |
| --- | --- |
| remove() | Remove current node. |

 **Result:**
boolean


---


### setAssistant {#setAssistant}

| Name | Description |
| --- | --- |
| setAssistant(boolean) | Returns or sets the node as assistant. Read/write boolean. |


---


### setOrganizationChartLayout {#setOrganizationChartLayout}

| Name | Description |
| --- | --- |
| setOrganizationChartLayout(int) | Returns or sets organization chart layout type associated with current node. Read/write OrganizationChartLayoutType. |


---


### setPosition {#setPosition}

| Name | Description |
| --- | --- |
| setPosition(int) | Returns or sets zero-based position of node among sibling nodes. Read/write int. |

 **Error**

| Error | Condition |
| --- | --- |
 | ArgumentOutOfRangeException | value is less than 0. -or- value is equal to or greater than siblings count |


---


