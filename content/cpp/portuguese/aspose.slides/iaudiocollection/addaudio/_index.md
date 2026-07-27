---
title: AddAudio()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona uma cópia de um arquivo de áudio de outra apresentação.
type: docs
weight: 14
url: /pt/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) método


Adiciona uma cópia de um arquivo de áudio de outra apresentação.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Áudio de origem. |

### Valor de retorno

Áudio adicionado.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) método


Cria e adiciona um áudio a uma apresentação a partir de um stream.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream de onde o áudio será adicionado. |

### Valor de retorno

Áudio adicionado.

Obsoleto
:   Use AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). O método será removido na versão 17.10.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) método


Cria e adiciona um áudio a uma apresentação a partir de um stream.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Stream de onde o áudio de vídeo será adicionado. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | O comportamento que será aplicado ao stream. |

### Valor de retorno

Áudio adicionado.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) método


Cria e adiciona um áudio a uma apresentação a partir de um array de bytes.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) bytes. |

### Valor de retorno

Áudio adicionado.

## Veja também

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [IAudio](../../iaudio/)
* Classe [IAudioCollection](../)
* Classe [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)