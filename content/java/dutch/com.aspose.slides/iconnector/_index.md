---
title: IConnector
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een connector voor.
type: docs
url: /nl/com.aspose.slides/iconnector/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Stelt een connector voor.
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Retourneert shape's locks. |
| [getConnectorLock()](#getConnectorLock--) | Retourneert Connector's locks. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Retourneert of stelt de shape in om het begin van de connector eraan te koppelen. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Retourneert of stelt de shape in om het begin van de connector eraan te koppelen. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Retourneert of stelt de shape in om het einde van de connector eraan te koppelen. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Retourneert of stelt de shape in om het einde van de connector eraan te koppelen. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Retourneert of stelt de index van de connection site voor start shape in. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Retourneert of stelt de index van de connection site voor start shape in. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Retourneert of stelt de index van de connection site voor end shape in. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Retourneert of stelt de index van de connection site voor end shape in. |
| [reroute()](#reroute--) | Routet de connector opnieuw zodat hij het kortste mogelijke pad tussen de shapes neemt die hij verbindt. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```


Retourneert shape's locks. Alleen-lezen [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retour:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Retourneert Connector's locks. Alleen-lezen [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retour:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


Retourneert of stelt de shape in om het begin van de connector eraan te koppelen. Lezen/schrijven [IShape](../../com.aspose.slides/ishape).

**Retour:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


Retourneert of stelt de shape in om het begin van de connector eraan te koppelen. Lezen/schrijven [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


Retourneert of stelt de shape in om het einde van de connector eraan te koppelen. Lezen/schrijven [IShape](../../com.aspose.slides/ishape).

**Retour:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


Retourneert of stelt de shape in om het einde van de connector eraan te koppelen. Lezen/schrijven [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


Retourneert of stelt de index van de connection site voor start shape in. Lezen/schrijven long.

**Retour:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


Retourneert of stelt de index van de connection site voor start shape in. Lezen/schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


Retourneert of stelt de index van de connection site voor end shape in. Lezen/schrijven long.

**Retour:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


Retourneert of stelt de index van de connection site voor end shape in. Lezen/schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```


Routet de connector opnieuw zodat hij het kortste mogelijke pad tussen de shapes neemt die hij verbindt.