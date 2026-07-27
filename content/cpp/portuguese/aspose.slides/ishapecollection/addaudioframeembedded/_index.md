---
title: AddAudioFrameEmbedded()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo quadro de áudio com um arquivo WAV incorporado e o adiciona ao final da coleção de formas. O áudio incorporado é adicionado à coleção Presentation.Audios.
type: docs
weight: 248
url: /pt/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method


Cria um novo quadro de áudio com um arquivo WAV incorporado e o adiciona ao final da coleção de formas. O áudio incorporado é adicionado à coleção Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro de áudio, em pontos. |
| y | **float** | A coordenada y do novo quadro de áudio, em pontos. |
| width | **float** | A largura do novo quadro de áudio, em pontos. |
| height | **float** | A altura do novo quadro de áudio, em pontos. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um fluxo de entrada contendo dados de áudio WAV a serem incorporados. |

### Valor de Retorno

O [IAudioFrame](../../iaudioframe/) recém-criado.

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) method


Cria um novo quadro de áudio e o adiciona ao final da coleção de formas usando um objeto de áudio existente da lista Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro de áudio, em pontos. |
| y | **float** | A coordenada y do novo quadro de áudio, em pontos. |
| width | **float** | A largura do novo quadro de áudio, em pontos. |
| height | **float** | A altura do novo quadro de áudio, em pontos. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Uma instância [IAudio](../../iaudio/) da coleção Presentation.Audios. |

### Valor de Retorno

O [IAudioFrame](../../iaudioframe/) recém-criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudioFrame](../../iaudioframe/)
* Classe [Stream](../../../system.io/stream/)
* Classe [IShapeCollection](../)
* Classe [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)