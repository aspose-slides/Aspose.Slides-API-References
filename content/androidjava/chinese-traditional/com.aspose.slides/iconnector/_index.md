---
title: IConnector
second_title: Aspose.Slides for Android via Java API 參考
description: 代表一個連接器。
type: docs
url: /zh-hant/com.aspose.slides/iconnector/
---
**已實作的介面:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

代表一個連接器。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | 返回形狀的鎖定。 |
| [getConnectorLock()](#getConnectorLock--) | 返回 Connector 的鎖定。 |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | 返回或設定形狀以將連接器的起點附加到該形狀。 |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | 返回或設定形狀以將連接器的起點附加到該形狀。 |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | 返回或設定形狀以將連接器的終點附加到該形狀。 |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | 返回或設定形狀以將連接器的終點附加到該形狀。 |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | 返回或設定起始形狀的連接點索引。 |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | 返回或設定起始形狀的連接點索引。 |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | 返回或設定結束形狀的連接點索引。 |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | 返回或設定結束形狀的連接點索引。 |
| [reroute()](#reroute--) | 重新路由連接器，使其在它所連接的形狀之間採取最短路徑。 |

### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

返回形狀的鎖定。唯讀 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**返回：**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

返回 Connector 的鎖定。唯讀 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**返回：**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

返回或設定形狀以將連接器的起點附加到該形狀。可讀寫 [IShape](../../com.aspose.slides/ishape)。

**返回：**
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

返回或設定形狀以將連接器的起點附加到該形狀。可讀寫 [IShape](../../com.aspose.slides/ishape)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

返回或設定形狀以將連接器的終點附加到該形狀。可讀寫 [IShape](../../com.aspose.slides/ishape)。

**返回：**
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

返回或設定形狀以將連接器的終點附加到該形狀。可讀寫 [IShape](../../com.aspose.slides/ishape)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

返回或設定起始形狀的連接點索引。可讀寫 long。

**返回：**
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

返回或設定起始形狀的連接點索引。可讀寫 long。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

返回或設定結束形狀的連接點索引。可讀寫 long。

**返回：**
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

返回或設定結束形狀的連接點索引。可讀寫 long。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```

重新路由連接器，使其在它所連接的形狀之間採取最短路徑。