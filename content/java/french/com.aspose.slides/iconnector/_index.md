---
title: IConnector
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente un connecteur.
type: docs
url: /fr/com.aspose.slides/iconnector/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Représente un connecteur.
## Méthodes

| Méthode | Description |
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


Renvoie les verrous du shape. Lecture seule [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retourne :**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Renvoie les verrous du Connector. Lecture seule [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retourne :**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


Renvoie ou définit le shape à attacher au début du connector. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Retourne :**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


Renvoie ou définit le shape à attacher au début du connector. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


Renvoie ou définit le shape à attacher à la fin du connector. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Retourne :**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


Renvoie ou définit le shape à attacher à la fin du connector. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


Renvoie ou définit l'index du site de connexion pour le shape de départ. Lecture/écriture long.

**Retourne :**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


Renvoie ou définit l'index du site de connexion pour le shape de départ. Lecture/écriture long.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


Renvoie ou définit l'index du site de connexion pour le shape de fin. Lecture/écriture long.

**Retourne :**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


Renvoie ou définit l'index du site de connexion pour le shape de fin. Lecture/écriture long.

**Paramètres :**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```


Routage du connector afin qu'il prenne le chemin le plus court possible entre les shapes qu'il connecte.