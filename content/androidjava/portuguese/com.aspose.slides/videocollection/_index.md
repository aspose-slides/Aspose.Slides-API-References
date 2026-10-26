---
title: VideoCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de objetos Video.
type: docs
url: /pt/com.aspose.slides/videocollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as interfaces implementadas:**
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
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia vídeos para o array especificado a partir do índice especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor indicando se o acesso à coleção é sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
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
| Parâmetro | Tipo | Descrição |
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
| Parâmetro | Tipo | Descrição |
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
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Stream de onde adicionar o arquivo de vídeo. |
| loadingStreamBehavior | int | O comportamento que será aplicado ao stream. |

**Retorna:**
[IVideo](../../com.aspose.slides/ivideo) - Adicionado [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public final IVideo addVideo(byte[] videoData)
```

Cria e adiciona um vídeo a uma apresentação a partir de um array de bytes.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| videoData | byte[] | Bytes do vídeo. |

**Retorna:**
[IVideo](../../com.aspose.slides/ivideo) - Vídeo adicionado.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia vídeos para o array especificado a partir do índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Índice. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor indicando se o acesso à coleção é sincronizado (thread-safe). Somente leitura boolean.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Somente leitura Object.

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

Retorna um iterador java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IVideo> - Um java.util.Iterator para a coleção inteira.