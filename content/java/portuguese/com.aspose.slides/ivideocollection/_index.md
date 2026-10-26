---
title: IVideoCollection
second_title: Referência da API Aspose.Slides para Java
description: Representa uma coleção de objetos Video.
type: docs
url: /pt/com.aspose.slides/ivideocollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IVideoCollection extends IGenericCollection<IVideo>
```

Representa uma coleção de objetos Video.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addVideo(IVideo video)](#addVideo-com.aspose.slides.IVideo-) | Adiciona uma cópia de um arquivo de vídeo de outra apresentação. |
| [addVideo(InputStream stream, int loadingStreamBehavior)](#addVideo-java.io.InputStream-int-) | Cria e adiciona um vídeo a uma apresentação a partir de um fluxo. |
| [addVideo(byte[] videoData)](#addVideo-byte---) | Cria e adiciona um vídeo a uma apresentação a partir de um array de bytes. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IVideo get_Item(int index)
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
public abstract IVideo addVideo(IVideo video)
```


Adiciona uma cópia de um arquivo de vídeo de outra apresentação.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| video | [IVideo](../../com.aspose.slides/ivideo) | Vídeo fonte. |

**Retorna:**
[IVideo](../../com.aspose.slides/ivideo) - Vídeo adicionado.
### addVideo(InputStream stream, int loadingStreamBehavior) {#addVideo-java.io.InputStream-int-}
```
public abstract IVideo addVideo(InputStream stream, int loadingStreamBehavior)
```


Cria e adiciona um vídeo a uma apresentação a partir de um fluxo.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | java.io.InputStream | Fluxo de onde o arquivo de vídeo será adicionado. |
| loadingStreamBehavior | int | O comportamento que será aplicado ao fluxo. |

**Retorna:**
[IVideo](../../com.aspose.slides/ivideo) - Adicionado [IVideo](../../com.aspose.slides/ivideo).
### addVideo(byte[] videoData) {#addVideo-byte---}
```
public abstract IVideo addVideo(byte[] videoData)
```


Cria e adiciona um vídeo a uma apresentação a partir de um array de bytes.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| videoData | byte[] | Bytes do vídeo. |

**Retorna:**
[IVideo](../../com.aspose.slides/ivideo) - Vídeo adicionado.