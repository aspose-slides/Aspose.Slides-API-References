---
title: IConnector
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje spojku.
type: docs
url: /cs/com.aspose.slides/iconnector/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Reprezentuje spojku.
## Metody

| Metoda | Popis |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Vrací zámky tvaru. |
| [getConnectorLock()](#getConnectorLock--) | Vrací zámky spojky. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Vrací nebo nastavuje tvar, ke kterému je připojen začátek spojky. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Vrací nebo nastavuje tvar, ke kterému je připojen začátek spojky. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Vrací nebo nastavuje tvar, ke kterému je připojen konec spojky. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Vrací nebo nastavuje tvar, ke kterému je připojen konec spojky. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Vrací nebo nastavuje index připojovacího místa pro počáteční tvar. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Vrací nebo nastavuje index připojovacího místa pro počáteční tvar. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Vrací nebo nastavuje index připojovacího místa pro koncový tvar. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Vrací nebo nastavuje index připojovacího místa pro koncový tvar. |
| [reroute()](#reroute--) | Přepočítá trasu spojky tak, aby zvolila nejkratší možnou cestu mezi tvary, které spojuje. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```


Vrací zámky tvaru. Pouze pro čtení [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Vrací:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Vrací zámky spojky. Pouze pro čtení [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Vrací:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


Vrací nebo nastavuje tvar, ke kterému je připojen začátek spojky. Čtení/Zápis [IShape](../../com.aspose.slides/ishape).

**Vrací:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


Vrací nebo nastavuje tvar, ke kterému je připojen začátek spojky. Čtení/Zápis [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


Vrací nebo nastavuje tvar, ke kterému je připojen konec spojky. Čtení/Zápis [IShape](../../com.aspose.slides/ishape).

**Vrací:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


Vrací nebo nastavuje tvar, ke kterému je připojen konec spojky. Čtení/Zápis [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


Vrací nebo nastavuje index připojovacího místa pro počáteční tvar. Čtení/Zápis long.

**Vrací:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


Vrací nebo nastavuje index připojovacího místa pro počáteční tvar. Čtení/Zápis long.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


Vrací nebo nastavuje index připojovacího místa pro koncový tvar. Čtení/Zápis long.

**Vrací:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


Vrací nebo nastavuje index připojovacího místa pro koncový tvar. Čtení/Zápis long.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```


Přepočítá trasu spojky tak, aby zvolila nejkratší možnou cestu mezi tvary, které spojuje.