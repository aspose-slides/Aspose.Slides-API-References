---
title: IPortionCollection
second_title: Aspose.Slides dla Androida za pośrednictwem referencji API Java
description: Reprezentuje kolekcję fragmentów.
type: docs
url: /pl/com.aspose.slides/iportioncollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IPortionCollection extends System.Collections.Generic.IGenericEnumerable<IPortion>
```

Reprezentuje kolekcję fragmentów.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o podanym indeksie. |
| [getCount()](#getCount--) | Pobiera liczbę elementów faktycznie znajdujących się w kolekcji. |
| [add(IPortion value)](#add-com.aspose.slides.IPortion-) | Dodaje Portion na koniec kolekcji. |
| [indexOf(IPortion item)](#indexOf-com.aspose.slides.IPortion-) | Określa indeks konkretnego Portion w kolekcji. |
| [insert(int index, IPortion value)](#insert-int-com.aspose.slides.IPortion-) | Wstawia Portion do kolekcji pod podanym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie elementy z kolekcji. |
| [contains(IPortion item)](#contains-com.aspose.slides.IPortion-) | Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość. |
| [remove(IPortion item)](#remove-com.aspose.slides.IPortion-) | Usuwa pierwsze wystąpienie określonego obiektu z [IGenericCollection](../../com.aspose.slides/igenericcollection). |
| [removeAt(int index)](#removeAt-int-) | Usuwa element o podanym indeksie z kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IPortion get_Item(int index)
```

Pobiera element o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IPortion](../../com.aspose.slides/iportion)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Pobiera liczbę elementów faktycznie znajdujących się w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### add(IPortion value) {#add-com.aspose.slides.IPortion-}
```
public abstract void add(IPortion value)
```

Dodaje Portion na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion do dodania na koniec kolekcji. |

### indexOf(IPortion item) {#indexOf-com.aspose.slides.IPortion-}
```
public abstract int indexOf(IPortion item)
```

Określa indeks konkretnego Portion w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Portion do odnalezienia w kolekcji. |

**Zwraca:**
int - Indeks elementu, jeśli został znaleziony w kolekcji; w przeciwnym razie -1.
### insert(int index, IPortion value) {#insert-int-com.aspose.slides.IPortion-}
```
public abstract void insert(int index, IPortion value)
```

Wstawia Portion do kolekcji pod podanym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy, pod którym Portion ma być wstawiony. |
| value | [IPortion](../../com.aspose.slides/iportion) | Portion do wstawienia. |

### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie elementy z kolekcji.

### contains(IPortion item) {#contains-com.aspose.slides.IPortion-}
```
public abstract boolean contains(IPortion item)
```

Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Obiekt do zlokalizowania w [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**
boolean - true, jeśli element został znaleziony w [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie false.
### remove(IPortion item) {#remove-com.aspose.slides.IPortion-}
```
public abstract boolean remove(IPortion item)
```

Usuwa pierwsze wystąpienie określonego obiektu z [IGenericCollection](../../com.aspose.slides/igenericcollection).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IPortion](../../com.aspose.slides/iportion) | Obiekt do usunięcia z [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**
boolean - true, jeśli element został pomyślnie usunięty z [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie false. Ta metoda również zwraca false, jeśli element nie został znaleziony w oryginalnym [IGenericCollection](../../com.aspose.slides/igenericcollection).
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa element o podanym indeksie z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zerowy elementu do usunięcia. |