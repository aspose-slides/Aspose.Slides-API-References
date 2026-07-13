---
title: ISequenceCollection
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Reprezentuje kolekcję interaktywnych sekwencji.
type: docs
url: /pl/com.aspose.slides/isequencecollection/
---
**Wszystkie implementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ISequenceCollection extends System.Collections.Generic.IGenericEnumerable<ISequence>
```

Reprezentuje kolekcję interaktywnych sekwencji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getCount()](#getCount--) | Zwraca liczbę elementów w kolekcji Tylko do odczytu int. |
| [add(IShape shapeTrigger)](#add-com.aspose.slides.IShape-) | Dodaje nową interaktywną sekwencję. |
| [remove(ISequence item)](#remove-com.aspose.slides.ISequence-) | Usuwa określoną sekwencję z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa sekwencję pod określonym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie sekwencje z kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca sekwencję pod określonym indeksem. |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Zwraca liczbę elementów w kolekcji Tylko do odczytu int.

**Zwraca:**
int
### add(IShape shapeTrigger) {#add-com.aspose.slides.IShape-}
```
public abstract ISequence add(IShape shapeTrigger)
```


Dodaje nową interaktywną sekwencję.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| shapeTrigger | [IShape](../../com.aspose.slides/ishape) | Obiekt kształtu [IShape](../../com.aspose.slides/ishape) |

**Zwraca:**
[ISequence](../../com.aspose.slides/isequence) - Nowa sekwencja [ISequence](../../com.aspose.slides/isequence)
### remove(ISequence item) {#remove-com.aspose.slides.ISequence-}
```
public abstract void remove(ISequence item)
```


Usuwa określoną sekwencję z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| item | [ISequence](../../com.aspose.slides/isequence) | Sekwencja do usunięcia. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Usuwa sekwencję pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu w kolekcji int |

### clear() {#clear--}
```
public abstract void clear()
```


Usuwa wszystkie sekwencje z kolekcji.

### get_Item(int index) {#get-Item-int-}
```
public abstract ISequence get_Item(int index)
```


Zwraca sekwencję pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks elementu. |

**Zwraca:**
[ISequence](../../com.aspose.slides/isequence) - Obiekt [ISequence](../../com.aspose.slides/isequence).