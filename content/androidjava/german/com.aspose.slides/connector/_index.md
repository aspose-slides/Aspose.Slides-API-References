---
title: Connector
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt einen Verbinder dar.
type: docs
url: /de/com.aspose.slides/connector/
---
**Vererbung:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Stellt einen Verbinder dar.
## Methoden

| Method | Description |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Gibt die Sperren der Form zurück. |
| [getConnectorLock()](#getConnectorLock--) | Gibt die Sperren des Verbinders zurück. |
| [getShapeType()](#getShapeType--) | Gibt den AutoShape-Typ zurück oder legt ihn fest. |
| [setShapeType(int value)](#setShapeType-int-) | Gibt den AutoShape-Typ zurück oder legt ihn fest. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Gibt die Form zurück, an die der Anfang des Verbinders angehängt wird, oder legt sie fest. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Gibt die Form zurück, an die der Anfang des Verbinders angehängt wird, oder legt sie fest. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Gibt die Form zurück, an die das Ende des Verbinders angehängt wird, oder legt sie fest. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Gibt die Form zurück, an die das Ende des Verbinders angehängt wird, oder legt sie fest. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Gibt den Index der Verbindungsstelle für die Startform zurück oder legt ihn fest. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Gibt den Index der Verbindungsstelle für die Startform zurück oder legt ihn fest. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Gibt den Index der Verbindungsstelle für die Zielform zurück oder legt ihn fest. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Gibt den Index der Verbindungsstelle für die Zielform zurück oder legt ihn fest. |
| [reroute()](#reroute--) | Leitet den Verbinder neu, sodass er den kürzesten möglichen Pfad zwischen den Formen, die er verbindet, nimmt. |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

Gibt die Sperren der Form zurück. Nur lesbar [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Rückgabe:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

Gibt die Sperren des Verbinders zurück. Nur lesbar [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Rückgabe:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Gibt den AutoShape-Typ zurück oder legt ihn fest. Lese/Schreib [ShapeType](../../com.aspose.slides/shapetype).

**Rückgabe:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Gibt den AutoShape-Typ zurück oder legt ihn fest. Lese/Schreib [ShapeType](../../com.aspose.slides/shapetype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

Gibt die Form zurück, an die der Anfang des Verbinders angehängt wird, oder legt sie fest. Lese/Schreib [IShape](../../com.aspose.slides/ishape).

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

Gibt die Form zurück, an die der Anfang des Verbinders angehängt wird, oder legt sie fest. Lese/Schreib [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

Gibt die Form zurück, an die das Ende des Verbinders angehängt wird, oder legt sie fest. Lese/Schreib [IShape](../../com.aspose.slides/ishape).

**Rückgabe:**
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

Gibt die Form zurück, an die das Ende des Verbinders angehängt wird, oder legt sie fest. Lese/Schreib [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

Gibt den Index der Verbindungsstelle für die Startform zurück oder legt ihn fest. Lese/Schreib long.

**Rückgabe:**
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

Gibt den Index der Verbindungsstelle für die Startform zurück oder legt ihn fest. Lese/Schreib long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

Gibt den Index der Verbindungsstelle für die Zielform zurück oder legt ihn fest. Lese/Schreib long.

**Rückgabe:**
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

Gibt den Index der Verbindungsstelle für die Zielform zurück oder legt ihn fest. Lese/Schreib long.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```

Leitet den Verbinder neu, sodass er den kürzesten möglichen Pfad zwischen den Formen, die er verbindet, nimmt.