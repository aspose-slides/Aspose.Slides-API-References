---
title: IConnector
second_title: Odwołanie API Aspose.Slides dla Javy
description: Reprezentuje łącznik.
type: docs
url: /pl/com.aspose.slides/iconnector/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Reprezentuje łącznik.
## Metody

| Metoda | Opis |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Zwraca blokady shape. |
| [getConnectorLock()](#getConnectorLock--) | Zwraca blokady Connector. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Zwraca lub ustawia shape, do którego ma być przyłączony początek łącznika. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Zwraca lub ustawia shape, do którego ma być przyłączony początek łącznika. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Zwraca lub ustawia shape, do którego ma być przyłączony koniec łącznika. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Zwraca lub ustawia shape, do którego ma być przyłączony koniec łącznika. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Zwraca lub ustawia indeks miejsca połączenia dla shape początkowego. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Zwraca lub ustawia indeks miejsca połączenia dla shape początkowego. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Zwraca lub ustawia indeks miejsca połączenia dla shape końcowego. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Zwraca lub ustawia indeks miejsca połączenia dla shape końcowego. |
| [reroute()](#reroute--) | Przebudowuje łącznik, aby przyjął najkrótszą możliwą ścieżkę między połączonymi shape. |

### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

Zwraca blokady shape. Tylko do odczytu [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Zwraca:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

Zwraca blokady Connector. Tylko do odczytu [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Zwraca:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

Zwraca lub ustawia shape, do którego ma być przyłączony początek łącznika. Odczyt/zapis [IShape](../../com.aspose.slides/ishape).

**Zwraca:**
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

Zwraca lub ustawia shape, do którego ma być przyłączony początek łącznika. Odczyt/zapis [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

Zwraca lub ustawia shape, do którego ma być przyłączony koniec łącznika. Odczyt/zapis [IShape](../../com.aspose.slides/ishape).

**Zwraca:**
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

Zwraca lub ustawia shape, do którego ma być przyłączony koniec łącznika. Odczyt/zapis [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

Zwraca lub ustawia indeks miejsca połączenia dla shape początkowego. Odczyt/zapis long.

**Zwraca:**
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

Zwraca lub ustawia indeks miejsca połączenia dla shape początkowego. Odczyt/zapis long.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

Zwraca lub ustawia indeks miejsca połączenia dla shape końcowego. Odczyt/zapis long.

**Zwraca:**
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

Zwraca lub ustawia indeks miejsca połączenia dla shape końcowego. Odczyt/zapis long.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```

Przebudowuje łącznik, aby przyjął najkrótszą możliwą ścieżkę między połączonymi shape.