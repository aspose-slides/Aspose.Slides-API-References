---
title: Connector
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een connector voor.
type: docs
url: /nl/com.aspose.slides/connector/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Stelt een connector voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Retourneert de vergrendelingen van de vorm. |
| [getConnectorLock()](#getConnectorLock--) | Retourneert de vergrendelingen van de connector. |
| [getShapeType()](#getShapeType--) | Retourneert of stelt het AutoShape-type in. |
| [setShapeType(int value)](#setShapeType-int-) | Retourneert of stelt het AutoShape-type in. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Retourneert of stelt de vorm in waaraan het begin van de connector wordt gekoppeld. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Retourneert of stelt de vorm in waaraan het begin van de connector wordt gekoppeld. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Retourneert of stelt de vorm in waaraan het einde van de connector wordt gekoppeld. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Retourneert of stelt de vorm in waaraan het einde van de connector wordt gekoppeld. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Retourneert of stelt de index van de verbindingplaats voor de startvorm in. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Retourneert of stelt de index van de verbindingplaats voor de startvorm in. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Retourneert of stelt de index van de verbindingplaats voor de eindvorm in. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Retourneert of stelt de index van de verbindingplaats voor de eindvorm in. |
| [reroute()](#reroute--) | Herleidt de connector zodat hij het kortste mogelijke pad tussen de vormen die hij verbindt neemt. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```


Retourneert de vergrendelingen van de vorm. Alleen-lezen [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retour:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```


Retourneert de vergrendelingen van de connector. Alleen-lezen [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retour:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Retourneert of stelt het AutoShape-type in. Lezen/schrijven [ShapeType](../../com.aspose.slides/shapetype).

**Retour:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Retourneert of stelt het AutoShape-type in. Lezen/schrijven [ShapeType](../../com.aspose.slides/shapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```


Retourneert of stelt de vorm in waaraan het begin van de connector wordt gekoppeld. Lezen/schrijven [IShape](../../com.aspose.slides/ishape).

**Retour:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```


Retourneert of stelt de vorm in waaraan het begin van de connector wordt gekoppeld. Lezen/schrijven [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```


Retourneert of stelt de vorm in waaraan het einde van de connector wordt gekoppeld. Lezen/schrijven [IShape](../../com.aspose.slides/ishape).

**Retour:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```


Retourneert of stelt de vorm in waaraan het einde van de connector wordt gekoppeld. Lezen/schrijven [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```


Retourneert of stelt de index van de verbindingplaats voor de startvorm in. Lezen/schrijven long.

**Retour:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```


Retourneert of stelt de index van de verbindingplaats voor de startvorm in. Lezen/schrijven long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```


Retourneert of stelt de index van de verbindingplaats voor de eindvorm in. Lezen/schrijven long.

**Retour:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```


Retourneert of stelt de index van de verbindingplaats voor de eindvorm in. Lezen/schrijven long.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```


Herleidt de connector zodat hij het kortste mogelijke pad tussen de vormen die hij verbindt neemt.