---
title: IAudioCollection
second_title: Aspose.Slides dla Androida przy użyciu interfejsu API Java
description: Reprezentuje kolekcję osadzonych plików audio.
type: docs
url: /pl/com.aspose.slides/iaudiocollection/
---
**Wszystkie zaimplementowane interfejsy:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Reprezentuje kolekcję osadzonych plików audio.
## Metody

| Metoda | Opis |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Zwraca element o podanym indeksie. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Dodaje kopię pliku audio z innej prezentacji. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Tworzy i dodaje audio do prezentacji ze strumienia. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Tworzy i dodaje audio do prezentacji ze strumienia. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Tworzy i dodaje audio do prezentacji z tablicy bajtów. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```


Zwraca element o podanym indeksie. Tylko do odczytu [IAudio](../../com.aspose.slides/iaudio).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| index | int |  |

**Zwraca:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```


Dodaje kopię pliku audio z innej prezentacji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Źródłowy audio. |

**Zwraca:**
[IAudio](../../com.aspose.slides/iaudio) - Dodane audio.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
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
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Tworzy i dodaje audio do prezentacji ze strumienia.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| stream | java.io.InputStream | Strumień, z którego dodać audio wideo. |
| loadingStreamBehavior | int | [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) zastosowany do strumienia. |

**Zwraca:**
[IAudio](../../com.aspose.slides/iaudio) - Dodane audio.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```


Tworzy i dodaje audio do prezentacji z tablicy bajtów.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| audioData | byte[] | Bajty audio. |

**Zwraca:**
[IAudio](../../com.aspose.slides/iaudio) - Dodane audio.