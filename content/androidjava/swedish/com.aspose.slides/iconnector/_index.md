---
title: IConnector
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en connector.
type: docs
url: /sv/com.aspose.slides/iconnector/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Representerar en connector.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Returnerar shape's lås. |
| [getConnectorLock()](#getConnectorLock--) | Returnerar Connector's lås. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Returnerar eller anger shape som ansluten i början av connectorn. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Returnerar eller anger shape som ansluten i början av connectorn. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Returnerar eller anger shape som ansluten i slutet av connectorn. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Returnerar eller anger shape som ansluten i slutet av connectorn. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Returnerar eller anger index för anslutningsplats för startshape. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Returnerar eller anger index för anslutningsplats för startshape. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Returnerar eller anger index för anslutningsplats för endshape. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Returnerar eller anger index för anslutningsplats för endshape. |
| [reroute()](#reroute--) | Routar om connector så att den tar den kortaste möjliga vägen mellan de shapes den ansluter. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```


Returnerar shape's lås. Endast läsning [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Returnerar:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Returnerar Connector's lås. Endast läsning [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Returnerar:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


Returnerar eller anger shape som ansluten i början av connectorn. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


Returnerar eller anger shape som ansluten i början av connectorn. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


Returnerar eller anger shape som ansluten i slutet av connectorn. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


Returnerar eller anger shape som ansluten i slutet av connectorn. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


Returnerar eller anger index för anslutningsplats för startshape. Läs/skriv long.

**Returnerar:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


Returnerar eller anger index för anslutningsplats för startshape. Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


Returnerar eller anger index för anslutningsplats för endshape. Läs/skriv long.

**Returnerar:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


Returnerar eller anger index för anslutningsplats för endshape. Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```


Routar om connector så att den tar den kortaste möjliga vägen mellan de shapes den ansluter.