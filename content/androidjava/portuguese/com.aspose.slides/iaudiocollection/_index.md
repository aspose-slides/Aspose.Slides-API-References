---
title: IAudioCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa uma coleção de arquivos de áudio incorporados.
type: docs
url: /pt/com.aspose.slides/iaudiocollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IAudioCollection extends IGenericCollection<IAudio>
```

Representa uma coleção de arquivos de áudio incorporados.
## Métodos

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addAudio(IAudio audio)](#addAudio-com.aspose.slides.IAudio-) | Adiciona uma cópia de um arquivo de áudio de outra apresentação. |
| [addAudio(InputStream stream)](#addAudio-java.io.InputStream-) | Cria e adiciona um áudio a uma apresentação a partir de um stream. |
| [addAudio(InputStream stream, int loadingStreamBehavior)](#addAudio-java.io.InputStream-int-) | Cria e adiciona um áudio a uma apresentação a partir de um stream. |
| [addAudio(byte[] audioData)](#addAudio-byte---) | Cria e adiciona um áudio a uma apresentação a partir de um array de bytes. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IAudio get_Item(int index)
```


Obtém o elemento no índice especificado. Somente leitura [IAudio](../../com.aspose.slides/iaudio).

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio)
### addAudio(IAudio audio) {#addAudio-com.aspose.slides.IAudio-}
```
public abstract IAudio addAudio(IAudio audio)
```


Adiciona uma cópia de um arquivo de áudio de outra apresentação.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| audio | [IAudio](../../com.aspose.slides/iaudio) | Áudio de origem. |

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio) - Áudio adicionado.
### addAudio(InputStream stream) {#addAudio-java.io.InputStream-}
```
public abstract IAudio addAudio(InputStream stream)
```


Cria e adiciona um áudio a uma apresentação a partir de um stream.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream de onde adicionar o áudio. |

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio) - Áudio adicionado.
### addAudio(InputStream stream, int loadingStreamBehavior) {#addAudio-java.io.InputStream-int-}
```
public abstract IAudio addAudio(InputStream stream, int loadingStreamBehavior)
```


Cria e adiciona um áudio a uma apresentação a partir de um stream.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.InputStream | Stream de onde adicionar o áudio de vídeo. |
| loadingStreamBehavior | int | O [LoadingStreamBehavior](../../com.aspose.slides/loadingstreambehavior) que será aplicado ao stream. |

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio) - Áudio adicionado.
### addAudio(byte[] audioData) {#addAudio-byte---}
```
public abstract IAudio addAudio(byte[] audioData)
```


Cria e adiciona um áudio a uma apresentação a partir de um array de bytes.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| audioData | byte[] | Bytes de áudio. |

**Retorna:**
[IAudio](../../com.aspose.slides/iaudio) - Áudio adicionado.