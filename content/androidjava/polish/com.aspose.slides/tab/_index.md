---
title: Tab
second_title: Aspose.Slides dla Androida za pośrednictwem interfejsu API Java
description: Reprezentuje tabulację dla tekstu.
type: docs
url: /pl/com.aspose.slides/tab/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ITab](../../com.aspose.slides/itab)
```
public final class Tab extends PVIObject implements ITab
```

Reprezentuje tabulację dla tekstu.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [Tab(double position, int align)](#Tab-double-int-) | Tworzy nową Tab |
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPosition()](#getPosition--) | Zwraca lub ustawia pozycję tabulacji. |
| [setPosition(double value)](#setPosition-double-) | Zwraca lub ustawia pozycję tabulacji. |
| [getAlignment()](#getAlignment--) | Zwraca lub ustawia styl wyrównania tabulacji. |
| [setAlignment(int value)](#setAlignment-int-) | Zwraca lub ustawia styl wyrównania tabulacji. |
| [compareTo(Object obj)](#compareTo-java.lang.Object-) | Porównuje bieżącą instancję z innym obiektem tego samego typu. |
### Tab(double position, int align) {#Tab-double-int-}
```
public Tab(double position, int align)
```


Tworzy nową Tab

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | double | Pozycja Tab. |
| align | int | Wyrównanie. |

### getVersion() {#getVersion--}
```
public long getVersion()
```


Wersja. Tylko do odczytu long.

**Zwraca:**
long
### getPosition() {#getPosition--}
```
public final double getPosition()
```


Zwraca lub ustawia pozycję tabulacji. Przypisanie tej właściwości może zmienić indeks tabulacji w kolekcji i unieważnić Enumerator. Odczyt/zapis double.

**Zwraca:**
double
### setPosition(double value) {#setPosition-double-}
```
public final void setPosition(double value)
```


Zwraca lub ustawia pozycję tabulacji. Przypisanie tej właściwości może zmienić indeks tabulacji w kolekcji i unieważnić Enumerator. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getAlignment() {#getAlignment--}
```
public final int getAlignment()
```


Zwraca lub ustawia styl wyrównania tabulacji. Odczyt/zapis [TabAlignment](../../com.aspose.slides/tabalignment).

**Zwraca:**
int
### setAlignment(int value) {#setAlignment-int-}
```
public final void setAlignment(int value)
```


Zwraca lub ustawia styl wyrównania tabulacji. Odczyt/zapis [TabAlignment](../../com.aspose.slides/tabalignment).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### compareTo(Object obj) {#compareTo-java.lang.Object-}
```
public final int compareTo(Object obj)
```


Porównuje bieżącą instancję z innym obiektem tego samego typu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt do porównania z tą instancją. |

**Zwraca:**
int - 32-bitowa liczba całkowita, która wskazuje względny porządek porównywanych elementów. Wartość zwracana ma następujące znaczenia:

* < 0 - Ta instancja jest mniejsza niż obj.
* = 0 - Ta instancja jest równa obj.
* > 0 - Ta instancja jest większa niż obj.