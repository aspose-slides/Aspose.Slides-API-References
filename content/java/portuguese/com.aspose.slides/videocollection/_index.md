---
title: VideoCollection
second_title: Referência da API Aspose.Slides for Java
description: Representa uma coleção de objetos Video.
type: docs
url: /pt/com.aspose.slides/videocollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IVideoCollection](../../com.aspose.slides/ivideocollection)
```
public class VideoCollection extends DomObject<Presentation> implements IVideoCollection
```

Representa uma coleção de objetos Video.
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Retorna o número de arquivos de vídeo na coleção. |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Adiciona uma cópia de um arquivo de vídeo de outra apresentação. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Cria e adiciona um vídeo a uma apresentação a partir de um stream. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Cria e adiciona um vídeo a uma apresentação a partir de um array de bytes. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia vídeos para o array especificado começando do índice especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna a raiz de sincronização. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para toda a coleção. |
### size() {#size--}
```
public final int size()
```


Retorna o número de arquivos de vídeo na coleção. Somente leitura int.

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IVideo get_Item(int index)
```


Obtém o elemento no índice especificado. Somente leitura [IVideo](../../com.aspose.slides/ivideo).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IVideo](../../com.aspose.slides/ivideo)
### addVideo(IVideo video) {#addVideo-com.aspose.slides.IVideo-}
```
public final IVideo addVideo(IVideo video)
```


Adiciona uma cópia de um arquivo de vídeo de outra apresentação.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Vídeo de origem. |

**Retorna:**
[IVideo](../../com.aspose.slides/ivideo) - Vídeo adicionado.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public final IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Cria e adiciona um vídeo a uma apresentação a partir de um stream.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream de onde adicionar o arquivo de vídeo. |
| loadingStreamBehavior | int | O comportamento que será aplicado ao stream. |

**Retorna:**
[IVideo](../../com.aspose.slides/ivideo) - [IVideo](../../com.aspose.slides/ivideo) adicionado.
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```


Cria e adiciona um vídeo a uma apresentação a partir de um array de bytes.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| videoData | byte[] | Bytes do vídeo. |

**Retorna:**
[IVideo](../../com.aspose.slides/ivideo) - Vídeo adicionado.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```


Copia vídeos para o array especificado começando do índice especificado.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Índice. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```


Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```


Retorna a raiz de sincronização. Somente leitura Object.

**Retorna:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iterator()
```


Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IVideo> iteratorJava()
```


Retorna um iterador java para toda a coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Um java.util.Iterator para toda a coleção.