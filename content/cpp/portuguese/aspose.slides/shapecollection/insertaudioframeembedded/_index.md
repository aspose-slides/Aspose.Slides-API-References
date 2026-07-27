---
title: InsertAudioFrameEmbedded()
second_title: Referência da API Aspose.Slides para C++
description: "Cria um novo quadro de áudio com um arquivo WAV incorporado e o insere na coleção de formas no índice especificado. O áudio incorporado é adicionado à coleção Presentation::get_Audios."
type: docs
weight: 300
url: /pt/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) método


Cria um novo quadro de áudio com um arquivo WAV incorporado e o insere na coleção de formas no índice especificado. O áudio incorporado é adicionado à coleção [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir o quadro de áudio. |
| x | **float** | A coordenada x do novo quadro de áudio, em pontos. |
| y | **float** | A coordenada y do novo quadro de áudio, em pontos. |
| width | **float** | A largura do novo quadro de áudio, em pontos. |
| height | **float** | A altura do novo quadro de áudio, em pontos. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um fluxo de entrada contendo dados de áudio WAV para incorporar. |

### Valor de Retorno

O [IAudioFrame](../../iaudioframe/) recém-criado.

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) método


Cria um novo quadro de áudio e o insere na coleção de formas no índice especificado usando um objeto de áudio existente da lista [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir o quadro de áudio. |
| x | **float** | A coordenada x do novo quadro de áudio, em pontos. |
| y | **float** | A coordenada y do novo quadro de áudio, em pontos. |
| width | **float** | A largura do novo quadro de áudio, em pontos. |
| height | **float** | A altura do novo quadro de áudio, em pontos. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Uma instância [IAudio](../../iaudio/) da coleção [Presentation::get_Audios](../../presentation/get_audios/) para incorporar. |

### Valor de Retorno

O [IAudioFrame](../../iaudioframe/) recém-criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* classe [IAudioFrame](../../iaudioframe/)
* classe [Stream](../../../system.io/stream/)
* classe [ShapeCollection](../)
* classe [IAudio](../../iaudio/)
* namespace [Aspose::Slides](../../)
* biblioteca [Aspose.Slides](../../../)