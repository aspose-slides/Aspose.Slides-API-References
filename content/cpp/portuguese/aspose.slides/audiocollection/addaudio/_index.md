---
title: AddAudio()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma cópia de um arquivo de áudio de outra apresentação.
type: docs
weight: 53
url: /pt/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) método

Adiciona uma cópia de um arquivo de áudio de outra apresentação.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Áudio de origem. |

### Valor de Retorno

Áudio adicionado.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) método

Cria e adiciona um áudio a uma apresentação a partir de um fluxo.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de onde adicionar o áudio. |

### Valor de Retorno

Áudio adicionado.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) método

Cria e adiciona um áudio a uma apresentação a partir de um fluxo.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Fluxo de onde adicionar o áudio de vídeo. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | O comportamento que será aplicado ao fluxo. |

### Valor de Retorno

Áudio adicionado.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) método

Cria e adiciona um áudio a uma apresentação a partir de um array de bytes.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bytes. |

### Valor de Retorno

Áudio adicionado.

## Veja Também

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [IAudio](../../iaudio/)
* Class [AudioCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)