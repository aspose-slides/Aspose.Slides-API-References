---
title: AudioCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una collezione di file audio incorporati.
type: docs
url: /it/com.aspose.slides/audiocollection/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Rappresenta una collezione di file audio incorporati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce il numero di file audio nella collezione. |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Aggiunge una copia di un file audio da un'altra presentazione. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Crea e aggiunge un audio a una presentazione dallo stream. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Crea e aggiunge un audio a una presentazione dallo stream. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Crea e aggiunge un audio a una presentazione da un array di byte. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia gli audio in un array specificato a partire dall'indice specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce la radice di sincronizzazione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iterator java per l'intera collezione. |
### size() {#size--}
```
public final int size()
```

Restituisce il numero di file audio nella collezione. int sola lettura.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

Ottiene l'elemento all'indice specificato. [IAudio](../../com.aspose.slides/iaudio) sola lettura.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

Aggiunge una copia di un file audio da un'altra presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio di origine. |

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio) - Audio aggiunto.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

Crea e aggiunge un audio a una presentazione dallo stream.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream da cui aggiungere audio. |

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio) - Audio aggiunto.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Crea e aggiunge un audio a una presentazione dallo stream.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream da cui aggiungere audio. |
| loadingStreamBehavior | int | Il comportamento che verrà applicato allo stream. |

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio) - Audio aggiunto.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

Crea e aggiunge un audio a una presentazione da un array di byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| audioData | byte[] | Byte audio. |

**Restituisce:**
[IAudio](../../com.aspose.slides/iaudio) - Audio aggiunto.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia gli audio in un array specificato a partire dall'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Indice. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). boolean sola lettura.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Restituisce una radice di sincronizzazione. Object sola lettura.

**Restituisce:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Restituisce un iterator java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Un java.util.Iterator per l'intera collezione.