---
title: IVideoCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una colección de objetos Video.
type: docs
url: /es/com.aspose.slides/ivideocollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Representa una colección de objetos Video.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Agrega una copia de un archivo de video desde otra presentación. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Crea y agrega un video a una presentación desde un flujo. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Crea y agrega un video a una presentación a partir de una matriz de bytes. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
```


Obtiene el elemento en el índice especificado. Solo lectura [IVideo](../../com.aspose.slides/ivideo).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public abstract IVideo addVideo(IVideo video)
```


Agrega una copia de un archivo de video desde otra presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video de origen. |

**Devuelve:**
[IVideo](../../com.aspose.slides/ivideo) - Video añadido.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Crea y agrega un video a una presentación desde un flujo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo del cual agregar el archivo de video. |
| loadingStreamBehavior | int | El comportamiento que se aplicará al flujo. |

**Devuelve:**
[IVideo](../../com.aspose.slides/ivideo) - Añadido [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


Crea y agrega un video a una presentación a partir de una matriz de bytes.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| videoData | byte[] | Bytes del video. |

**Devuelve:**
[IVideo](../../com.aspose.slides/ivideo) - Video añadido.