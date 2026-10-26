---
title: IVideoCollection
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta una raccolta di oggetti Video.
type: docs
url: /it/com.aspose.slides/ivideocollection/
---
**Tutte le interfacce implementate:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Rappresenta una raccolta di oggetti Video.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Restituisce l'elemento all'indice specificato. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Aggiunge una copia di un file video da un'altra presentazione. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Crea e aggiunge un video a una presentazione dallo stream. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Crea e aggiunge un video a una presentazione da un array di byte. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```


Restituisce l'elemento all'indice specificato. Solamente lettura [IVideo](../../com.aspose.slides/ivideo).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int |  |

**Restituisce:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
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
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Crea e aggiunge un video a una presentazione dallo stream.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream da cui aggiungere il file video. |
| loadingStreamBehavior | int | Il comportamento che sarà applicato allo stream. |

**Restituisce:**
[IVideo](../../com.aspose.slides/ivideo) - Aggiunto [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


Crea e aggiunge un video a una presentazione da un array di byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| videoData | byte[] | Byte del video. |

**Restituisce:**
[IVideo](../../com.aspose.slides/ivideo) - Video aggiunto.