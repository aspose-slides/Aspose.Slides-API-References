---
title: VideoCollection
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Rappresenta una raccolta di oggetti Video.
type: docs
url: /it/com.aspose.slides/videocollection/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Rappresenta una collezione di oggetti Video.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [size()](#size--) | Restituisce un numero di file video nella collezione. |
| [get_Item(int index)](#get-Item-int-) | Ottiene l'elemento all'indice specificato. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Aggiunge una copia di un file video da un'altra presentazione. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Crea e aggiunge un video a una presentazione da un flusso. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Crea e aggiunge un video a una presentazione da un array di byte. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia i video in un array specificato a partire dall'indice specificato. |
| [isSynchronized()](#isSynchronized--) | Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Restituisce una radice di sincronizzazione. |
| [iterator()](#iterator--) | Restituisce un enumeratore che itera attraverso la collezione. |
| [iteratorJava()](#iteratorJava--) | Restituisce un iteratore java per l'intera collezione. |
### size() {#size--}
```
public final int size()
```


Restituisce un numero di file video nella collezione. Solo lettura int.

**Restituisce:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```


Ottiene l'elemento all'indice specificato. Solo lettura [IVideo](../../com.aspose.slides/ivideo).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```


Aggiunge una copia di un file video da un'altra presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video di origine. |

**Restituisce:**
[IVideo](../../com.aspose.slides/ivideo) - Video aggiunto.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Crea e aggiunge un video a una presentazione da un flusso.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Flusso da cui aggiungere il file video. |
| loadingStreamBehavior | int | Il comportamento da applicare al flusso. |

**Restituisce:**
[IVideo](../../com.aspose.slides/ivideo) - [IVideo](../../com.aspose.slides/ivideo) aggiunto.
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```


Crea e aggiunge un video a una presentazione da un array di byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| videoData | byte[] | Byte del video. |

**Restituisce:**
[IVideo](../../com.aspose.slides/ivideo) - Video aggiunto.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia i video in un array specificato a partire dall'indice specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Indice. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Restituisce un valore che indica se l'accesso alla collezione è sincronizzato (thread-safe). Solo lettura boolean.

**Restituisce:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Restituisce una radice di sincronizzazione. Solo lettura Object.

**Restituisce:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```


Restituisce un enumeratore che itera attraverso la collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Un IGenericEnumerator che può essere usato per iterare attraverso la collezione.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```


Restituisce un iteratore java per l'intera collezione.

**Restituisce:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Un java.util.Iterator per l'intera collezione.