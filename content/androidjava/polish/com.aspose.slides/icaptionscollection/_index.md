---
title: ICaptionsCollection
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Reprezentuje kolekcję napisów zamkniętych.
type: docs
url: /pl/com.aspose.slides/icaptionscollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable
```
public interface ICaptionsCollection extends System.Collections.Generic.IGenericEnumerable<ICaptions>
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
### get_Item(int index) {#get-Item-int-}
```
public abstract ICaptions get_Item(int index)
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
public abstract ICaptions add(String label, String filePath)
```

Dodaje napisy zamknięte WebVTT na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| label | java.lang.String | Etykieta napisów zamkniętych. |
| filePath | java.lang.String | Ścieżka do pliku WebVTT. |

**Zwraca:**
[ICaptions](../../com.aspose.slides/icaptions) - Dodana [ICaptions](../../com.aspose.slides/icaptions) instancja.
### add(String label, InputStream stream) {#add-java.lang.String-java.io.InputStream-}
```
public abstract ICaptions add(String label, InputStream stream)
```

Dodaje napisy zamknięte WebVTT na koniec kolekcji ze strumienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| label | java.lang.String | Etykieta napisów zamkniętych. |
| stream | java.io.InputStream | Strumień wejściowy zawierający dane w formacie WebVTT. |

**Zwraca:**
[ICaptions](../../com.aspose.slides/icaptions) - Dodana [ICaptions](../../com.aspose.slides/icaptions) instancja.
### remove(ICaptions captions) {#remove-com.aspose.slides.ICaptions-}
```
public abstract void remove(ICaptions captions)
```

Usuwa określone napisy zamknięte z kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| captions | [ICaptions](../../com.aspose.slides/icaptions) | Napisy zamknięte do usunięcia. |

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Usuwa napisy zamknięte pod określonym indeksem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int | Indeks napisów zamkniętych do usunięcia. |

### clear() {#clear--}
```
public abstract void clear()
```

Usuwa wszystkie napisy zamknięte z kolekcji.

### getCount() {#getCount--}
```
public abstract int getCount()
```

Zwraca liczbę elementów w kolekcji. Tylko do odczytu int .

**Zwraca:**
int