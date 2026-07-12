---
title: Connector
second_title: Aspose.Slides Androidhoz Java API referencia
description: Egy csatlakozót ábrázol.
type: docs
url: /hu/com.aspose.slides/connector/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Minden megvalósított interfész:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Egy csatlakozót ábrázol.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Visszaadja a shape zárolásait. |
| [getConnectorLock()](#getConnectorLock--) | Visszaadja a connector zárolásait. |
| [getShapeType()](#getShapeType--) | Visszaadja vagy beállítja az AutoShape típusát. |
| [setShapeType(int value)](#setShapeType-int-) | Visszaadja vagy beállítja az AutoShape típusát. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Visszaadja vagy beállítja azt a shape-t, amelyhez a csatlakozó elejét kell csatolni. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Visszaadja vagy beállítja azt a shape-t, amelyhez a csatlakozó elejét kell csatolni. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Visszaadja vagy beállítja azt a shape-t, amelyhez a csatlakozó végét kell csatolni. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Visszaadja vagy beállítja azt a shape-t, amelyhez a csatlakozó végét kell csatolni. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Visszaadja vagy beállítja a kezdő shape csatlakozási pont indexét. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Visszaadja vagy beállítja a kezdő shape csatlakozási pont indexét. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Visszaadja vagy beállítja a befejező shape csatlakozási pont indexét. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Visszaadja vagy beállítja a befejező shape csatlakozási pont indexét. |
| [reroute()](#reroute--) | Átirányítja a csatlakozót, hogy a lehető legrövidebb utat vegye a csatlakoztatott alakzatok között. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```


Visszaadja a shape zárolásait. Csak olvasható [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Visszatérési érték:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```


Visszaadja a connector zárolásait. Csak olvasható [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Visszatérési érték:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Visszaadja vagy beállítja az AutoShape típusát. Olvasás/írás [ShapeType](../../com.aspose.slides/shapetype).

**Visszatérési érték:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Visszaadja vagy beállítja az AutoShape típusát. Olvasás/írás [ShapeType](../../com.aspose.slides/shapetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```


Visszaadja vagy beállítja azt a shape-t, amelyhez a csatlakozó elejét kell csatolni. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```


Visszaadja vagy beállítja azt a shape-t, amelyhez a csatlakozó elejét kell csatolni. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```


Visszaadja vagy beállítja azt a shape-t, amelyhez a csatlakozó végét kell csatolni. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```


Visszaadja vagy beállítja azt a shape-t, amelyhez a csatlakozó végét kell csatolni. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```


Visszaadja vagy beállítja a kezdő shape csatlakozási pont indexét. Olvasás/írás long.

**Visszatérési érték:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```


Visszaadja vagy beállítja a kezdő shape csatlakozási pont indexét. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```


Visszaadja vagy beállítja a befejező shape csatlakozási pont indexét. Olvasás/írás long.

**Visszatérési érték:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```


Visszaadja vagy beállítja a befejező shape csatlakozási pont indexét. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```


Átirányítja a csatlakozót, hogy a lehető legrövidebb utat vegye a csatlakoztatott alakzatok között.