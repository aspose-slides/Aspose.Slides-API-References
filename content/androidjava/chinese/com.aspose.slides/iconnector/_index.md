---
title: IConnector
second_title: 适用于 Android 的 Aspose.Slides Java API 参考
description: 表示一个连接器。
type: docs
url: /zh/com.aspose.slides/iconnector/
---
**所有已实现的接口：**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

表示一个连接器。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | 返回形状的锁定。 |
| [getConnectorLock()](#getConnectorLock--) | 返回连接器的锁定。 |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | 返回或设置用于连接器起点的形状。 |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | 返回或设置用于连接器起点的形状。 |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | 返回或设置用于连接器终点的形状。 |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | 返回或设置用于连接器终点的形状。 |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | 返回或设置起始形状的连接点索引。 |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | 返回或设置起始形状的连接点索引。 |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | 返回或设置结束形状的连接点索引。 |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | 返回或设置结束形状的连接点索引。 |
| [reroute()](#reroute--) | 重新路由连接器，使其在所连接的形状之间采用最短路径。 |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

返回形状的锁定。只读 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**返回：**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

返回连接器的锁定。只读 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**返回：**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

返回或设置用于连接器起点的形状。读/写 [IShape](../../com.aspose.slides/ishape)。

**返回：**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

返回或设置用于连接器起点的形状。读/写 [IShape](../../com.aspose.slides/ishape)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

返回或设置用于连接器终点的形状。读/写 [IShape](../../com.aspose.slides/ishape)。

**返回：**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

返回或设置用于连接器终点的形状。读/写 [IShape](../../com.aspose.slides/ishape)。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

返回或设置起始形状的连接点索引。读/写 long。

**返回：**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

返回或设置起始形状的连接点索引。读/写 long。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

返回或设置结束形状的连接点索引。读/写 long。

**返回：**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

返回或设置结束形状的连接点索引。读/写 long。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

重新路由连接器，使其在所连接的形状之间采用最短路径。