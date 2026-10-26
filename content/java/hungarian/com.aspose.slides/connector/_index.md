---
title: Connector
second_title: Aspose.Slides for Java API referencia
description: Egy csatlakozót reprezentál.
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

Egy csatlakozót reprezentál.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Visszaadja az alakzat zárolásait. |
| [getConnectorLock()](#getConnectorLock--) | Visszaadja a csatlakozó zárolásait. |
| [getShapeType()](#getShapeType--) | Visszaadja vagy beállítja az AutoShape típusát. |
| [setShapeType(int value)](#setShapeType-int-) | Visszaadja vagy beállítja az AutoShape típusát. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Visszaadja vagy beállítja azt az alakzatot, amelyhez a csatlakozó elejét kell csatolni. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Visszaadja vagy beállítja azt az alakzatot, amelyhez a csatlakozó elejét kell csatolni. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Visszaadja vagy beállítja azt az alakzatot, amelyhez a csatlakozó végét kell csatolni. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Visszaadja vagy beállítja azt az alakzatot, amelyhez a csatlakozó végét kell csatolni. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Visszaadja vagy beállítja a kiinduló alakzat csatlakozási pontjának indexét. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Visszaadja vagy beállítja a kiinduló alakzat csatlakozási pontjának indexét. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Visszaadja vagy beállítja a befejező alakzat csatlakozási pontjának indexét. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Visszaadja vagy beállítja a befejező alakzat csatlakozási pontjának indexét. |
| [reroute()](#reroute--) | Újraútvonalazza a csatlakozót, hogy a csatlakoztatott alakzatok között a lehető legkisebb útvonalat vegye. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```


Visszaadja az alakzat zárolásait. Csak olvasható [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Visszatérési érték:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```


Visszaadja a csatlakozó zárolásait. Csak olvasható [IConnectorLock](../../com.aspose.slides/iconnectorlock).

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```


Visszaadja vagy beállítja azt az alakzatot, amelyhez a csatlakozó elejét kell csatolni. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```


Visszaadja vagy beállítja azt az alakzatot, amelyhez a csatlakozó elejét kell csatolni. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```


Visszaadja vagy beállítja azt az alakzatot, amelyhez a csatlakozó végét kell csatolni. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Visszatérési érték:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```


Visszaadja vagy beállítja azt az alakzatot, amelyhez a csatlakozó végét kell csatolni. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```


Visszaadja vagy beállítja a kiinduló alakzat csatlakozási pontjának indexét. Olvasás/írás long.

**Visszatérési érték:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```


Visszaadja vagy beállítja a kiinduló alakzat csatlakozási pontjának indexét. Olvasás/írás long.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```


Visszaadja vagy beállítja a befejező alakzat csatlakozási pontjának indexét. Olvasás/írás long.

**Visszatérési érték:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```


Visszaadja vagy beállítja a befejező alakzat csatlakozási pontjának indexét. Olvasás/írás long.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public final void reroute()
```


Újraútvonalazza a csatlakozót, hogy a csatlakoztatott alakzatok között a lehető legkisebb útvonalat vegye.