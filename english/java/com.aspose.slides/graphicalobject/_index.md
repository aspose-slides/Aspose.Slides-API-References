---
title: GraphicalObject
second_title: Aspose.Sildes for Java API Reference
description: p
 Represents abstract graphical object.
type: docs
weight: 230
url: /java/com.aspose.slides/graphicalobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**All Implemented Interfaces:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public class GraphicalObject extends Shape implements IGraphicalObject
```

Represents abstract graphical object.
## Constructors

| Constructor | Description |
| --- | --- |
| [GraphicalObject(IDOMObject parentImmediate)](#GraphicalObject-com.aspose.slides.IDOMObject-) |  |
| [GraphicalObject(IDOMObject parentImmediate, GraphicalObjectPPTXUnsupportedProps pptxUnsupportedProps)](#GraphicalObject-com.aspose.slides.IDOMObject-com.aspose.slides.GraphicalObjectPPTXUnsupportedProps-) |  |
| [GraphicalObject(IDOMObject parentImmediate, GraphicalObjectPPTXUnsupportedProps pptxUnsupportedProps, GraphicalObjectPPTUnsupportedProps pptUnsupportedProps)](#GraphicalObject-com.aspose.slides.IDOMObject-com.aspose.slides.GraphicalObjectPPTXUnsupportedProps-com.aspose.slides.GraphicalObjectPPTUnsupportedProps-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getGraphicalObjectLock()](#getGraphicalObjectLock--) | Returns shape's locks. |
### GraphicalObject(IDOMObject parentImmediate) {#GraphicalObject-com.aspose.slides.IDOMObject-}
```
 GraphicalObject(IDOMObject parentImmediate)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |

### GraphicalObject(IDOMObject parentImmediate, GraphicalObjectPPTXUnsupportedProps pptxUnsupportedProps) {#GraphicalObject-com.aspose.slides.IDOMObject-com.aspose.slides.GraphicalObjectPPTXUnsupportedProps-}
```
 GraphicalObject(IDOMObject parentImmediate, GraphicalObjectPPTXUnsupportedProps pptxUnsupportedProps)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |
| pptxUnsupportedProps | com.aspose.slides.GraphicalObjectPPTXUnsupportedProps |  |

### GraphicalObject(IDOMObject parentImmediate, GraphicalObjectPPTXUnsupportedProps pptxUnsupportedProps, GraphicalObjectPPTUnsupportedProps pptUnsupportedProps) {#GraphicalObject-com.aspose.slides.IDOMObject-com.aspose.slides.GraphicalObjectPPTXUnsupportedProps-com.aspose.slides.GraphicalObjectPPTUnsupportedProps-}
```
 GraphicalObject(IDOMObject parentImmediate, GraphicalObjectPPTXUnsupportedProps pptxUnsupportedProps, GraphicalObjectPPTUnsupportedProps pptUnsupportedProps)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| parentImmediate | com.aspose.slides.IDOMObject |  |
| pptxUnsupportedProps | com.aspose.slides.GraphicalObjectPPTXUnsupportedProps |  |
| pptUnsupportedProps | com.aspose.slides.GraphicalObjectPPTUnsupportedProps |  |

### getGraphicalObjectLock() {#getGraphicalObjectLock--}
```
public final IGraphicalObjectLock getGraphicalObjectLock()
```


Returns shape's locks. Read-only [IGraphicalObjectLock](../../com.aspose.slides/igraphicalobjectlock).

**Returns:**
[IGraphicalObjectLock](../../com.aspose.slides/igraphicalobjectlock)
