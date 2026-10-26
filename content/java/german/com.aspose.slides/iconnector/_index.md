---
title: IConnector
second_title: Aspose.Slides für Java API Referenz
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
| [getShapeLock()](#getShapeLock--) | Gibt die Sperren der Form zurück. |
| [getConnectorLock()](#getConnectorLock--) | Gibt die Sperren des Connectors zurück. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Gibt die Form zurück oder legt sie fest, an die der Anfang des Connectors angehängt wird. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Gibt die Form zurück oder legt sie fest, an die der Anfang des Connectors angehängt wird. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Gibt die Form zurück oder legt sie fest, an die das Ende des Connectors angehängt wird. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Gibt die Form zurück oder legt sie fest, an die das Ende des Connectors angehängt wird. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Gibt den Index der Verbindungsstelle für die Startform zurück oder legt ihn fest. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Gibt den Index der Verbindungsstelle für die Startform zurück oder legt ihn fest. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Gibt den Index der Verbindungsstelle für die Endform zurück oder legt ihn fest. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Gibt den Index der Verbindungsstelle für die Endform zurück oder legt ihn fest. |
| [reroute()](#reroute--) | Leitet den Connector um, sodass er den kürzesten möglichen Pfad zwischen den verbundenen Formen nimmt. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

Gibt die Sperren der Form zurück. Nur-Lesen [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Rückgabe:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

Gibt die Sperren des Connectors zurück. Nur-Lesen [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Rückgabe:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

Gibt die Form zurück oder legt sie fest, an die der Anfang des Connectors angehängt wird. Lesen/Schreiben [IShape](../../com.aspose.slides/ishape).

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

Gibt die Form zurück oder legt sie fest, an die der Anfang des Connectors angehängt wird. Lesen/Schreiben [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

Gibt die Form zurück oder legt sie fest, an die das Ende des Connectors angehängt wird. Lesen/Schreiben [IShape](../../com.aspose.slides/ishape).

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

Gibt die Form zurück oder legt sie fest, an die das Ende des Connectors angehängt wird. Lesen/Schreiben [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

Gibt den Index der Verbindungsstelle für die Startform zurück oder legt ihn fest. Lesen/Schreiben long.

**Rückgabe:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

Gibt den Index der Verbindungsstelle für die Startform zurück oder legt ihn fest. Lesen/Schreiben long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

Gibt den Index der Verbindungsstelle für die Endform zurück oder legt ihn fest. Lesen/Schreiben long.

**Rückgabe:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

Gibt den Index der Verbindungsstelle für die Endform zurück oder legt ihn fest. Lesen/Schreiben long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

Leitet den Connector um, sodass er den kürzesten möglichen Pfad zwischen den verbundenen Formen nimmt.