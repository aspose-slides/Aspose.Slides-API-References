---
title: Connector
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente un connecteur.
type: docs
url: /fr/com.aspose.slides/connector/
---
**Héritage:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Toutes les interfaces implémentées:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Représente un connecteur.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Renvoie les verrous de la forme. |
| [getConnectorLock()](#getConnectorLock--) | Renvoie les verrous du connecteur. |
| [getShapeType()](#getShapeType--) | Renvoie ou définit le type AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | Renvoie ou définit le type AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Renvoie ou définit la forme à laquelle attacher le début du connecteur. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Renvoie ou définit la forme à laquelle attacher le début du connecteur. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Renvoie ou définit la forme à laquelle attacher la fin du connecteur. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Renvoie ou définit la forme à laquelle attacher la fin du connecteur. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Renvoie ou définit l'index du point de connexion pour la forme de départ. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Renvoie ou définit l'index du point de connexion pour la forme de départ. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Renvoie ou définit l'index du point de connexion pour la forme d'arrivée. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Renvoie ou définit l'index du point de connexion pour la forme d'arrivée. |
| [reroute()](#reroute--) | Routage du connecteur afin qu'il prenne le chemin le plus court possible entre les formes qu'il relie. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```


Renvoie les verrous de la forme. Lecture seule [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Renvoie:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```


Renvoie les verrous du connecteur. Lecture seule [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Renvoie:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Renvoie ou définit le type AutoShape. Lecture/écriture [ShapeType](../../com.aspose.slides/shapetype).

**Renvoie:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Renvoie ou définit le type AutoShape. Lecture/écriture [ShapeType](../../com.aspose.slides/shapetype).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```


Renvoie ou définit la forme à laquelle attacher le début du connecteur. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Renvoie:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```


Renvoie ou définit la forme à laquelle attacher le début du connecteur. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```


Renvoie ou définit la forme à laquelle attacher la fin du connecteur. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Renvoie:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```


Renvoie ou définit la forme à laquelle attacher la fin du connecteur. Lecture/écriture [IShape](../../com.aspose.slides/ishape).

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```


Renvoie ou définit l'index du point de connexion pour la forme de départ. Lecture/écriture long.

**Renvoie:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```


Renvoie ou définit l'index du point de connexion pour la forme de départ. Lecture/écriture long.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```


Renvoie ou définit l'index du point de connexion pour la forme d'arrivée. Lecture/écriture long.

**Renvoie:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```


Renvoie ou définit l'index du point de connexion pour la forme d'arrivée. Lecture/écriture long.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```


Routage du connecteur afin qu'il prenne le chemin le plus court possible entre les formes qu'il relie.