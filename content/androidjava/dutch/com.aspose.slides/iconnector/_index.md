---
title: IConnector
second_title: Aspose.Slides voor Android via Java API-referentie
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
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Retourneert de vergrendelingen van de vorm. |
| [getConnectorLock()](#getConnectorLock--) | Retourneert de vergrendelingen van de Connector. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Retourneert of stelt de vorm in waaraan het begin van de connector wordt gekoppeld. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Retourneert of stelt de vorm in waaraan het begin van de connector wordt gekoppeld. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Retourneert of stelt de vorm in waaraan het einde van de connector wordt gekoppeld. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Retourneert of stelt de vorm in waaraan het einde van de connector wordt gekoppeld. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Retourneert of stelt de index van de verbindingsplaats voor de startvorm in. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Retourneert of stelt de index van de verbindingsplaats voor de startvorm in. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Retourneert of stelt de index van de verbindingsplaats voor de eindvorm in. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Retourneert of stelt de index van de verbindingsplaats voor de eindvorm in. |
| [reroute()](#reroute--) | Leidt de connector opnieuw zodat hij het kortste mogelijke pad tussen de vormen die hij verbindt neemt. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

Retourneert de vergrendelingen van de vorm. Alleen-lezen [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retour:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

Retourneert de vergrendelingen van de Connector. Alleen-lezen [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Retour:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

Retourneert of stelt de vorm in waaraan het begin van de connector wordt gekoppeld. Lezen/Schrijven [IShape](../../com.aspose.slides/ishape).

**Retour:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

Retourneert of stelt de vorm in waaraan het begin van de connector wordt gekoppeld. Lezen/Schrijven [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

Retourneert of stelt de vorm in waaraan het einde van de connector wordt gekoppeld. Lezen/Schrijven [IShape](../../com.aspose.slides/ishape).

**Retour:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

Retourneert of stelt de vorm in waaraan het einde van de connector wordt gekoppeld. Lezen/Schrijven [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

Retourneert of stelt de index van de verbindingsplaats voor de startvorm in. Lezen/Schrijven long.

**Retour:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

Retourneert of stelt de index van de verbindingsplaats voor de startvorm in. Lezen/Schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

Retourneert of stelt de index van de verbindingsplaats voor de eindvorm in. Lezen/Schrijven long.

**Retour:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

Retourneert of stelt de index van de verbindingsplaats voor de eindvorm in. Lezen/Schrijven long.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

Leidt de connector opnieuw zodat hij het kortste mogelijke pad tussen de vormen die hij verbindt neemt.