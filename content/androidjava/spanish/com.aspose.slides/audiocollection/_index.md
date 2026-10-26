---
title: AudioCollection
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Representa una colección de archivos de audio incrustados.
type: docs
url: /es/com.aspose.slides/audiocollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)  
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Representa una colección de archivos de audio incrustados.
## Métodos

| Method | Description |
| --- | --- |
| [size()](#size--) | Devuelve un número de archivos de audio en la colección. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Agrega una copia de un archivo de audio de otra presentación. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Crea y agrega un audio a una presentación desde un flujo. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Crea y agrega un audio a una presentación desde un flujo. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Crea y agrega un audio a una presentación desde una matriz de bytes. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia audios al array especificado comenzando desde el índice especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve la raíz de sincronización. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
### size() {#size--}
```
public final int size()
```

Devuelve un número de archivos de audio en la colección. Solo lectura int.

**Devuelve:**  
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
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
| stream | java.io.InputStream | Flujo del cual se agrega el audio. |

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
| stream | java.io.InputStream | Flujo del cual se agrega el audio de video. |
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

Copia audios al array especificado comenzando desde el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Índice. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). Solo lectura boolean.

**Devuelve:**  
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Devuelve la raíz de sincronización. Solo lectura Object.

**Devuelve:**  
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Un java.util.Iterator para toda la colección.