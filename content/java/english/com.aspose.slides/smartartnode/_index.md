---
title: SmartArtNode
second_title: Aspose.Slides for Java API Reference
description: Represents node of a SmartArt object
type: docs
url: /com.aspose.slides/smartartnode/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

Represents node of a SmartArt object
## Methods

| Method | Description |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Returns collections of all child nodes of the current node. |
| [getShapes()](#getShapes--) | Returns collections of all shapes associated with the node. |
| [getTextFrame()](#getTextFrame--) | Returns text frame of the node. |
| [isAssistant()](#isAssistant--) | Returns or sets the node as assistant. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Returns or sets the node as assistant. |
| [getLevel()](#getLevel--) | Returns nesting level of the node. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Returns the FillFormat object that contains fill formatting properties for a node bullet. |
| [getPosition()](#getPosition--) | Returns or sets zero-based position of node among sibling nodes. |
| [setPosition(int value)](#setPosition-int-) | Returns or sets zero-based position of node among sibling nodes. |
| [isHidden()](#isHidden--) | Returns true if this node is a hidden node in the data model. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Returns or sets organization chart layout type associated with current node. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Returns or sets organization chart layout type associated with current node. |
| [remove()](#remove--) | Remove current node. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```


Returns collections of all child nodes of the current node. Read-only [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returns:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```


Returns collections of all shapes associated with the node. Read-only [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Returns:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


Returns text frame of the node. Read-only [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```


Returns or sets the node as assistant. Read/write boolean.

**Returns:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```


Returns or sets the node as assistant. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public final int getLevel()
```


Returns nesting level of the node. Read-only int.

**Returns:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```


Returns the FillFormat object that contains fill formatting properties for a node bullet. Note: can return null for certain types of SmartArt layout which does not provide bullets for nodes. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


Returns or sets zero-based position of node among sibling nodes. Read/write  int .

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Returns or sets zero-based position of node among sibling nodes. Read/write  int .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


Returns true if this node is a hidden node in the data model. Read-only boolean.

**Returns:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```


Returns or sets organization chart layout type associated with current node. Read/write [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Returns:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```


Returns or sets organization chart layout type associated with current node. Read/write [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public final boolean remove()
```


Remove current node.

**Returns:**
boolean - true if removed succesfully, otherwise false
