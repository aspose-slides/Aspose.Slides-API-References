---
title: Connector
second_title: Aspose.Slides 的 Java API 参考
description: 表示连接器。
type: docs
url: /zh/com.aspose.slides/connector/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

表示连接器。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | 返回形状的锁定。 |
| [getConnectorLock()](#getConnectorLock--) | 返回连接器的锁定。 |
| [getShapeType()](#getShapeType--) | 返回或设置 AutoShape 类型。 |
| [setShapeType(int value)](#setShapeType-int-) | 返回或设置 AutoShape 类型。 |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | 返回或设置连接器起始端要附着的形状。 |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | 返回或设置连接器起始端要附着的形状。 |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | 返回或设置连接器结束端要附着的形状。 |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | 返回或设置连接器结束端要附着的形状。 |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | 返回或设置起始形状的连接点索引。 |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | 返回或设置起始形状的连接点索引。 |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | 返回或设置结束形状的连接点索引。 |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | 返回或设置结束形状的连接点索引。 |
| [reroute()](#reroute--) | 重新路由连接器，使其在所连接的形状之间采用最短路径。 |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```


返回形状的锁定。只读 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**返回:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```


返回连接器的锁定。只读 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**返回:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


返回或设置 AutoShape 类型。读/写 [ShapeType](../../com.aspose.slides/shapetype)。

**返回:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


返回或设置 AutoShape 类型。读/写 [ShapeType](../../com.aspose.slides/shapetype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```


返回或设置连接器起始端要附着的形状。读/写 [IShape](../../com.aspose.slides/ishape)。

**返回:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```


返回或设置连接器起始端要附着的形状。读/写 [IShape](../../com.aspose.slides/ishape)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```


返回或设置连接器结束端要附着的形状。读/写 [IShape](../../com.aspose.slides/ishape)。

**返回:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```


返回或设置连接器结束端要附着的形状。读/写 [IShape](../../com.aspose.slides/ishape)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```


返回或设置起始形状的连接点索引。读/写 long。

**返回:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```


返回或设置起始形状的连接点索引。读/写 long。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```


返回或设置结束形状的连接点索引。读/写 long。

**返回:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```


返回或设置结束形状的连接点索引。读/写 long。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```


重新路由连接器，使其在所连接的形状之间采用最短路径。