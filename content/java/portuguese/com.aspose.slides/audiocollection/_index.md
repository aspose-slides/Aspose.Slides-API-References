---
title: AudioCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa uma coleção de arquivos de áudio incorporados.
type: docs
url: /pt/com.aspose.slides/audiocollection/
---
**Herança:**
java.lang.Object, com.aspose.slides.DomObject

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IAudioCollection](../../com.aspose.slides/iaudiocollection)
```
public class AudioCollection extends DomObject<Presentation> implements IAudioCollection
```

Representa uma coleção de arquivos de áudio incorporados.
## Métodos

| Método | Descrição |
| --- | --- |
| [size()](#size--) | Retorna um número de arquivos de áudio na coleção. |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Adiciona uma cópia de um arquivo de áudio de outra apresentação. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Cria e adiciona um áudio a uma apresentação a partir de stream. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Cria e adiciona um áudio a uma apresentação a partir de stream. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Cria e adiciona um áudio a uma apresentação a partir de um array de bytes. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia áudios para o array especificado começando a partir do índice especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor que indica se o acesso à coleção é sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna uma raiz de sincronização. |
| [iterator()](#iterator--) | Retorna um enumerador que itera sobre a coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterador java para toda a coleção. |
### size() {#size--}
```
public final int size()
```

Retorna um número de arquivos de áudio na coleção. Somente leitura int.

Retorna:
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

Obtém o elemento no índice especificado. Somente leitura [IAudio](../../com.aspose.slides/iaudio).

Parâmetros:
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

Retorna:
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

Adiciona uma cópia de um arquivo de áudio de outra apresentação.

Parâmetros:
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Áudio de origem. |

Retorna:
[IAudio](../../com.aspose.slides/iaudio) - Áudio adicionado.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

Cria e adiciona um áudio a uma apresentação a partir de stream.

Parâmetros:
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo de onde adicionar o áudio. |

Retorna:
[IAudio](../../com.aspose.slides/iaudio) - Áudio adicionado.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Cria e adiciona um áudio a uma apresentação a partir de stream.

Parâmetros:
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo de onde adicionar o áudio. |
| loadingStreamBehavior | int | O comportamento que será aplicado ao fluxo. |

Retorna:
[IAudio](../../com.aspose.slides/iaudio) - Áudio adicionado.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

Cria e adiciona um áudio a uma apresentação a partir de um array de bytes.

Parâmetros:
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| audioData | byte[] | Bytes de áudio. |

Retorna:
[IAudio](../../com.aspose.slides/iaudio) - Áudio adicionado.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia áudios para o array especificado começando a partir do índice especificado.

Parâmetros:
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Matriz. |
| index | int | Índice. |
### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor que indica se o acesso à coleção é sincronizado (thread-safe). Somente leitura boolean.

Retorna:
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna uma raiz de sincronização. Somente leitura Object.

Retorna:
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Retorna um enumerador que itera sobre a coleção.

Retorna:
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Retorna um iterador java para toda a coleção.

Retorna:
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Um java.util.Iterator para toda a coleção.