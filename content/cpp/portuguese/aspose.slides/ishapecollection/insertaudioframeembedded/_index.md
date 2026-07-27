---
title: InsertAudioFrameEmbedded()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova moldura de áudio com um arquivo WAV incorporado e a insere na coleção de formas no índice especificado. O áudio incorporado é adicionado à coleção Presentation.Audios.
type: docs
weight: 261
url: /pt/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) método

Cria uma nova moldura de áudio com um arquivo WAV incorporado e a insere na coleção de formas no índice especificado. O áudio incorporado é adicionado à coleção Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir a moldura de áudio. |
| x | **float** | A coordenada x da nova moldura de áudio, em pontos. |
| y | **float** | A coordenada y da nova moldura de áudio, em pontos. |
| width | **float** | A largura da nova moldura de áudio, em pontos. |
| height | **float** | A altura da nova moldura de áudio, em pontos. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um fluxo de entrada contendo dados de áudio WAV a ser incorporado. |

### Valor de Retorno

O [IAudioFrame](../../iaudioframe/) recém-criado.

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) método

Cria uma nova moldura de áudio e a insere na coleção de formas no índice especificado usando um objeto de áudio existente da lista Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir a moldura de áudio. |
| x | **float** | A coordenada x da nova moldura de áudio, em pontos. |
| y | **float** | A coordenada y da nova moldura de áudio, em pontos. |
| width | **float** | A largura da nova moldura de áudio, em pontos. |
| height | **float** | A altura da nova moldura de áudio, em pontos. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Uma instância [IAudio](../../iaudio/) da coleção Presentation.Audios a ser incorporada. |

### Valor de Retorno

O [IAudioFrame](../../iaudioframe/) recém-criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAudioFrame](../../iaudioframe/)
* Classe [Stream](../../../system.io/stream/)
* Classe [IShapeCollection](../)
* Classe [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)