---
title: SequenceCollection
second_title: Aspose.Slides dla Androida - referencja API w języku Java
description: Reprezentuje kolekcję interaktywnych sekwencji.
type: docs
url: /pl/com.aspose.slides/sequencecollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISequenceCollection](../../com.aspose.slides/isequencecollection)
```
public class SequenceCollection implements ISequenceCollection
```

Reprezentuje kolekcję interaktywnych sekwencji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getCount()](#getCount--) | Zwraca liczbę elementów w kolekcji Tylko do odczytu int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Dodaje nową interaktywną sekwencję. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Usuwa określoną sekwencję z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa sekwencję o podanym indeksie. |
| [clear()](#clear--) | Usuwa wszystkie sekwencje z kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca sekwencję o podanym indeksie. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
### getCount() {#getCount--}
```
public final int getCount()
```


Zwraca liczbę elementów w kolekcji Tylko do odczytu int.

**Zwraca:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public final ISequence add(IShape shapeTrigger)
```


Dodaje nową interaktywną sekwencję. Do odczytu/zapisu [Sequence](../../com.aspose.slides/sequence).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) |  |

**Zwraca:**
[ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public final void remove(ISequence item)
```


Usuwa określoną sekwencję z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sekwencja do usunięcia. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Usuwa sekwencję o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks sekwencji, którą należy usunąć. |

### clear() {#clear--}
```
public final void clear()
```


Usuwa wszystkie sekwencje z kolekcji.

### get_Item(int index) {#get-Item-int-}
```
public final ISequence get_Item(int index)
```


Zwraca sekwencję o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu. |

**Zwraca:**
[ISequence](../../com.aspose.slides/isequence) - Obiekt [ISequence](../../com.aspose.slides/isequence).
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iterator()
```


Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - IGenericEnumerator, który można użyć do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<ISequence> iteratorJava()
```


Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ISequence> - java.util.Iterator dla całej kolekcji.