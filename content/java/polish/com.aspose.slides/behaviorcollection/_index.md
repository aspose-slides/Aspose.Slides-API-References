---
title: BehaviorCollection
second_title: Aspose.Slides for Java – odniesienie API
description: Reprezentuje kolekcję efektów zachowań.
type: docs
url: /pl/com.aspose.slides/behaviorcollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
```
public class BehaviorCollection implements IBehaviorCollection
```

Reprezentuje kolekcję efektów zachowania.
## Metody

| Metoda | Opis |
| --- | --- |
| [getCount()](#getCount--) | Zwraca liczbę zachowań w kolekcji. |
| [isReadOnly()](#isReadOnly--) | Pobiera wartość wskazującą, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu. |
| [add(IBehavior item)](#add-com.aspose.slides.IBehavior-) | Dodaje nowe zachowanie do kolekcji. |
| [indexOf(IBehavior item)](#indexOf-com.aspose.slides.IBehavior-) | Określa indeks konkretnego elementu na liście. |
| [insert(int index, IBehavior item)](#insert-int-com.aspose.slides.IBehavior-) | Wstawia nowe zachowanie do kolekcji pod określonym indeksem. |
| [copyTo(IBehavior[] array, int arrayIndex)](#copyTo-com.aspose.slides.IBehavior---int-) | Kopiuje elementy [IGenericCollection](../../com.aspose.slides/igenericcollection) do tablicy, zaczynając od określonego indeksu tablicy. |
| [remove(IBehavior item)](#remove-com.aspose.slides.IBehavior-) | Usuwa określone zachowanie z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa zachowanie z kolekcji pod określonym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie zachowania z kolekcji. |
| [contains(IBehavior item)](#contains-com.aspose.slides.IBehavior-) | Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość. |
| [get_Item(int index)](#get-Item-int-) | Zwraca zachowanie pod określonym indeksem. |
| [set_Item(int index, IBehavior value)](#set-Item-int-com.aspose.slides.IBehavior-) | Ustawia zachowanie pod określonym indeksem. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
### getCount() {#getCount--}
```
public final int getCount()
```


Zwraca liczbę zachowań w kolekcji. Typ tylko do odczytu int.

**Zwraca:**
int
### isReadOnly() {#isReadOnly--}
```
public final boolean isReadOnly()
```


Pobiera wartość wskazującą, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu. Typ tylko do odczytu boolean.

**Zwraca:**
boolean - true, jeśli [IGenericCollection](../../com.aspose.slides/igenericcollection) jest tylko do odczytu; w przeciwnym razie false.
### add(IBehavior item) {#add-com.aspose.slides.IBehavior-}
```
public final void add(IBehavior item)
```


Dodaje nowe zachowanie do kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Zachowanie do dodania. |
### indexOf(IBehavior item) {#indexOf-com.aspose.slides.IBehavior-}
```
public final int indexOf(IBehavior item)
```


Określa indeks konkretnego elementu na liście.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Obiekt do odnalezienia na liście. |

**Zwraca:**
int - Indeks elementu, jeśli został znaleziony na liście; w przeciwnym razie -1.
### insert(int index, IBehavior item) {#insert-int-com.aspose.slides.IBehavior-}
```
public final void insert(int index, IBehavior item)
```


Wstawia nowe zachowanie do kolekcji pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks, pod którym nowe zachowanie ma zostać wstawione. |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Zachowanie do wstawienia. |
### copyTo(IBehavior[] array, int arrayIndex) {#copyTo-com.aspose.slides.IBehavior---int-}
```
public final void copyTo(IBehavior[] array, int arrayIndex)
```


Kopiuje elementy [IGenericCollection](../../com.aspose.slides/igenericcollection) do tablicy, zaczynając od określonego indeksu tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | [IBehavior\[\]](../../com.aspose.slides/ibehavior) | Jednowymiarowa tablica, będąca miejscem przeznaczenia elementów kopiowanych z [IGenericCollection](../../com.aspose.slides/igenericcollection). Tablica musi mieć indeksowanie zerowe. |
| arrayIndex | int | Indeks zerowy w tablicy, od którego rozpoczyna się kopiowanie. |
### remove(IBehavior item) {#remove-com.aspose.slides.IBehavior-}
```
public final boolean remove(IBehavior item)
```


Usuwa określone zachowanie z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Zachowanie do usunięcia. |

**Zwraca:**
boolean
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Usuwa zachowanie z kolekcji pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zachowania do usunięcia. |
### clear() {#clear--}
```
public final void clear()
```


Usuwa wszystkie zachowania z kolekcji.
### contains(IBehavior item) {#contains-com.aspose.slides.IBehavior-}
```
public final boolean contains(IBehavior item)
```


Określa, czy [IGenericCollection](../../com.aspose.slides/igenericcollection) zawiera określoną wartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [IBehavior](../../com.aspose.slides/ibehavior) | Obiekt do odnalezienia w [IGenericCollection](../../com.aspose.slides/igenericcollection). |

**Zwraca:**
boolean - true, jeśli element zostanie znaleziony w [IGenericCollection](../../com.aspose.slides/igenericcollection); w przeciwnym razie false.
### get_Item(int index) {#get-Item-int-}
```
public final IBehavior get_Item(int index)
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
public final void set_Item(int index, IBehavior value)
```


Ustawia zachowanie pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks zachowania do zwrócenia. |
| value | [IBehavior](../../com.aspose.slides/ibehavior) |  |
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iterator()
```


Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - IGenericEnumerator, który można wykorzystać do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IBehavior> iteratorJava()
```


Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IBehavior> - java.util.Iterator dla całej kolekcji.