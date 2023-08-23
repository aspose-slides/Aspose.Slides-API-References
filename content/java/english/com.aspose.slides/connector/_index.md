---
title: Connector
second_title: Aspose.Slides for Java API Reference
description: Represents a connector.
type: docs
url: /com.aspose.slides/connector/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Represents a connector.
## Methods

| Method | Description |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Returns shape's locks. |
| [getConnectorLock()](#getConnectorLock--) | Returns connector's locks. |
| [getShapeType()](#getShapeType--) | Returns or sets the AutoShape type. |
| [setShapeType(int value)](#setShapeType-int-) | Returns or sets the AutoShape type. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Returns or sets the shape to attach the beginning of the connector to. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Returns or sets the shape to attach the beginning of the connector to. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Returns or sets the shape to attach the end of the connector to. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Returns or sets the shape to attach the end of the connector to. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Returns or sets the index of connection site for start shape. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Returns or sets the index of connection site for start shape. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Returns or sets the index of connection site for end shape. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Returns or sets the index of connection site for end shape. |
| [reroute()](#reroute--) | Reroutes connector so that it take the shortest possible path between the shapes it connect. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```


Returns shape's locks. Read-only [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Returns:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```


Returns connector's locks. Read-only [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Returns:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Returns or sets the AutoShape type. Read/write [ShapeType](../../com.aspose.slides/shapetype).

**Returns:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Returns or sets the AutoShape type. Read/write [ShapeType](../../com.aspose.slides/shapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```


Returns or sets the shape to attach the beginning of the connector to. Read/write [IShape](../../com.aspose.slides/ishape).

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```


Returns or sets the shape to attach the beginning of the connector to. Read/write [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```


Returns or sets the shape to attach the end of the connector to. Read/write [IShape](../../com.aspose.slides/ishape).

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```


Returns or sets the shape to attach the end of the connector to. Read/write [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```


Returns or sets the index of connection site for start shape. Read/write long.

**Returns:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```


Returns or sets the index of connection site for start shape. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```


Returns or sets the index of connection site for end shape. Read/write long.

**Returns:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```


Returns or sets the index of connection site for end shape. Read/write long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```


Reroutes connector so that it take the shortest possible path between the shapes it connect.

