---
title: IConnector
second_title: Aspose.Slides for Java API 參考
description: 表示一個連接器。
type: docs
url: /zh-hant/com.aspose.slides/iconnector/
---
**所有已實作的介面:**  
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

表示一個連接器。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | 傳回形狀的鎖定。 |
| [getConnectorLock()](#getConnectorLock--) | 傳回 Connector 的鎖定。 |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | 傳回或設定形狀，以將連接器的起點附加到該形狀。 |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | 傳回或設定形狀，以將連接器的起點附加到該形狀。 |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | 傳回或設定形狀，以將連接器的終點附加到該形狀。 |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | 傳回或設定形狀，以將連接器的終點附加到該形狀。 |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | 傳回或設定起始形狀的連接站點索引。 |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | 傳回或設定起始形狀的連接站點索引。 |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) *| 傳回或設定結束形狀的連接站點索引。 |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | 傳回或設定結束形狀的連接站點索引。 |
| [reroute()](#reroute--) | 重新路由連接器，使其在連接的形狀之間採取最短的路徑。 |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

傳回形狀的鎖定。唯讀 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**傳回:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

傳回 Connector 的鎖定。唯讀 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**傳回:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

傳回或設定形狀，以將連接器的起點附加到該形狀。可讀寫 [IShape](../../com.aspose.slides/ishape)。

**傳回:**  
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

傳回或設定形狀，以將連接器的起點附加到該形狀。可讀寫 [IShape](../../com.aspose.slides/ishape)。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

傳回或設定形狀，以將連接器的終點附加到該形狀。可讀寫 [IShape](../../com.aspose.slides/ishape)。

**傳回:**  
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

傳回或設定形狀，以將連接器的終點附加到該形狀。可讀寫 [IShape](../../com.aspose.slides/ishape)。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

傳回或設定起始形狀的連接站點索引。可讀寫 long。

**傳回:**  
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

傳回或設定起始形狀的連接站點索引。可讀寫 long。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

傳回或設定結束形狀的連接站點索引。可讀寫 long。

**傳回:**  
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

傳回或設定結束形狀的連接站點索引。可讀寫 long。

**參數:**  
| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

重新路由連接器，使其在連接的形狀之間採取最短的路徑。