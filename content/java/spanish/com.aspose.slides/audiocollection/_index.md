---
title: AudioCollection
second_title: Referencia de API de Aspose.Slides para Java
description: Representa una colección de archivos de audio incrustados.
type: docs
url: /es/com.aspose.slides/audiocollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Representa una colección de archivos de audio incrustados.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Devuelve un número de archivos de audio en la colección. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Agrega una copia de un archivo de audio de otra presentación. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Crea y agrega un audio a una presentación desde un flujo. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Crea y agrega un audio a una presentación desde un flujo. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Crea y agrega un audio a una presentación desde un arreglo de bytes. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia audios a la matriz especificada comenzando desde el índice especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
| [iterator()](#iterator--) | Devuelve un enumerador que recorre la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
### size() {#size--}
```
public final int size()
```

Devuelve un número de archivos de audio en la colección. Solo de lectura int.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

Obtiene el elemento en el índice especificado. Solo de lectura [IAudio](../../com.aspose.slides/iaudio).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int |  |

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
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
public final IAudio addAudio(InputStream stream)
```

Crea y agrega un audio a una presentación desde un flujo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo del cual agregar el audio. |

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio) - Audio agregado.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Crea y agrega un audio a una presentación desde un flujo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo del cual agregar el audio de vídeo. |
| loadingStreamBehavior | int | El comportamiento que se aplicará al flujo. |

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio) - Audio agregado.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

Crea y agrega un audio a una presentación desde una matriz de bytes.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| audioData | byte[] | Bytes de audio. |

**Devuelve:**
[IAudio](../../com.aspose.slides/iaudio) - Audio agregado.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia audios a la matriz especificada comenzando desde el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Matriz. |
| index | int | Índice. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo de lectura boolean.

**Devuelve:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve una raíz de sincronización. Solo de lectura Object.

**Devuelve:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Devuelve un enumerador que recorre la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Un IGenericEnumerator que puede usarse para recorrer la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Un java.util.Iterator para toda la colección.