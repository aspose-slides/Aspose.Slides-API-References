---
title: IConnector
second_title: Aspose.Slides Java API referencia
description: Egy csatlakozót reprezentál.
type: docs
url: /hu/com.aspose.slides/iconnector/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Egy connector-t reprezentál.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Visszaadja a shape zárolásait. |
| [getConnectorLock()](#getConnectorLock--) | Visszaadja a Connector zárolásait. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Visszaadja vagy beállítja a shape-et, amelyhez a connector eleje csatlakozik. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Visszaadja vagy beállítja a shape-et, amelyhez a connector eleje csatlakozik. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Visszaadja vagy beállítja a shape-et, amelyhez a connector vége csatlakozik. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Visszaadja vagy beállítja a shape-et, amelyhez a connector vége csatlakozik. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Visszaadja vagy beállítja a kezdő shape kapcsolathelyének indexét. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Visszaadja vagy beállítja a kezdő shape kapcsolathelyének indexét. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Visszaadja vagy beállítja a befejező shape kapcsolathelyének indexét. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Visszaadja vagy beállítja a befejező shape kapcsolathelyének indexét. |
| [reroute()](#reroute--) | Átirányítja a connector-t, hogy a csatlakoztatott shape-ek között a lehető legrövidebb útvonalat vegye. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

Visszaadja a shape zárolásait. Csak olvasható [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Visszaad:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

Visszaadja a Connector zárolásait. Csak olvasható [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Visszaad:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

Visszaadja vagy beállítja a shape-et, amelyhez a connector eleje csatlakozik. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Visszaad:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

Visszaadja vagy beállítja a shape-et, amelyhez a connector eleje csatlakozik. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

Visszaadja vagy beállítja a shape-et, amelyhez a connector vége csatlakozik. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Visszaad:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

Visszaadja vagy beállítja a shape-et, amelyhez a connector vége csatlakozik. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

Visszaadja vagy beállítja a kezdő shape kapcsolathelyének indexét. Olvasás/írás long.

**Visszaad:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

Visszaadja vagy beállítja a kezdő shape kapcsolathelyének indexét. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

Visszaadja vagy beállítja a befejező shape kapcsolathelyének indexét. Olvasás/írás long.

**Visszaad:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

Visszaadja vagy beállítja a befejező shape kapcsolathelyének indexét. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

Átirányítja a connector-t, hogy a csatlakoztatott shape-ek között a lehető legrövidebb útvonalat vegye.