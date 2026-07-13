---
title: IBehaviorCollection
second_title: Aspose.Slides dla Androida – referencja API Java
description: Reprezentuje kolekcję efektów zachowań.
type: docs
url: /pl/com.aspose.slides/ibehaviorcollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface IBehaviorCollection extends System.Collections.Generic.IGenericEnumerable<IBehavior>
```

Reprezentuje kolekcję efektów zachowań.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca zachowanie pod określonym indeksem. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Zwraca zachowanie pod określonym indeksem. |
| [getCount()](#getCount--) | Zwraca liczbę zachowań w kolekcji. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Dodaje nowe zachowanie do kolekcji. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Określa indeks określonego elementu na liście. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Wstawia nowe zachowanie do kolekcji pod określonym indeksem. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Usuwa określone zachowanie z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa zachowanie z kolekcji pod określonym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie zachowania z kolekcji. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IBehavior get_Item(int index)
```


Zwraca zachowanie pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zachowania do zwrócenia. |

**Zwraca:**
[IBehavior](../../com.aspose.slides/ibehavior) - Zachowanie animacji.
### set_Item(int index, IBehavior value) {#set-Item-int-com.aspose.slides.IBehavior-}
```
public abstract void set_Item(int index, IBehavior value)
```


Zwraca zachowanie pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zachowania do zwrócenia. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |

### getCount() {#getCount--}
```
public abstract int getCount()
```


Zwraca liczbę zachowań w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public abstract void add(IBehavior item)
```


Dodaje nowe zachowanie do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Zachowanie do dodania. |

### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public abstract int indexOf(IBehavior item)
```


Określa indeks określonego elementu na liście.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Obiekt do zlokalizowania na liście. |

**Zwraca:**
int - Indeks elementu, jeśli zostanie znaleziony na liście; w przeciwnym razie -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public abstract void insert(int index, IBehavior item)
```


Wstawia nowe zachowanie do kolekcji pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks, pod którym ma zostać wstawione nowe zachowanie. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Zachowanie do wstawienia. |

### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public abstract boolean remove(IBehavior item)
```


Usuwa określone zachowanie z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Zachowanie do usunięcia. |

**Zwraca:**
boolean - true jeśli zachowanie zostało pomyślnie usunięte
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Usuwa zachowanie z kolekcji pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zachowania do usunięcia. |

### clear() {#clear--}
```
public abstract void clear()
```


Usuwa wszystkie zachowania z kolekcji.

### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public abstract boolean contains(IBehavior item)
```


Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Obiekt do zlokalizowania w [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**
boolean - true jeśli element zostanie znaleziony w [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie false.