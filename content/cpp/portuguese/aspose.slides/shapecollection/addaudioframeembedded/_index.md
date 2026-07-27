---
title: AddAudioFrameEmbedded()
second_title: Referência da API Aspose.Slides para C++
description: "Cria um novo quadro de áudio com um arquivo WAV incorporado e o adiciona ao final da coleção de formas. O áudio incorporado é adicionado à coleção Presentation::get_Audios."
type: docs
weight: 287
url: /pt/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) método

Cria um novo quadro de áudio com um arquivo WAV incorporado e o adiciona ao final da coleção de formas. O áudio incorporado é adicionado à coleção [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro de áudio, em pontos. |
| y | **float** | A coordenada y do novo quadro de áudio, em pontos. |
| width | **float** | A largura do novo quadro de áudio, em pontos. |
| height | **float** | A altura do novo quadro de áudio, em pontos. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Um fluxo de entrada contendo dados de áudio WAV para incorporar. |

### Valor de Retorno

O [IAudioFrame](../../iaudioframe/) recém-criado.

## Observações



O exemplo a seguir mostra como criar [Audio](../../audio/) Frame. 
```cpp
// Instancia uma classe de apresentação que representa um arquivo de apresentação
auto pres = System::MakeObject<Presentation>();

// Obtém o primeiro slide
auto slide = pres->get_Slides()->idx_get(0);
// Carrega o arquivo de som wav para o fluxo
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// Adiciona o quadro de áudio
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// Define o modo de reprodução e o volume do áudio
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// Grava o arquivo PowerPoint no disco
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) método

Cria um novo quadro de áudio e o adiciona ao final da coleção de formas usando um objeto de áudio existente da lista [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| x | **float** | A coordenada x do novo quadro de áudio, em pontos. |
| y | **float** | A coordenada y do novo quadro de áudio, em pontos. |
| width | **float** | A largura do novo quadro de áudio, em pontos. |
| height | **float** | A altura do novo quadro de áudio, em pontos. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Uma instância [IAudio](../../iaudio/) da coleção [Presentation::get_Audios](../../presentation/get_audios/). |

### Valor de Retorno

O [IAudioFrame](../../iaudioframe/) recém-criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [ShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)