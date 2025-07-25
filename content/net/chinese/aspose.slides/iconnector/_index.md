---
title: IConnector
second_title: Aspose.Sildes for .NET API Reference
description: 代表一个连接器。
type: docs
weight: 5410
url: /zh/aspose.slides/iconnector/
---

## IConnector接口

代表一个连接器。

```csharp
public interface IConnector : IGeometryShape
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [AsIGeometryShape](../../aspose.slides/iconnector/asigeometryshape) { get; } | 允许获取基本的IGeometryShape接口。 只读 [`IGeometryShape`](../igeometryshape)。 |
| [ConnectorLock](../../aspose.slides/iconnector/connectorlock) { get; } | 返回连接器的锁。 只读 [`IConnectorLock`](../iconnectorlock)。 |
| [EndShapeConnectedTo](../../aspose.slides/iconnector/endshapeconnectedto) { get; set; } | 返回或设置连接器末端附加的形状。 读/写 [`IShape`](../ishape)。 |
| [EndShapeConnectionSiteIndex](../../aspose.slides/iconnector/endshapeconnectionsiteindex) { get; set; } | 返回或设置末端形状的连接站点索引。 读/写 UInt32。 |
| [ShapeLock](../../aspose.slides/iconnector/shapelock) { get; } | 返回形状的锁。 只读 [`IConnectorLock`](../iconnectorlock)。 |
| [StartShapeConnectedTo](../../aspose.slides/iconnector/startshapeconnectedto) { get; set; } | 返回或设置连接器起始端附加的形状。 读/写 [`IShape`](../ishape)。 |
| [StartShapeConnectionSiteIndex](../../aspose.slides/iconnector/startshapeconnectionsiteindex) { get; set; } | 返回或设置起始形状的连接站点索引。 读/写 UInt32。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Reroute](../../aspose.slides/iconnector/reroute)() | 重新规划连接器，使其在连接的形状之间采取最短路径。 |

### 另见

* 接口 [IGeometryShape](../igeometryshape)
* 命名空间 [Aspose.Slides](../../aspose.slides)
* 程序集 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->