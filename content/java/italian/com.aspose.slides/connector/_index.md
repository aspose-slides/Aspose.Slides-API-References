---
title: Connector
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un connettore.
type: docs
url: /it/com.aspose.slides/connector/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Tutte le interfacce implementate:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Rappresenta un connettore.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Restituisce i lock della forma. |
| [getConnectorLock()](#getConnectorLock--) | Restituisce i lock del connettore. |
| [getShapeType()](#getShapeType--) | Restituisce o imposta il tipo AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | Restituisce o imposta il tipo AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Restituisce o imposta la forma a cui collegare l'inizio del connettore. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Restituisce o imposta la forma a cui collegare l'inizio del connettore. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Restituisce o imposta la forma a cui collegare la fine del connettore. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Restituisce o imposta la forma a cui collegare la fine del connettore. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Restituisce o imposta l'indice del punto di connessione per la forma di partenza. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Restituisce o imposta l'indice del punto di connessione per la forma di partenza. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Restituisce o imposta l'indice del punto di connessione per la forma di arrivo. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Restituisce o imposta l'indice del punto di connessione per la forma di arrivo. |
| [reroute()](#reroute--) | Reruta il connettore in modo che segua il percorso più breve possibile tra le forme collegate. |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

Restituisce i lock della forma. Solo lettura [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Restituisce:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

Restituisce i lock del connettore. Solo lettura [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Restituisce:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Restituisce o imposta il tipo AutoShape. Lettura/scrittura [ShapeType](../../com.aspose.slides/shapetype).

**Restituisce:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Restituisce o imposta il tipo AutoShape. Lettura/scrittura [ShapeType](../../com.aspose.slides/shapetype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

Restituisce o imposta la forma a cui collegare l'inizio del connettore. Lettura/scrittura [IShape](../../com.aspose.slides/ishape).

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

Restituisce o imposta la forma a cui collegare l'inizio del connettore. Lettura/scrittura [IShape](../../com.aspose.slides/ishape).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

Restituisce o imposta la forma a cui collegare la fine del connettore. Lettura/scrittura [IShape](../../com.aspose.slides/ishape).

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

Restituisce o imposta la forma a cui collegare la fine del connettore. Lettura/scrittura [IShape](../../com.aspose.slides/ishape).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

Restituisce o imposta l'indice del punto di connessione per la forma di partenza. Lettura/scrittura long.

**Restituisce:**
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

Restituisce o imposta l'indice del punto di connessione per la forma di partenza. Lettura/scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

Restituisce o imposta l'indice del punto di connessione per la forma di arrivo. Lettura/scrittura long.

**Restituisce:**
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

Restituisce o imposta l'indice del punto di connessione per la forma di arrivo. Lettura/scrittura long.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```

Reruta il connettore in modo che segua il percorso più breve possibile tra le forme collegate.