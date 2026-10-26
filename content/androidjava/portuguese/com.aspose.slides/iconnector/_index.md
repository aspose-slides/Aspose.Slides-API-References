---
title: IConnector
second_title: Aspose.Slides para Android via Referência da API Java
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
| [getShapeLock()](#getShapeLock--) | Returns shape's locks. |
| [getConnectorLock()](#getConnectorLock--) | Returns Connector's locks. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Returns or sets the shape to attach the beginning of the connector to. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Returns or sets the shape to attach the beginning of the connector to. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Returns or sets the shape to attach the end of the connector to. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Returns or sets the shape to attach the end of the connector to. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Returns or sets the index of connection site for start shape. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Returns or sets the index of connection site for start shape. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Returns or sets the index of connection site for end shape. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Returns or sets the index of connection site for end shape. |
| [reroute()](#reroute--) | Reroutes connector so that it take the shortest possible path between the shapes it connect. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```


Retorna os bloqueios da forma. Somente leitura [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retorno:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Retorna os bloqueios do conector. Somente leitura [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retorno:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


Retorna ou define a forma à qual o início do conector deve ser conectado. Leitura/gravação [IShape](../../com.aspose.slides/ishape).

**Retorno:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


Retorna ou define a forma à qual o início do conector deve ser conectado. Leitura/gravação [IShape](../../com.aspose.slides/ishape).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


Retorna ou define a forma à qual o fim do conector deve ser conectado. Leitura/gravação [IShape](../../com.aspose.slides/ishape).

**Retorno:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


Retorna ou define a forma à qual o fim do conector deve ser conectado. Leitura/gravação [IShape](../../com.aspose.slides/ishape).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


Retorna ou define o índice do ponto de conexão para a forma inicial. Leitura/gravação long.

**Retorno:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


Retorna ou define o índice do ponto de conexão para a forma inicial. Leitura/gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


Retorna ou define o índice do ponto de conexão para a forma final. Leitura/gravação long.

**Retorno:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


Retorna ou define o índice do ponto de conexão para a forma final. Leitura/gravação long.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```


Redireciona o conector para que ele siga o caminho mais curto possível entre as formas que conecta.