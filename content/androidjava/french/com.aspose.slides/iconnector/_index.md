---
title: IConnector
second_title: Aspose.Slides pour Android via la référence API Java
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
| [getShapeLock()](#getShapeLock--) | Renvoie les verrous de la forme. |
| [getConnectorLock()](#getConnectorLock--) | Renvoie les verrous du Connecteur. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Renvoie ou définit la forme à laquelle attacher le début du connecteur. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Renvoie ou définit la forme à laquelle attacher le début du connecteur. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Renvoie ou définit la forme à laquelle attacher la fin du connecteur. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Renvoie ou définit la forme à laquelle attacher la fin du connecteur. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Renvoie ou définit l’index du site de connexion pour la forme de départ. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Renvoie ou définit l’index du site de connexion pour la forme de départ. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Renvoie ou définit l’index du site de connexion pour la forme de fin. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Renvoie ou définit l’index du site de connexion pour la forme de fin. |
| [reroute()](#reroute--) | Reroute le connecteur afin qu’il suive le chemin le plus court possible entre les formes qu’il connecte. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```


Renvoie les verrous de la forme. Lecture seule [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Renvoie :**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Renvoie les verrous du Connecteur. Lecture seule [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Renvoie :**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


Renvoie ou définit la forme à laquelle attacher le début du connecteur. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Renvoie :**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


Renvoie ou définit la forme à laquelle attacher le début du connecteur. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


Renvoie ou définit la forme à laquelle attacher la fin du connecteur. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Renvoie :**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


Renvoie ou définit la forme à laquelle attacher la fin du connecteur. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


Renvoie ou définit l’index du site de connexion pour la forme de départ. Lecture/écriture long.

**Renvoie :**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


Renvoie ou définit l’index du site de connexion pour la forme de départ. Lecture/écriture long.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


Renvoie ou définit l’index du site de connexion pour la forme de fin. Lecture/écriture long.

**Renvoie :**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


Renvoie ou définit l’index du site de connexion pour la forme de fin. Lecture/écriture long.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```


Reroute le connecteur afin qu’il suive le chemin le plus court possible entre les formes qu’il connecte.