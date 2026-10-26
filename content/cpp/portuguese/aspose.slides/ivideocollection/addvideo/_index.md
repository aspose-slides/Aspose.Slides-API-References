---
title: AddVideo()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma cópia de um arquivo de vídeo de outra apresentação.
type: docs
weight: 14
url: /pt/aspose.slides/ivideocollection/addvideo/
---
## IVideoCollection::AddVideo(System::SharedPtr\<IVideo\>) método


Adiciona uma cópia de um arquivo de vídeo de outra apresentação.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<IVideo> video)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Vídeo de origem. |

### Valor de retorno

Vídeo adicionado.

## IVideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) método


Cria e adiciona um vídeo a uma apresentação a partir de um fluxo.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo a partir do qual o arquivo de vídeo será adicionado. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | O comportamento que será aplicado ao fluxo. |

### Valor de retorno

Adicionado [IVideo](../../ivideo/).

## IVideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) método


Cria e adiciona um vídeo a uma apresentação a partir de um array de bytes.

```cpp
virtual System::SharedPtr<IVideo> Aspose::Slides::IVideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) bytes. |

### Valor de retorno

Vídeo adicionado.

## Veja Também

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IVideo](../../ivideo/)
* Class [IVideoCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)