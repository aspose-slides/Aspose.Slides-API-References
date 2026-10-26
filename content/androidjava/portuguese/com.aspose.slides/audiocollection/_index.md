---
title: AudioCollection
second_title: Aspose.Slides para Android via Referência de API Java
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
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Cria e adiciona um áudio a uma apresentação a partir de um stream. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Cria e adiciona um áudio a uma apresentação a partir de um stream. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Cria e adiciona um áudio a uma apresentação a partir de um array de bytes. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copia áudios para o array especificado começando a partir do índice especificado. |
| [isSynchronized()](#isSynchronized--) | Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). |
| [getSyncRoot()](#getSyncRoot--) | Retorna a raiz de sincronização. |
| [iterator()](#iterator--) | Retorna um enumerador que itera através da coleção. |
| [iteratorJava()](#iteratorJava--) | Retorna um iterator java para a coleção inteira. |
### size() {#size--}
```
public final int size()
```

Retorna um número de arquivos de áudio na coleção. int somente leitura.

**Retorna:**
int
### get_Item(int index) {#get-Item-int-}
```
public final IAudio get_Item(int index)
```

Obtém o elemento no índice especificado. Somente leitura [IAudio](../../com.aspose.slides/iaudio).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public final IAudio addAudio(IAudio audio)
```

Adiciona uma cópia de um arquivo de áudio de outra apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Áudio de origem. |

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio) - Áudio adicionado.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public final IAudio addAudio(InputStream stream)
```

Cria e adiciona um áudio a uma apresentação a partir de um stream.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Stream de onde adicionar o áudio. |

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio) - Áudio adicionado.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public final IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```

Cria e adiciona um áudio a uma apresentação a partir de um stream.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Stream de onde adicionar áudio de vídeo. |
| loadingStreamBehavior | int | O comportamento que será aplicado ao stream. |

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio) - Áudio adicionado.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public final IAudio addAudio(byte[] audioData)
```

Cria e adiciona um áudio a uma apresentação a partir de um array de bytes.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| audioData | byte[] | Bytes de áudio. |

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio) - Áudio adicionado.
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public final void copyTo(System.Array array, int index)
```

Copia áudios para o array especificado começando a partir do índice especificado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array. |
| index | int | Index. |

### isSynchronized() {#isSynchronized--}
```
public final boolean isSynchronized()
```

Retorna um valor que indica se o acesso à coleção está sincronizado (thread-safe). boolean somente leitura.

**Retorna:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public final Object getSyncRoot()
```

Retorna a raiz de sincronização. Object somente leitura.

**Retorna:**
java.lang.Object
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iterator()
```

Retorna um enumerador que itera através da coleção.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Um IGenericEnumerator que pode ser usado para iterar através da coleção.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IAudio> iteratorJava()
```

Retorna um iterator java para a coleção inteira.

**Retorna:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IAudio> - Um java.util.Iterator para a coleção inteira.