---
title: Connector
second_title: Aspose.Slides dla Androida – odniesienie do Java API
description: Reprezentuje łącznik.
type: docs
url: /pl/com.aspose.slides/connector/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Wszystkie implementowane interfejsy:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Reprezentuje łącznik.
## Metody

| Method | Description |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Zwraca blokady kształtu. |
| [getConnectorLock()](#getConnectorLock--) | Zwraca blokady łącznika. |
| [getShapeType()](#getShapeType--) | Zwraca lub ustawia typ AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | Zwraca lub ustawia typ AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Zwraca lub ustawia kształt, do którego podłączyć początek łącznika. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Zwraca lub ustawia kształt, do którego podłączyć początek łącznika. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Zwraca lub ustawia kształt, do którego podłączyć koniec łącznika. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Zwraca lub ustawia kształt, do którego podłączyć koniec łącznika. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Zwraca lub ustawia indeks miejsca połączenia dla kształtu początkowego. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Zwraca lub ustawia indeks miejsca połączenia dla kształtu początkowego. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Zwraca lub ustawia indeks miejsca połączenia dla kształtu końcowego. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Zwraca lub ustawia indeks miejsca połączenia dla kształtu końcowego. |
| [reroute()](#reroute--) | Przekierowuje łącznik tak, aby przyjął najkrótszą możliwą ścieżkę pomiędzy kształtami, które łączy. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```


Zwraca blokady kształtu. Tylko do odczytu [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Zwraca:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```


Zwraca blokady łącznika. Tylko do odczytu [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Zwraca:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```


Zwraca lub ustawia typ AutoShape. Odczyt/zapis [ShapeType](../../com.aspose.slides/shapetype).

**Zwraca:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```


Zwraca lub ustawia typ AutoShape. Odczyt/zapis [ShapeType](../../com.aspose.slides/shapetype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```


Zwraca lub ustawia kształt, do którego podłączyć początek łącznika. Odczyt/zapis [IShape](../../com.aspose.slides/ishape).

**Zwraca:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```


Zwraca lub ustawia kształt, do którego podłączyć początek łącznika. Odczyt/zapis [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```


Zwraca lub ustawia kształt, do którego podłączyć koniec łącznika. Odczyt/zapis [IShape](../../com.aspose.slides/ishape).

**Zwraca:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```


Zwraca lub ustawia kształt, do którego podłączyć koniec łącznika. Odczyt/zapis [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```


Zwraca lub ustawia indeks miejsca połączenia dla kształtu początkowego. Odczyt/zapis long.

**Zwraca:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```


Zwraca lub ustawia indeks miejsca połączenia dla kształtu początkowego. Odczyt/zapis long.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```


Zwraca lub ustawia indeks miejsca połączenia dla kształtu końcowego. Odczyt/zapis long.

**Zwraca:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```


Zwraca lub ustawia indeks miejsca połączenia dla kształtu końcowego. Odczyt/zapis long.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```


Przekierowuje łącznik tak, aby przyjął najkrótszą możliwą ścieżkę pomiędzy kształtami, które łączy.