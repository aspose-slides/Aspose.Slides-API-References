---
title: VideoCollection
second_title: Aspose.Slides dla Androida przez interfejs API Java
description: Reprezentuje kolekcję obiektów Video.
type: docs
url: /pl/com.aspose.slides/videocollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Reprezentuje kolekcję obiektów Video.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Zwraca liczbę plików wideo w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o określonym indeksie. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Dodaje kopię pliku wideo z innej prezentacji. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Tworzy i dodaje wideo do prezentacji ze strumienia. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Tworzy i dodaje wideo do prezentacji z tablicy bajtów. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje wideo do określonej tablicy zaczynając od podanego indeksu. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest zsynchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca java iterator dla całej kolekcji. |
### size() {#size--}
```
public final int size()
```

Zwraca liczbę plików wideo w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```

Pobiera element o określonym indeksie. Tylko do odczytu [IVideo](../../com.aspose.slides/ivideo).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```

Dodaje kopię pliku wideo z innej prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Źródłowe wideo. |

**Zwraca:**
[IVideo](../../com.aspose.slides/ivideo) - Dodany wideo.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Tworzy i dodaje wideo do prezentacji ze strumienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień, z którego dodać plik wideo. |
| loadingStreamBehavior | int | Zachowanie, które zostanie zastosowane do strumienia. |

**Zwraca:**
[IVideo](../../com.aspose.slides/ivideo) - Dodany [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Tworzy i dodaje wideo do prezentacji z tablicy bajtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| videoData | byte[] | Bajty wideo. |

**Zwraca:**
[IVideo](../../com.aspose.slides/ivideo) - Dodany wideo.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje wideo do określonej tablicy zaczynając od podanego indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica. |
| index | int | Indeks. |

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
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - IGenericEnumerator, który może być użyty do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Zwraca java iterator dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - java.util.Iterator dla całej kolekcji.