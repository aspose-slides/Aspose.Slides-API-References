---
title: IConnector
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Connector dar.
type: docs
url: /de/com.aspose.slides/iconnector/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Stellt einen Connector dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Gibt shape's locks zurück. |
| [getConnectorLock()](#getConnectorLock--) | Gibt Connector's locks zurück. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Gibt die shape zurück oder legt sie fest, an die der Anfang des connector angehängt wird. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Gibt die shape zurück oder legt sie fest, an die der Anfang des connector angehängt wird. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Gibt die shape zurück oder legt sie fest, an die das Ende des connector angehängt wird. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Gibt die shape zurück oder legt sie fest, an die das Ende des connector angehängt wird. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Gibt den Index des Verbindungspunkts für die start shape zurück oder legt ihn fest. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Gibt den Index des Verbindungspunkts für die start shape zurück oder legt ihn fest. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Gibt den Index des Verbindungspunkts für die end shape zurück oder legt ihn fest. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Gibt den Index des Verbindungspunkts für die end shape zurück oder legt ihn fest. |
| [reroute()](#reroute--) | Leitet den connector neu, sodass er den kürzesten möglichen Pfad zwischen den shapes nimmt. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```


Gibt shape's locks zurück. Nur lesbar [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Rückgabe:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Gibt Connector's locks zurück. Nur lesbar [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Rückgabe:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


Gibt die shape zurück oder legt sie fest, an die der Anfang des connector angehängt wird. Lesen/Schreiben [IShape](../../com.aspose.slides/ishape).

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


Gibt die shape zurück oder legt sie fest, an die der Anfang des connector angehängt wird. Lesen/Schreiben [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


Gibt die shape zurück oder legt sie fest, an die das Ende des connector angehängt wird. Lesen/Schreiben [IShape](../../com.aspose.slides/ishape).

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


Gibt die shape zurück oder legt sie fest, an die das Ende des connector angehängt wird. Lesen/Schreiben [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


Gibt den Index des Verbindungspunkts für die start shape zurück oder legt ihn fest. Lesen/Schreiben long.

**Rückgabe:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


Gibt den Index des Verbindungspunkts für die start shape zurück oder legt ihn fest. Lesen/Schreiben long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


Gibt den Index des Verbindungspunkts für die end shape zurück oder legt ihn fest. Lesen/Schreiben long.

**Rückgabe:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


Gibt den Index des Verbindungspunkts für die end shape zurück oder legt ihn fest. Lesen/Schreiben long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```


Leitet den connector neu, sodass er den kürzesten möglichen Pfad zwischen den shapes nimmt.