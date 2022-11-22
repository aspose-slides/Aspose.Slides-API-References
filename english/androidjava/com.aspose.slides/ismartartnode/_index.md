---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: Represents node of a SmartArt diagram.
type: docs
weight: 1039
url: /androidjava/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

Represents node of a SmartArt diagram.
## Methods

| Method | Description |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | Returns collections of all child nodes of current node. |
| [getShapes()](#getShapes--) | Returns collections of all shapes associated with the node. |
| [getTextFrame()](#getTextFrame--) | Returns or sets text of the node. |
| [isAssistant()](#isAssistant--) | Returns or sets the node as assistant. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | Returns or sets the node as assistant. |
| [getLevel()](#getLevel--) | Returns nesting level of the node. |
| [getBulletFillFormat()](#getBulletFillFormat--) | Returns the FillFormat object that contains fill formatting properties for a node bullet. |
| [getPosition()](#getPosition--) | Returns or sets zero-based position of the node among sibling nodes. |
| [setPosition(int value)](#setPosition-int-) | Returns or sets zero-based position of the node among sibling nodes. |
| [isHidden()](#isHidden--) | Returns true if this node is a hidden node in the data model. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | Returns or sets organization chart layout type associated with current node. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | Returns or sets organization chart layout type associated with current node. |
| [remove()](#remove--) | Remove current node. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```


Returns collections of all child nodes of current node. Read-only [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**Returns:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```


Returns collections of all shapes associated with the node. Read-only [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**Returns:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Returns or sets text of the node. Read-only [ITextFrame](../../com.aspose.slides/itextframe).

**Returns:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```


Returns or sets the node as assistant. Read/write boolean.

**Returns:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```


Returns or sets the node as assistant. Read/write boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public abstract int getLevel()
```


Returns nesting level of the node. Read-only int.

**Returns:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```


Returns the FillFormat object that contains fill formatting properties for a node bullet. Note: can return null for certain types of SmartArt layout which does not provide bullets for nodes. Read-only [IFillFormat](../../com.aspose.slides/ifillformat).

**Returns:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Returns or sets zero-based position of the node among sibling nodes. Read/write int.

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Returns or sets zero-based position of the node among sibling nodes. Read/write int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


Returns true if this node is a hidden node in the data model. Read-only boolean.

**Returns:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```


Returns or sets organization chart layout type associated with current node. Read/write [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Returns:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```


Returns or sets organization chart layout type associated with current node. Read/write [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public abstract boolean remove()
```


Remove current node.

**Returns:**
boolean - true if removed succesfully, otherwise false.
