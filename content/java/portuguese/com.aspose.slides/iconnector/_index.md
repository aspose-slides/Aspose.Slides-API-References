---
title: IConnector
second_title: Referência da API Aspose.Slides para Java
description: Representa um conector.
type: docs
url: /pt/com.aspose.slides/iconnector/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Representa um conector.
## Métodos

| Método | Descrição |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Retorna os bloqueios do shape. |
| [getConnectorLock()](#getConnectorLock--) | Retorna os bloqueios do Connector. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Retorna ou define o shape ao qual anexar o início do connector. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Retorna ou define o shape ao qual anexar o início do connector. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Retorna ou define o shape ao qual anexar o fim do connector. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Retorna ou define o shape ao qual anexar o fim do connector. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Retorna ou define o índice do site de conexão para o shape de início. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Retorna ou define o índice do site de conexão para o shape de início. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Retorna ou define o índice do site de conexão para o shape de fim. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Retorna ou define o índice do site de conexão para o shape de fim. |
| [reroute()](#reroute--) | Redireciona o conector de modo que ele siga o caminho mais curto possível entre os shapes que conecta. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```


Retorna os bloqueios do shape. Somente leitura [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retorna:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Retorna os bloqueios do Connector. Somente leitura [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retorna:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


Retorna ou define o shape ao qual anexar o início do connector. Leitura/gravação [IShape](../../com.aspose.slides/ishape).

**Retorna:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


Retorna ou define o shape ao qual anexar o início do connector. Leitura/gravação [IShape](../../com.aspose.slides/ishape).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


Retorna ou define o shape ao qual anexar o fim do connector. Leitura/gravação [IShape](../../com.aspose.slides/ishape).

**Retorna:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


Retorna ou define o shape ao qual anexar o fim do connector. Leitura/gravação [IShape](../../com.aspose.slides/ishape).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


Retorna ou define o índice do site de conexão para o shape de início. Leitura/gravação long.

**Retorna:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


Retorna ou define o índice do site de conexão para o shape de início. Leitura/gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


Retorna ou define o índice do site de conexão para o shape de fim. Leitura/gravação long.

**Retorna:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


Retorna ou define o índice do site de conexão para o shape de fim. Leitura/gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```


Redireciona o conector de modo que ele siga o caminho mais curto possível entre os shapes que conecta.