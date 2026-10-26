---
title: Connector
second_title: Aspose.Slides pro Java – dokumentace API
description: Reprezentuje spojku.
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

Reprezentuje spojku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Vrací zámky tvaru. |
| [getConnectorLock()](#getConnectorLock--) | Vrací zámky spojky. |
| [getShapeType()](#getShapeType--) | Vrací nebo nastavuje typ AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | Vrací nebo nastavuje typ AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Vrací nebo nastavuje tvar, ke kterému se připojí začátek spojky. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Vrací nebo nastavuje tvar, ke kterému se připojí začátek spojky. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Vrací nebo nastavuje tvar, ke kterému se připojí konec spojky. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Vrací nebo nastavuje tvar, ke kterému se připojí konec spojky. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Vrací nebo nastavuje index místa připojení pro počáteční tvar. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Vrací nebo nastavuje index místa připojení pro počáteční tvar. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Vrací nebo nastavuje index místa připojení pro koncový tvar. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Vrací nebo nastavuje index místa připojení pro koncový tvar. |
| [reroute()](#reroute--) | Přesměruje spojku tak, aby zvolila nejkratší možnou cestu mezi tvary, které spojuje. |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

Vrací zámky tvaru. Pouze pro čtení [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Vrací:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

Vrací zámky spojky. Pouze pro čtení [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Vrací:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

Vrací nebo nastavuje typ AutoShape. Číst/Zapisovat [ShapeType](../../com.aspose.slides/shapetype).

**Vrací:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

Vrací nebo nastavuje typ AutoShape. Číst/Zapisovat [ShapeType](../../com.aspose.slides/shapetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

Vrací nebo nastavuje tvar, ke kterému se připojí začátek spojky. Číst/Zapisovat [IShape](../../com.aspose.slides/ishape).

**Vrací:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

Vrací nebo nastavuje tvar, ke kterému se připojí začátek spojky. Číst/Zapisovat [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

Vrací nebo nastavuje tvar, ke kterému se připojí konec spojky. Číst/Zapisovat [IShape](../../com.aspose.slides/ishape).

**Vrací:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

Vrací nebo nastavuje tvar, ke kterému se připojí konec spojky. Číst/Zapisovat [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

Vrací nebo nastavuje index místa připojení pro počáteční tvar. Číst/Zapisovat long.

**Vrací:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

Vrací nebo nastavuje index místa připojení pro počáteční tvar. Číst/Zapisovat long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

Vrací nebo nastavuje index místa připojení pro koncový tvar. Číst/Zapisovat long.

**Vrací:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionIndex(long value)
```

Vrací nebo nastavuje index místa připojení pro koncový tvar. Číst/Zapisovat long.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public final void reroute()
```

Přesměruje spojku tak, aby zvolila nejkratší možnou cestu mezi tvary, které spojuje.