---
title: IAudioCollection
second_title: Aspose.Slides para Android vía Referencia de API Java
description: Representa una colección de archivos de audio incrustados.
type: docs
url: /es/com.aspose.slides/iaudiocollection/
---
**Todas las interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Representa una colección de archivos de audio incrustados.
## Métodos

| Método | Descripción |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Agrega una copia de un archivo de audio de otra presentación. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Crea y agrega un audio a una presentación desde un flujo. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Crea y agrega un audio a una presentación desde un flujo. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Crea y agrega un audio a una presentación desde una matriz de bytes. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```


Obtiene el elemento en el índice especificado. Solo lectura [IAudio](../../com.aspose.slides/iaudio).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```


Agrega una copia de un archivo de audio de otra presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Audio de origen. |

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio) - Audio agregado.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```


Crea y agrega un audio a una presentación desde un flujo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo del que agregar audio. |

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio) - Audio agregado.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Crea y agrega un audio a una presentación desde un flujo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo del que agregar audio de video. |
| loadingStreamBehavior | int | El [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) que se aplicará al flujo. |

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio) - Audio agregado.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```


Crea y agrega un audio a una presentación desde una matriz de bytes.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| audioData | byte[] | Bytes de audio. |

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio) - Audio agregado.