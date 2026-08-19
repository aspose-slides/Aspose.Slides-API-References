---
title: Connector
second_title: Aspose.Slides voor Java API-referentie
description: Vertegenwoordigt een connector.
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

Representeert een connector.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Retourneert shape's locks. |
| [getConnectorLock()](#getConnectorLock--) | Retourneert connector's locks. |
| [getShapeType()](#getShapeType--) | Retourneert of stelt het AutoShape-type in. |
| [setShapeType(int value)](#setShapeType-int-) | Retourneert of stelt het AutoShape-type in. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Retourneert of stelt de shape in om het begin van de connector aan te bevestigen. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Retourneert of stelt de shape in om het begin van de connector aan te bevestigen. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Retourneert of stelt de shape in om het einde van de connector aan te bevestigen. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Retourneert of stelt de shape in om het einde van de connector aan te bevestigen. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Retourneert of stelt de index van de verbindingsplaats voor de startshape in. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Retourneert of stelt de index van de verbindingsplaats voor de startshape in. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Retourneert of stelt de index van de verbindingsplaats voor de eindshape in. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Retourneert of stelt de index van de verbindingsplaats voor de eindshape in. |
| [reroute()](#reroute--) | Routet de connector opnieuw zodat deze het kortste mogelijke pad tussen de shapes die het verbindt, neemt. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

Retourneert shape's locks. Alleen-lezen [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retourneert:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

Retourneert connector's locks. Alleen-lezen [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retourneert:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Retourneert of stelt het AutoShape-type in. Lezen/Schrijven [ShapeType](../../com.aspose.slides/shapetype).

**Retourneert:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Retourneert of stelt het AutoShape-type in. Lezen/Schrijven [ShapeType](../../com.aspose.slides/shapetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

Retourneert of stelt de shape in om het begin van de connector aan te bevestigen. Lezen/Schrijven [IShape](../../com.aspose.slides/ishape).

**Retourneert:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

Retourneert of stelt de shape in om het begin van de connector aan te bevestigen. Lezen/Schrijven [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

Retourneert of stelt de shape in om het einde van de connector aan te bevestigen. Lezen/Schrijven [IShape](../../com.aspose.slides/ishape).

**Retourneert:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

Retourneert of stelt de shape in om het einde van de connector aan te bevestigen. Lezen/Schrijven [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

Retourneert of stelt de index van de verbindingsplaats voor de startshape in. Lezen/Schrijven long.

**Retourneert:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

Retourneert of stelt de index van de verbindingsplaats voor de startshape in. Lezen/Schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

Retourneert of stelt de index van de verbindingsplaats voor de eindshape in. Lezen/Schrijven long.

**Retourneert:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

Retourneert of stelt de index van de verbindingsplaats voor de eindshape in. Lezen/Schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public final void reroute()
```

Routet de connector opnieuw zodat deze het kortste mogelijke pad tussen de shapes die het verbindt, neemt.