---
title: Connector
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um conector.
type: docs
url: /pt/com.aspose.slides/connector/
---
**Herança:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Representa um conector.
## Métodos

| Método | Descrição |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Retorna os bloqueios da forma. |
| [getConnectorLock()](#getConnectorLock--) | Retorna os bloqueios do conector. |
| [getShapeType()](#getShapeType--) | Retorna ou define o tipo AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | Retorna ou define o tipo AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Retorna ou define a forma para anexar o início do conector. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Retorna ou define a forma para anexar o início do conector. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Retorna ou define a forma para anexar o final do conector. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Retorna ou define a forma para anexar o final do conector. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Retorna ou define o índice do ponto de conexão para a forma inicial. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Retorna ou define o índice do ponto de conexão para a forma inicial. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Retorna ou define o índice do ponto de conexão para a forma final. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Retorna ou define o índice do ponto de conexão para a forma final. |
| [reroute()](#reroute--) | Redireciona o conector de modo que ele siga o caminho mais curto possível entre as formas que conecta. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```


Retorna os bloqueios da forma. Somente leitura [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retorna:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```


Retorna os bloqueios do conector. Somente leitura [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retorna:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Retorna ou define o tipo AutoShape. Leitura/gravação [ShapeType](../../com.aspose.slides/shapetype).

**Retorna:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Retorna ou define o tipo AutoShape. Leitura/gravação [ShapeType](../../com.aspose.slides/shapetype).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```


Retorna ou define a forma para anexar o início do conector. Leitura/gravação [IShape](../../com.aspose.slides/ishape).

**Retorna:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```


Retorna ou define a forma para anexar o início do conector. Leitura/gravação [IShape](../../com.aspose.slides/ishape).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```


Retorna ou define a forma para anexar o final do conector. Leitura/gravação [IShape](../../com.aspose.slides/ishape).

**Retorna:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```


Retorna ou define a forma para anexar o final do conector. Leitura/gravação [IShape](../../com.aspose.slides/ishape).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```


Retorna ou define o índice do ponto de conexão para a forma inicial. Leitura/gravação long.

**Retorna:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```


Retorna ou define o índice do ponto de conexão para a forma inicial. Leitura/gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```


Retorna ou define o índice do ponto de conexão para a forma final. Leitura/gravação long.

**Retorna:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```


Retorna ou define o índice do ponto de conexão para a forma final. Leitura/gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```


Redireciona o conector de modo que ele siga o caminho mais curto possível entre as formas que conecta.