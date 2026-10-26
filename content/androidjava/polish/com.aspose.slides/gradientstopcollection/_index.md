---
title: GradientStopCollection
second_title: Aspose.Slides dla Androida – odwołanie do API Java
description: Reprezentuje kolekcję punktów gradientu.
type: docs
url: /pl/com.aspose.slides/gradientstopcollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IGradientStopCollection](../../com.aspose.slides/igradientstopcollection)
```
public final class GradientStopCollection extends PVIObject implements IGradientStopCollection
```

Reprezentuje kolekcję punktów gradientu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [size()](#size--) | Zwraca liczbę punktów gradientu w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Zwraca punkt gradientu o podanym indeksie. |
| [add(float position, Integer color)](#add-float-java.lang.Integer-) | Tworzy nowy punkt gradientu i dodaje go na koniec kolekcji. |
| [addPresetColor(float position, int presetColor)](#addPresetColor-float-int-) | Tworzy nowy punkt gradientu i dodaje go na koniec kolekcji. |
| [addSchemeColor(float position, int schemeColor)](#addSchemeColor-float-int-) | Tworzy nowy punkt gradientu i dodaje go na koniec kolekcji. |
| [insert(int index, float position, Integer color)](#insert-int-float-java.lang.Integer-) | Tworzy nowy punkt gradientu i wstawia go w określonym indeksie w kolekcji. |
| [insertPresetColor(int index, float position, int presetColor)](#insertPresetColor-int-float-int-) | Tworzy nowy punkt gradientu i wstawia go w określonym indeksie w kolekcji. |
| [insertSchemeColor(int index, float position, int schemeColor)](#insertSchemeColor-int-float-int-) | Tworzy nowy punkt gradientu i wstawia go w określonym indeksie w kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa punkt gradientu o podanym indeksie. |
| [clear()](#clear--) | Usuwa wszystkie punkty gradientu z kolekcji. |
| [iterator()](#iterator--) | Zwraca iterator, który przegląda kolekcję. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator java dla całej kolekcji. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wszystkie elementy z kolekcji do określonej tablicy. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo-bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Wersja. Tylko do odczytu long.

**Zwraca:**
long
### size() {#size--}
```
public final int size()
```


Zwraca liczbę punktów gradientu w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IGradientStop get_Item(int index)
```


Zwraca punkt gradientu o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IGradientStop](../../com.aspose.slides/igradientstop)
### add(float position, Integer color) {#add-float-java.lang.Integer-}
```
public final IGradientStop add(float position, Integer color)
```


Tworzy nowy punkt gradientu i dodaje go na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | float | Pozycja nowego punktu gradientu. |
| color | java.lang.Integer | Kolor nowego punktu gradientu. |

**Zwraca:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks nowego punktu gradientu w kolekcji.
### addPresetColor(float position, int presetColor) {#addPresetColor-float-int-}
```
public final IGradientStop addPresetColor(float position, int presetColor)
```


Tworzy nowy punkt gradientu i dodaje go na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | float | Pozycja nowego punktu gradientu. |
| presetColor | int | Kolor nowego punktu gradientu. |

**Zwraca:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks nowego punktu gradientu w kolekcji.
### addSchemeColor(float position, int schemeColor) {#addSchemeColor-float-int-}
```
public final IGradientStop addSchemeColor(float position, int schemeColor)
```


Tworzy nowy punkt gradientu i dodaje go na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| position | float | Pozycja nowego punktu gradientu. |
| schemeColor | int | Kolor nowego punktu gradientu. |

**Zwraca:**
[IGradientStop](../../com.aspose.slides/igradientstop) - Indeks nowego punktu gradientu w kolekcji.
### insert(int index, float position, Integer color) {#insert-int-float-java.lang.Integer-}
```
public final void insert(int index, float position, Integer color)
```


Tworzy nowy punkt gradientu i wstawia go w określonym indeksie w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks w kolekcji, w którym nowy punkt gradientu zostanie wstawiony. |
| position | float | Pozycja nowego punktu gradientu. |
| color | java.lang.Integer | Kolor nowego punktu gradientu. |

### insertPresetColor(int index, float position, int presetColor) {#insertPresetColor-int-float-int-}
```
public final void insertPresetColor(int index, float position, int presetColor)
```


Tworzy nowy punkt gradientu i wstawia go w określonym indeksie w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks w kolekcji, w którym nowy punkt gradientu zostanie wstawiony. |
| position | float | Pozycja nowego punktu gradientu. |
| presetColor | int | Kolor nowego punktu gradientu. |

### insertSchemeColor(int index, float position, int schemeColor) {#insertSchemeColor-int-float-int-}
```
public final void insertSchemeColor(int index, float position, int schemeColor)
```


Tworzy nowy punkt gradientu i wstawia go w określonym indeksie w kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks w kolekcji, w którym nowy punkt gradientu zostanie wstawiony. |
| position | float | Pozycja nowego punktu gradientu. |
| schemeColor | int | Kolor nowego punktu gradientu. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Usuwa punkt gradientu o podanym indeksie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks punktu gradientu, który ma zostać usunięty. |

### clear() {#clear--}
```
public final void clear()
```


Usuwa wszystkie punkty gradientu z kolekcji.

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iterator()
```


Zwraca iterator, który przegląda kolekcję.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - IGenericEnumerator, który może być użyty do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IGradientStop> iteratorJava()
```


Zwraca iterator java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IGradientStop> - java.util.Iterator dla całej kolekcji.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Kopiuje wszystkie elementy z kolekcji do określonej tablicy.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica docelowa. |
| index | int | Indeks początkowy w tablicy docelowej. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo-bezpieczny). Tylko do odczytu boolean.

**Zwraca:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Zwraca korzeń synchronizacji. Tylko do odczytu Object.

**Zwraca:**
java.lang.Object