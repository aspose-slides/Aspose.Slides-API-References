---
title: IConnector
second_title: Aspose.Slides för Java API-referens
description: Representerar en anslutning.
type: docs
url: /sv/com.aspose.slides/iconnector/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Representerar en anslutning.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Returnerar formens lås. |
| [getConnectorLock()](#getConnectorLock--) | Returnerar Connectors lås. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Returnerar eller anger formen som anslutningens början ska fästas på. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Returnerar eller anger formen som anslutningens början ska fästas på. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Returnerar eller anger formen som anslutningens slut ska fästas på. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Returnerar eller anger formen som anslutningens slut ska fästas på. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Returnerar eller anger index för anslutningsplats för startformen. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Returnerar eller anger index för anslutningsplats för startformen. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Returnerar eller anger index för anslutningsplats för slutformen. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Returnerar eller anger index för anslutningsplats för slutformen. |
| [reroute()](#reroute--) | Omruttar anslutning så att den tar den kortaste möjliga vägen mellan formerna den ansluter. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

Returnerar formens lås. Skrivskyddad [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Returnerar:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

Returnerar Connectors lås. Skrivskyddad [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Returnerar:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

Returnerar eller anger formen som anslutningens början ska fästas på. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

Returnerar eller anger formen som anslutningens början ska fästas på. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

Returnerar eller anger formen som anslutningens slut ska fästas på. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Returnerar:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

Returnerar eller anger formen som anslutningens slut ska fästas på. Läs/skriv [IShape](../../com.aspose.slides/ishape).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

Returnerar eller anger index för anslutningsplats för startformen. Läs/skriv long.

**Returnerar:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

Returnerar eller anger index för anslutningsplats för startformen. Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

Returnerar eller anger index för anslutningsplats för slutformen. Läs/skriv long.

**Returnerar:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

Returnerar eller anger index för anslutningsplats för slutformen. Läs/skriv long.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

Omruttar anslutning så att den tar den kortaste möjliga vägen mellan formerna den ansluter.