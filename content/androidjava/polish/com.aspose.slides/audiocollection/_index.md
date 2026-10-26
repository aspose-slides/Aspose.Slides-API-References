---
title: AudioCollection
second_title: Aspose.Slides dla Androida poprzez odniesienie API Java
description: Reprezentuje kolekcję osadzonych plików audio.
type: docs
url: /pl/com.aspose.slides/audiocollection/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Reprezentuje kolekcję osadzonych plików audio.
## Metody

| Metoda | Opis |
| --- | --- |
| [size()](#size--) | Zwraca liczbę plików audio w kolekcji. |
| [get_Item(int index)](#get-Item-int-) | Pobiera element o określonym indeksie. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Dodaje kopię pliku audio z innej prezentacji. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Tworzy i dodaje audio do prezentacji ze strumienia. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Tworzy i dodaje audio do prezentacji ze strumienia. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Tworzy i dodaje audio do prezentacji z tablicy bajtów. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Kopiuje audio do określonej tablicy zaczynając od podanego indeksu. |
| [isSynchronized()](#isSynchronized--) | Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo bezpieczny). |
| [getSyncRoot()](#getSyncRoot--) | Zwraca korzeń synchronizacji. |
| [iterator()](#iterator--) | Zwraca enumerator, który iteruje po kolekcji. |
| [iteratorJava()](#iteratorJava--) | Zwraca iterator Java dla całej kolekcji. |
### size() {#size--}
```
public final int size()
```

Zwraca liczbę plików audio w kolekcji. Tylko do odczytu int.

**Zwraca:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

Pobiera element o określonym indeksie. Tylko do odczytu [IAudio](../../com.aspose.slides/iaudio).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

Dodaje kopię pliku audio z innej prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio źródłowe. |

**Zwraca:**
[IAudio](../../com.aspose.slides/iaudio) - Dodane audio.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

Tworzy i dodaje audio do prezentacji ze strumienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień, z którego dodać audio. |

**Zwraca:**
[IAudio](../../com.aspose.slides/iaudio) - Dodane audio.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Tworzy i dodaje audio do prezentacji ze strumienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień, z którego dodać audio wideo. |
| loadingStreamBehavior | int | Zachowanie, które zostanie zastosowane do strumienia. |

**Zwraca:**
[IAudio](../../com.aspose.slides/iaudio) - Dodane audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

Tworzy i dodaje audio do prezentacji z tablicy bajtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| audioData | byte[] | Bajty audio. |

**Zwraca:**
[IAudio](../../com.aspose.slides/iaudio) - Dodane audio.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Kopiuje audio do określonej tablicy zaczynając od podanego indeksu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Tablica. |
| index | int | Indeks. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Zwraca wartość wskazującą, czy dostęp do kolekcji jest synchronizowany (wątkowo bezpieczny). Tylko do odczytu boolean.

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
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Zwraca enumerator, który iteruje po kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - IGenericEnumerator, który może być użyty do iteracji po kolekcji.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Zwraca iterator Java dla całej kolekcji.

**Zwraca:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - java.util.Iterator dla całej kolekcji.