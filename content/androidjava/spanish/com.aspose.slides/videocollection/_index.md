---
title: VideoCollection
second_title: Aspose.Slides para Android a través de la referencia de la API Java
description: Representa una colección de objetos Video.
type: docs
url: /es/com.aspose.slides/videocollection/
---
**Herencia:**
java.lang.Object, com.aspose.slides.DomObject

**Todas las interfaces implementadas:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Representa una colección de objetos Video.
## Métodos

| Método | Descripción |
| --- | --- |
| [size()](#size--) | Devuelve un número de archivos de video en la colección. |
| [get_Item(int index)](#get-Item-int-) | Obtiene el elemento en el índice especificado. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Agrega una copia de un archivo de video de otra presentación. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Crea y agrega un video a una presentación desde un flujo. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Crea y agrega un video a una presentación desde una matriz de bytes. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia videos al array especificado empezando desde el índice especificado. |
| [isSynchronized()](#isSynchronized--) | Devuelve un valor que indica si el acceso a la colección está sincronizado (seguro para subprocesos). |
| [getSyncRoot()](#getSyncRoot--) | Devuelve una raíz de sincronización. |
| [iterator()](#iterator--) | Devuelve un enumerador que itera a través de la colección. |
| [iteratorJava()](#iteratorJava--) | Devuelve un iterador java para toda la colección. |
### size() {#size--}
```
public final int size()
```

Devuelve un número de archivos de video en la colección. Solo lectura int.

**Devuelve:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
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
public final IVideo addVideo(IVideo video)
```

Agrega una copia de un archivo de video de otra presentación.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Video fuente. |

**Devuelve:**
[IVideo](../../com.aspose.slides/ivideo) - Video agregado.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```

Crea y agrega un video a una presentación desde un flujo.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | java.io.InputStream | Flujo desde el cual agregar el archivo de video. |
| loadingStreamBehavior | int | El comportamiento que se aplicará al flujo. |

**Devuelve:**
[IVideo](../../com.aspose.slides/ivideo) - Añadido [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Crea y agrega un video a una presentación desde una matriz de bytes.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| videoData | byte[] | Bytes del video. |

**Devuelve:**
[IVideo](../../com.aspose.slides/ivideo) - Video agregado.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia videos al array especificado empezando desde el índice especificado.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Matriz. |
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

Devuelve una raíz de sincronización. Solo lectura Object.

**Devuelve:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```

Devuelve un enumerador que itera a través de la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Un IGenericEnumerator que puede usarse para iterar a través de la colección.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```

Devuelve un iterador java para toda la colección.

**Devuelve:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Un java.util.Iterator para toda la colección.