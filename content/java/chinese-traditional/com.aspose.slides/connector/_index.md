---
title: Connector
second_title: Aspose.Slides for Java API 參考文件
description: 表示一個連接器。
type: docs
url: /zh-hant/com.aspose.slides/connector/
---
**繼承:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**所有實作的介面:**  
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)  
```
public class Connector extends GeometryShape implements IConnector
```

表示一個連接器。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | 返回形狀的鎖定。 |
| [getConnectorLock()](#getConnectorLock--) | 返回連接器的鎖定。 |
| [getShapeType()](#getShapeType--) | 返回或設定 AutoShape 類型。 |
| [setShapeType(int value)](#setShapeType-int-) | 返回或設定 AutoShape 類型。 |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | 返回或設定要將連接器的起點附加到的形狀。 |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | 返回或設定要將連接器的起點附加到的形狀。 |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | 返回或設定要將連接器的終點附加到的形狀。 |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | 返回或設定要將連接器的終點附加到的形狀。 |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | 返回或設定起始形狀的連接點索引。 |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | 返回或設定起始形狀的連接點索引。 |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | 返回或設定結束形狀的連接點索引。 |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | 返回或設定結束形狀的連接點索引。 |
| [reroute()](#reroute--) | 重新路由連接器，使其在連接的形狀之間走最短路徑。 |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

返回形狀的鎖定。只讀 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**返回：**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

返回連接器的鎖定。只讀 [IConnectorLock](../../com.aspose.slides/iconnectorlock)。

**返回：**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

返回或設定 AutoShape 類型。可讀寫 [ShapeType](../../com.aspose.slides/shapetype)。

**返回：**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

返回或設定 AutoShape 類型。可讀寫 [ShapeType](../../com.aspose.slides/shapetype)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

返回或設定要將連接器的起點附加到的形狀。可讀寫 [IShape](../../com.aspose.slides/ishape)。

**返回：**  
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

返回或設定要將連接器的起點附加到的形狀。可讀寫 [IShape](../../com.aspose.slides/ishape)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

返回或設定要將連接器的終點附加到的形狀。可讀寫 [IShape](../../com.aspose.slides/ishape)。

**返回：**  
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

返回或設定要將連接器的終點附加到的形狀。可讀寫 [IShape](../../com.aspose.slides/ishape)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

返回或設定起始形狀的連接點索引。可讀寫 long。

**返回：**  
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

返回或設定起始形狀的連接點索引。可讀寫 long。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

返回或設定結束形狀的連接點索引。可讀寫 long。

**返回：**  
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

返回或設定結束形狀的連接點索引。可讀寫 long。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```

重新路由連接器，使其在連接的形狀之間走最短路徑。