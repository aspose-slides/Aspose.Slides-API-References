---
title: Connector
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Reprezentuje konektor.
type: docs
url: /cs/com.aspose.slides/connector/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Všechny implementované rozhraní:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Reprezentuje konektor.

## Metody

| Metoda | Popis |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Vrací shape's zámky. |
| [getConnectorLock()](#getConnectorLock--) | Vrací connector's zámky. |
| [getShapeType()](#getShapeType--) | Vrací nebo nastavuje AutoShape type. |
| [setShapeType(int value)](#setShapeType-int-) | Vrací nebo nastavuje AutoShape type. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Vrací nebo nastavuje shape to attach the beginning of the connector to. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Vrací nebo nastavuje shape to attach the beginning of the connector to. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Vrací nebo nastavuje shape to attach the end of the connector to. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Vrací nebo nastavuje shape to attach the end of the connector to. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Vrací nebo nastavuje index of connection site for start shape. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Vrací nebo nastavuje index of connection site for start shape. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Vrací nebo nastavuje index of connection site for end shape. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Vrací nebo nastavuje index of connection site for end shape. |
| [reroute()](#reroute--) | Přesměruje konektor tak, aby zvolil nejkratší možnou cestu mezi spojenými tvary. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

Vrací shape's zámky. Pouze pro čtení [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Vrací:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

Vrací connector's zámky. Pouze pro čtení [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Vrací:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Vrací nebo nastavuje AutoShape type. Čtení/Zápis [ShapeType](../../com.aspose.slides/shapetype).

**Vrací:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Vrací nebo nastavuje AutoShape type. Čtení/Zápis [ShapeType](../../com.aspose.slides/shapetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

Vrací nebo nastavuje shape to attach the beginning of the connector to. Čtení/Zápis [IShape](../../com.aspose.slides/ishape).

**Vrací:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

Vrací nebo nastavuje shape to attach the beginning of the connector to. Čtení/Zápis [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

Vrací nebo nastavuje shape to attach the end of the connector to. Čtení/Zápis [IShape](../../com.aspose.slides/ishape).

**Vrací:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

Vrací nebo nastavuje shape to attach the end of the connector to. Čtení/Zápis [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

Vrací nebo nastavuje index of connection site for start shape. Čtení/Zápis long.

**Vrací:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

Vrací nebo nastavuje index of connection site for start shape. Čtení/Zápis long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

Vrací nebo nastavuje index of connection site for end shape. Čtení/Zápis long.

**Vrací:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

Vrací nebo nastavuje index of connection site for end shape. Čtení/Zápis long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public final void reroute()
```

Přesměruje konektor tak, aby zvolil nejkratší možnou cestu mezi spojenými tvary.