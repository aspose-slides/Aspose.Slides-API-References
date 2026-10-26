---
title: IConnector
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta un connettore.
type: docs
url: /it/com.aspose.slides/iconnector/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Rappresenta un connettore.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Restituisce i blocchi della forma. |
| [getConnectorLock()](#getConnectorLock--) | Restituisce i blocchi del connettore. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Restituisce o imposta la forma a cui collegare l'inizio del connettore. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Restituisce o imposta la forma a cui collegare l'inizio del connettore. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Restituisce o imposta la forma a cui collegare la fine del connettore. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Restituisce o imposta la forma a cui collegare la fine del connettore. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Restituisce o imposta l'indice del punto di connessione per la forma iniziale. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Restituisce o imposta l'indice del punto di connessione per la forma iniziale. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Restituisce o imposta l'indice del punto di connessione per la forma finale. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Restituisce o imposta l'indice del punto di connessione per la forma finale. |
| [reroute()](#reroute--) | Riprogramma il percorso del connettore in modo che segua il cammino più breve possibile tra le forme a cui è collegato. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

Restituisce i blocchi della forma. Sola lettura [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Restituisce:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

Restituisce i blocchi del connettore. Sola lettura [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Restituisce:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

Restituisce o imposta la forma a cui collegare l'inizio del connettore. Lettura/scrittura [IShape](../../com.aspose.slides/ishape).

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

Restituisce o imposta la forma a cui collegare l'inizio del connettore. Lettura/scrittura [IShape](../../com.aspose.slides/ishape).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

Restituisce o imposta la forma a cui collegare la fine del connettore. Lettura/scrittura [IShape](../../com.aspose.slides/ishape).

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

Restituisce o imposta la forma a cui collegare la fine del connettore. Lettura/scrittura [IShape](../../com.aspose.slides/ishape).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

Restituisce o imposta l'indice del punto di connessione per la forma iniziale. Lettura/scrittura long.

**Restituisce:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

Restituisce o imposta l'indice del punto di connessione per la forma iniziale. Lettura/scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

Restituisce o imposta l'indice del punto di connessione per la forma finale. Lettura/scrittura long.

**Restituisce:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

Restituisce o imposta l'indice del punto di connessione per la forma finale. Lettura/scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

Riprogramma il percorso del connettore in modo che segua il percorso più breve possibile tra le forme a cui è collegato.