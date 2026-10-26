---
title: IConnector
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa un conector.
type: docs
url: /es/com.aspose.slides/iconnector/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Representa un conector.
## Métodos

| Método | Descripción |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Devuelve los bloqueos de shape. |
| [getConnectorLock()](#getConnectorLock--) | Devuelve los bloqueos de Connector. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Devuelve o establece la shape a la que se adjunta el inicio del conector. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Devuelve o establece la shape a la que se adjunta el inicio del conector. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Devuelve o establece la shape a la que se adjunta el final del conector. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Devuelve o establece la shape a la que se adjunta el final del conector. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Devuelve o establece el índice del sitio de conexión para la shape de inicio. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Devuelve o establece el índice del sitio de conexión para la shape de inicio. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Devuelve o establece el índice del sitio de conexión para la shape de final. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Devuelve o establece el índice del sitio de conexión para la shape de final. |
| [reroute()](#reroute--) | Redirige el conector para que tome la ruta más corta posible entre las shapes que conecta. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```


Devuelve los bloqueos de shape. Solo lectura [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Devuelve:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Devuelve los bloqueos de Connector. Solo lectura [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Devuelve:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


Devuelve o establece la shape a la que se adjunta el inicio del conector. Lectura/escritura [IShape](../../com.aspose.slides/ishape).

**Devuelve:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


Devuelve o establece la shape a la que se adjunta el inicio del conector. Lectura/escritura [IShape](../../com.aspose.slides/ishape).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


Devuelve o establece la shape a la que se adjunta el final del conector. Lectura/escritura [IShape](../../com.aspose.slides/ishape).

**Devuelve:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


Devuelve o establece la shape a la que se adjunta el final del conector. Lectura/escritura [IShape](../../com.aspose.slides/ishape).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


Devuelve o establece el índice del sitio de conexión para la shape de inicio. Lectura/escritura long.

**Devuelve:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


Devuelve o establece el índice del sitio de conexión para la shape de inicio. Lectura/escritura long.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


Devuelve o establece el índice del sitio de conexión para la shape de final. Lectura/escritura long.

**Devuelve:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


Devuelve o establece el índice del sitio de conexión para la shape de final. Lectura/escritura long.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```


Redirige el conector para que tome la ruta más corta posible entre las shapes que conecta.