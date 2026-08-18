---
title: FontSubstRuleCollection
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje kolekcję zamiany czcionek.
type: docs
url: /pl/com.aspose.slides/fontsubstrulecollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IFontSubstRuleCollection](../../com.aspose.slides/ifontsubstrulecollection)
```
public class FontSubstRuleCollection implements IFontSubstRuleCollection
```

Reprezentuje kolekcję zamiany czcionek.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [FontSubstRuleCollection()](#FontSubstRuleCollection--) |  |
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Pobiera liczbę elementów faktycznie znajdujących się w kolekcji. |
| [add(IFontSubstRule value)](#add-com.aspose.slides.IFontSubstRule-) | Dodaje nową regułę zamiany czcionek do kolekcji |
| [remove(IFontSubstRule value)](#remove-com.aspose.slides.IFontSubstRule-) | Usuwa pierwsze wystąpienie określonego obiektu z kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o podanym indeksie. |
| [iterator()](#iterator--) | Zwraca enumerator iterujący po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Java dla całej kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
### FontSubstRuleCollection() {#FontSubstRuleCollection--}
```
public FontSubstRuleCollection()
```

### size() {#size--}
```
public final int size()
```

Pobiera liczbę elementów faktycznie znajdujących się w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### add(IFontSubstRule value) {#add-com.aspose.slides.IFontSubstRule-}
```
public final void add(IFontSubstRule value)
```

Dodaje nową regułę zamiany czcionek do kolekcji

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) |  |

### remove(IFontSubstRule value) {#remove-com.aspose.slides.IFontSubstRule-}
```
public final void remove(IFontSubstRule value)
```

Usuwa pierwsze wystąpienie określonego obiektu z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontSubstRule](../../com.aspose.slides/ifontsubstrule) | Reguła zamiany czcionek do usunięcia z kolekcji. |

### get_Item(int index) {#get-Item-int-}
```
public final IFontSubstRule get_Item(int index)
```

Pobiera element o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iterator()
```

Zwraca enumerator iterujący po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - IGenericEnumerator, który można użyć do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IFontSubstRule> iteratorJava()
```

Zwraca iterator Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IFontSubstRule> - java.util.Iterator dla całej kolekcji.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Początkowy indeks w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object