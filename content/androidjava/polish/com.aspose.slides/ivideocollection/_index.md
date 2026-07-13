---
title: IVideoCollection
second_title: Aspose.Slides dla Androida poprzez odwołanie API Java
description: Reprezentuje kolekcję obiektów Video.
type: docs
url: /pl/com.aspose.slides/ivideocollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Reprezentuje kolekcję obiektów Video.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Pobiera element pod określonym indeksem. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Dodaje kopię pliku wideo z innej prezentacji. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Tworzy i dodaje wideo do prezentacji ze strumienia. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Tworzy i dodaje wideo do prezentacji z tablicy bajtów. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```


Pobiera element pod określonym indeksem. Tylko do odczytu [IVideo](../../com.aspose.slides/ivideo).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```


Dodaje kopię pliku wideo z innej prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Wideo źródłowe. |

**Zwraca:**
[IVideo](../../com.aspose.slides/ivideo) - Dodane wideo.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Tworzy i dodaje wideo do prezentacji ze strumienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień, z którego dodać plik wideo. |
| loadingStreamBehavior | int | Zachowanie, które zostanie zastosowane do strumienia. |

**Zwraca:**
[IVideo](../../com.aspose.slides/ivideo) - Dodane [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


Tworzy i dodaje wideo do prezentacji z tablicy bajtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| videoData | byte[] | Bajty wideo. |

**Zwraca:**
[IVideo](../../com.aspose.slides/ivideo) - Dodane wideo.