---
title: VideoCollection
second_title: Aspose.Slides dla Java – odniesienie API
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
| [size()](#size--) | Returns a number of video files in the collection. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Adds a copy of an video file from an another presentation. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Creates and adds a video to a presentation from stream. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Creates and adds a video to a presentation from byte array. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies videos to specified array starting from specified index. |
| [isSynchronized()](#isSynchronized--) | Returns a value indicating whether access to the collection is synchronized (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Returns a synchronization root. |
| [iterator()](#iterator--) | Returns an enumerator that iterates through the collection. |
| [iteratorJava()](#iteratorJava--) | Returns a java iterator for the entire collection. |
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

Pobiera element o podanym indeksie. Tylko do odczytu [IVideo](../../com.aspose.slides/ivideo).

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
| video | [IVideo](../../com.aspose.slides/ivideo) | Source video. |

**Zwraca:**
[IVideo](../../com.aspose.slides/ivideo) - Dodane wideo.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Tworzy i dodaje wideo do prezentacji ze strumienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Stream to add video file from. |
| loadingStreamBehavior | int | The behavior which will be applied to the stream. |

**Zwraca:**
[IVideo](../../com.aspose.slides/ivideo) - Dodane [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Tworzy i dodaje wideo do prezentacji z tablicy bajtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| videoData | byte[] | Video bytes. |

**Zwraca:**
[IVideo](../../com.aspose.slides/ivideo) - Dodane wideo.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje wideo do określonej tablicy zaczynając od podanego indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Index. |

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
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Zwraca iterator Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - An java.util.Iterator for the entire collection.