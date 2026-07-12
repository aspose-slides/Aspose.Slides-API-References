---
title: IConnector
second_title: Aspose.Slides Androidra a Java API hivatkozáson keresztül
description: Egy csatlakozót reprezentál.
type: docs
url: /hu/com.aspose.slides/iconnector/
---
**Minden implementált interfész:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Egy csatlakozót reprezentál.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Visszaadja a shape zárolásait. |
| [getConnectorLock()](#getConnectorLock--) | Visszaadja a Connector zárolásait. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Visszaadja vagy beállítja azt a shape-et, amelyhez a csatlakozó elejét kell csatolni. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Visszaadja vagy beállítja azt a shape-et, amelyhez a csatlakozó elejét kell csatolni. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Visszaadja vagy beállítja azt a shape-et, amelyhez a csatlakozó végét kell csatolni. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Visszaadja vagy beállítja azt a shape-et, amelyhez a csatlakozó végét kell csatolni. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Visszaadja vagy beállítja a start shape kapcsolathelyének indexét. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Visszaadja vagy beállítja a start shape kapcsolathelyének indexét. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Visszaadja vagy beállítja az end shape kapcsolathelyének indexét. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Visszaadja vagy beállítja az end shape kapcsolathelyének indexét. |
| [reroute()](#reroute--) | Átirányítja a connectort, hogy a csatlakoztatott shape-ek között a lehető legrövidebb utat vegye. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```


Visszaadja a shape zárolásait. Csak olvasható [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Visszatér:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Visszaadja a Connector zárolásait. Csak olvasható [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Visszatér:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


Visszaadja vagy beállítja azt a shape-et, amelyhez a csatlakozó elejét kell csatolni. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Visszatér:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


Visszaadja vagy beállítja azt a shape-et, amelyhez a csatlakozó elejét kell csatolni. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


Visszaadja vagy beállítja azt a shape-et, amelyhez a csatlakozó végét kell csatolni. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Visszatér:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


Visszaadja vagy beállítja azt a shape-et, amelyhez a csatlakozó végét kell csatolni. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


Visszaadja vagy beállítja a start shape kapcsolathelyének indexét. Olvasás/írás long.

**Visszatér:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


Visszaadja vagy beállítja a start shape kapcsolathelyének indexét. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


Visszaadja vagy beállítja az end shape kapcsolathelyének indexét. Olvasás/írás long.

**Visszatér:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


Visszaadja vagy beállítja az end shape kapcsolathelyének indexét. Olvasás/írás long.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```


Átirányítja a connectort, hogy a csatlakoztatott shape-ek között a lehető legrövidebb utat vegye.