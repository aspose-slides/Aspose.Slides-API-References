---
title: ExtraColorSchemeCollection
second_title: Aspose.Slides dla Java – odniesienie do API
description: Reprezentuje kolekcję dodatkowych schematów kolorów.
type: docs
url: /pl/com.aspose.slides/extracolorschemecollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection), com.aspose.slides.IDOMObject
```
public class ExtraColorSchemeCollection implements IExtraColorSchemeCollection, IDOMObject
```

Reprezentuje kolekcję dodatkowych schematów kolorów.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Zwraca liczbę elementów w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca schemat kolorów według indeksu. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator języka Java dla całej kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do ArrayList jest synchronizowany (bezpieczny dla wątków). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca obiekt, który może być użyty do synchronizacji dostępu do kolekcji. |
### size() {#size--}
```
public final int size()
```

Zwraca liczbę elementów w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IExtraColorScheme get_Item(int index)
```

Zwraca schemat kolorów według indeksu. Tylko do odczytu [ExtraColorScheme](../../com.aspose.slides/extracolorscheme).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IExtraColorScheme](../../com.aspose.slides/iextracolorscheme)
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Zwraca obiekt Parent_Immediate. Tylko do odczytu IDOMObject.

**Zwraca:**
com.aspose.slides.IDOMObject
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IExtraColorScheme> iteratorJava()
```

Zwraca iterator języka Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IExtraColorScheme> - An java.util.Iterator for the entire collection.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje wszystkie elementy kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Indeks początkowy w tablicy. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do ArrayList jest synchronizowany (bezpieczny dla wątków). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca obiekt, który może być użyty do synchronizacji dostępu do kolekcji. Tylko do odczytu Object.

Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object