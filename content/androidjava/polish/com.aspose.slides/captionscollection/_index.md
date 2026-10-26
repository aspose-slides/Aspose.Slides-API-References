---
title: CaptionsCollection
second_title: Aspose.Slides dla Androida – odwołanie do API Java
description: Reprezentuje kolekcję napisów zamkniętych.
type: docs
url: /pl/com.aspose.slides/captionscollection/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ICaptionsCollection](../../com.aspose.slides/icaptionscollection)
```
public final class CaptionsCollection implements ICaptionsCollection
```

Reprezentuje kolekcję napisów zamkniętych.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca napisy zamknięte pod określonym indeksem. |
| [add(String label, String filePath)](#add-java.lang.String-java.lang.String-) | Dodaje napisy zamknięte WebVTT na koniec kolekcji. |
| [add(String label, InputStream stream)](#add-java.lang.String-java.io.InputStream-) | Dodaje napisy zamknięte WebVTT na koniec kolekcji ze strumienia. |
| [remove(ICaptions captions)](#remove-com.aspose.slides.ICaptions-) | Usuwa określone napisy zamknięte z kolekcji. |
| [removeAt(int index)](#removeAt-int-) | Usuwa napisy zamknięte pod określonym indeksem. |
| [clear()](#clear--) | Usuwa wszystkie napisy zamknięte z kolekcji. |
| [getCount()](#getCount--) | Zwraca liczbę elementów w kolekcji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
### get_Item(int index) {#get-Item-int-}
```
public final ICaptions get_Item(int index)
```

Zwraca napisy zamknięte pod określonym indeksem. Tylko do odczytu [ICaptions](../../com.aspose.slides/icaptions).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[ICaptions](../../com.aspose.slides/icaptions)
### add(String label, String filePath) {#add-java.lang.String-java.lang.String-}
```
public final ICaptions add(String label, String filePath)
```

Dodaje napisy zamknięte WebVTT na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| label | java.lang.String | Etykieta napisów zamkniętych. |
| filePath | java.lang.String | Ścieżka do pliku WebVTT. |

**Zwraca:**
[ICaptions](../../com.aspose.slides/icaptions) - Dodany [ICaptions](../../com.aspose.slides/icaptions) instancja.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public final ICaptions add(String label, InputStream stream)
```

Dodaje napisy zamknięte WebVTT na koniec kolekcji ze strumienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| label | java.lang.String | Etykieta napisów zamkniętych. |
| stream | java.io.InputStream | Strumień wejściowy zawierający dane w formacie WebVTT. |

**Zwraca:**
[ICaptions](../../com.aspose.slides/icaptions) - Dodany [ICaptions](../../com.aspose.slides/icaptions) instancja.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public final void remove(ICaptions captions)
```

Usuwa określone napisy zamknięte z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Napisy zamknięte do usunięcia. |

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Usuwa napisy zamknięte pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks napisów zamkniętych do usunięcia. |

### clear() {#clear--}
```
public final void clear()
```

Usuwa wszystkie napisy zamknięte z kolekcji.

### getCount() {#getCount--}
```
public final int getCount()
```

Zwraca liczbę elementów w kolekcji. Tylko do odczytu  int .

**Zwraca:**
int
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<ICaptions> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.ICaptions> - A  System.Collections.Generic.IEnumerator1  który może być użyty do iteracji po kolekcji.