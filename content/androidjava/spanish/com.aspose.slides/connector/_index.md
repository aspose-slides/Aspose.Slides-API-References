---
title: Connector
second_title: Aspose.Slides para Android mediante la referencia de API Java
description: Representa un conector.
type: docs
url: /es/com.aspose.slides/connector/
---
**Herencia:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Todas las interfaces implementadas:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Representa un conector.
## Métodos

| Método | Descripción |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Devuelve los bloqueos de la forma. |
| [getConnectorLock()](#getConnectorLock--) | Devuelve los bloqueos del conector. |
| [getShapeType()](#getShapeType--) | Devuelve o establece el tipo AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | Devuelve o establece el tipo AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Devuelve o establece la forma a la que se adjunta el comienzo del conector. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Devuelve o establece la forma a la que se adjunta el comienzo del conector. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Devuelve o establece la forma a la que se adjunta el final del conector. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Devuelve o establece la forma a la que se adjunta el final del conector. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Devuelve o establece el índice del sitio de conexión para la forma inicial. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Devuelve o establece el índice del sitio de conexión para la forma inicial. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Devuelve o establece el índice del sitio de conexión para la forma final. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Devuelve o establece el índice del sitio de conexión para la forma final. |
| [reroute()](#reroute--) | Redirige el conector para que tome la ruta más corta posible entre las formas que conecta. |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

Devuelve los bloqueos de la forma. Solo lectura [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Devuelve:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

Devuelve los bloqueos del conector. Solo lectura [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Devuelve:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Devuelve o establece el tipo AutoShape. Lectura/escritura [ShapeType](../../com.aspose.slides/shapetype).

**Devuelve:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Devuelve o establece el tipo AutoShape. Lectura/escritura [ShapeType](../../com.aspose.slides/shapetype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

Devuelve o establece la forma a la que se adjunta el comienzo del conector. Lectura/escritura [IShape](../../com.aspose.slides/ishape).

**Devuelve:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

Devuelve o establece la forma a la que se adjunta el comienzo del conector. Lectura/escritura [IShape](../../com.aspose.slides/ishape).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

Devuelve o establece la forma a la que se adjunta el final del conector. Lectura/escritura [IShape](../../com.aspose.slides/ishape).

**Devuelve:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

Devuelve o establece la forma a la que se adjunta el final del conector. Lectura/escritura [IShape](../../com.aspose.slides/ishape).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

Devuelve o establece el índice del sitio de conexión para la forma inicial. Lectura/escritura long.

**Devuelve:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

Devuelve o establece el índice del sitio de conexión para la forma inicial. Lectura/escritura long.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

Devuelve o establece el índice del sitio de conexión para la forma final. Lectura/escritura long.

**Devuelve:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

Devuelve o establece el índice del sitio de conexión para la forma final. Lectura/escritura long.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```

Redirige el conector para que tome la ruta más corta posible entre las formas que conecta.