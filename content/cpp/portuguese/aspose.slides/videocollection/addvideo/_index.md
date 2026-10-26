---
title: AddVideo()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma cópia de um arquivo de vídeo de outra apresentação.
type: docs
weight: 53
url: /pt/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) método

Adiciona uma cópia de um arquivo de vídeo de outra apresentação.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Vídeo de origem. |

### Valor de Retorno

Vídeo adicionado.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) método

Cria e adiciona um vídeo a uma apresentação a partir de um fluxo.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de onde o arquivo de vídeo será adicionado. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | O comportamento que será aplicado ao fluxo. |

### Valor de Retorno

[IVideo](../../ivideo/) adicionado.

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) método

Cria e adiciona um vídeo a uma apresentação a partir de um array de bytes.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) bytes. |

### Valor de Retorno

Vídeo adicionado.

## Veja Também

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IVideo](../../ivideo/)
* Class [VideoCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)