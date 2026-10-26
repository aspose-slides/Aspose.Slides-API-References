---
title: PortionCollection
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje kolekcję fragmentów.
type: docs
url: /pl/com.aspose.slides/portioncollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IPortionCollection](../../com.aspose.slides/iportioncollection)
```
public final class PortionCollection extends DomObject<Paragraph> implements IPortionCollection
```

Reprezentuje kolekcję fragmentów.
## Metody

| Metoda | Opis |
| --- | --- |
| [getCount()](#getCount--) | Pobiera liczbę elementów faktycznie znajdujących się w kolekcji. |
| [isReadOnly()](#isReadOnly--) | Pobiera wartość wskazującą, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu. |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o podanym indeksie. |
| [set_Item(int index, IPortion value)](#set-Item-int-com.aspose.slides.IPortion-) | Pobiera element o podanym indeksie. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Dodaje Portion na koniec kolekcji. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Określa indeks określonego elementu w liście. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Wstawia Portion do kolekcji w określonym indeksie. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość. |
| [copyTo(IPortion[] array, int arrayIndex)](#copyTo-com.aspose.slides.IPortion---int-) | Kopiuje elementy [IGenericCollection](../../com.aspose.slides/igenericcollection) do tablicy, zaczynając od określonego indeksu tablicy. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Usuwa pierwsze wystąpienie określonego obiektu z [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o podanym indeksie z kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator języka Java dla całej kolekcji. |
### getCount() {#getCount--}
```
public final int getCount()
```


Pobiera liczbę elementów faktycznie zawartych w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Pobiera wartość wskazującą, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu. Tylko do odczytu boolean.

**Zwraca:**
boolean - true jeśli [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu; w przeciwnym razie false.
### get_Item(int index) {#get-Item-int-}
```
public final IPortion get_Item(int index)
```


Pobiera element o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IPortion](../../com.aspose.slides/iportion)
### set_Item(int index, IPortion value) {#set-Item-int-com.aspose.slides.IPortion-}
```
public final void set_Item(int index, IPortion value)
```


Pobiera element o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |
| value | [IPortion](../../com.aspose.slides/iportion) |  |

### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public final void add(IPortion value)
```


Dodaje Portion na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion, który ma zostać dodany na koniec kolekcji. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public final int indexOf(IPortion item)
```


Określa indeks określonego elementu w liście.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Obiekt, który ma zostać odnaleziony w liście. |

**Zwraca:**
int - Indeks elementu, jeśli został znaleziony na liście; w przeciwnym razie -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public final void insert(int index, IPortion value)
```


Wstawia Portion do kolekcji w określonym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze, w którym Portion powinien zostać wstawiony. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion do wstawienia. |

### clear() {#clear--}
```
public final void clear()
```


Usuwa wszystkie elementy z kolekcji.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public final boolean contains(IPortion item)
```


Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Obiekt, który ma zostać odnaleziony w [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**
boolean - true jeśli element zostanie znaleziony w [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie false.
### copyTo(IPortion[] array, int arrayIndex) {#copyTo-com.aspose.slides.IPortion---int-}
```
public final void copyTo(IPortion[] array, int arrayIndex)
```


Kopiuje elementy [IGenericCollection](../../com.aspose.slides/igenericcollection) do tablicy, zaczynając od określonego indeksu tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | [IPortion\[\]](../../com.aspose.slides/iportion) | Jednowymiarowa tablica, która jest miejscem docelowym elementów skopiowanych z [IGenericCollection](../../com.aspose.slides/igenericcollection). Tablica musi mieć indeksowanie zerowe. |
| arrayIndex | int | Indeks bazujący na zerze w tablicy, od którego rozpoczyna się kopiowanie. |

### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public final boolean remove(IPortion item)
```


Usuwa pierwsze wystąpienie określonego obiektu z [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Obiekt, który ma zostać usunięty z [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**
boolean - true jeśli element został pomyślnie usunięty z [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie false. Ta metoda również zwraca false, jeśli element nie zostanie znaleziony w oryginalnym [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Usuwa element o podanym indeksie z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks bazujący na zerze elementu, który ma zostać usunięty. |

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iterator()
```


Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - IGenericEnumerator, który może być używany do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IPortion> iteratorJava()
```


Zwraca iterator języka Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IPortion> - java.util.Iterator dla całej kolekcji.