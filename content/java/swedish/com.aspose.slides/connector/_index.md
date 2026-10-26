---
title: Connector
second_title: Aspose.Slides för Java API-referens
description: Representerar en connector.
type: docs
url: /sv/com.aspose.slides/connector/
---
**Arv:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Representerar en connector.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Returnerar shape's locks. |
| [getConnectorLock()](#getConnectorLock--) | Returnerar connector's locks. |
| [getShapeType()](#getShapeType--) | Returnerar eller anger AutoShape-typen. |
| [setShapeType(int value)](#setShapeType-int-) | Returnerar eller anger AutoShape-typen. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Returnerar eller anger shape att fästa början av connectorn till. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Returnerar eller anger shape att fästa början av connectorn till. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Returnerar eller anger shape att fästa slutet av connectorn till. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Returnerar eller anger shape att fästa slutet av connectorn till. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Returnerar eller anger index för anslutningsplats för startshape. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Returnerar eller anger index för anslutningsplats för startshape. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Returnerar eller anger index för anslutningsplats för endshape. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Returnerar eller anger index för anslutningsplats för endshape. |
| [reroute()](#reroute--) | Omdirigerar connector så att den tar den kortaste möjliga vägen mellan de former den ansluter. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

Returnerar shape's locks. Skrivskyddad [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Returnerar:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

Returnerar connector's locks. Skrivskyddad [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Returnerar:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Returnerar eller anger AutoShape-typen. Läs/skriv [ShapeType](../../com.aspose.slides/shapetype).

**Returnerar:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Returnerar eller anger AutoShape-typen. Läs/skriv [ShapeType](../../com.aspose.slides/shapetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

Returnerar eller anger shape att fästa början av connectorn till. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

Returnerar eller anger shape att fästa början av connectorn till. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

Returnerar eller anger shape att fästa slutet av connectorn till. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

Returnerar eller anger shape att fästa slutet av connectorn till. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

Returnerar eller anger index för anslutningsplats för startshape. Läs/skriv long.

**Returnerar:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

Returnerar eller anger index för anslutningsplats för startshape. Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

Returnerar eller anger index för anslutningsplats för endshape. Läs/skriv long.

**Returnerar:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

Returnerar eller anger index för anslutningsplats för endshape. Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public final void reroute()
```

Omdirigerar connector så att den tar den kortaste möjliga vägen mellan de former den ansluter.