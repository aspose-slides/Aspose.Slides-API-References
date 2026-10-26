---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides için C++ API Referansı
description: "Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve belirtilen indeksde şekil koleksiyonuna ekler. Gömülü ses, Presentation::get_Audios koleksiyonuna eklenir."
type: docs
weight: 300
url: /tr/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) metodu


Belirtilen indeksde gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve şekil koleksiyonuna ekler. Gömülü ses, [Presentation::get_Audios](../../presentation/get_audios/) koleksiyonuna eklenir.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Ses çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Gömülecek WAV ses verisini içeren bir giriş akışı. |

### Return Value

Yeni oluşturulan [IAudioFrame](../../iaudioframe/).

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) metodu


Belirtilen indeksde, [Presentation::get_Audios](../../presentation/get_audios/) listesindeki mevcut bir ses nesnesini kullanarak yeni bir ses çerçevesi oluşturur ve şekil koleksiyonuna ekler.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```


### Arguments

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Ses çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | [Presentation::get_Audios](../../presentation/get_audios/) koleksiyonundan gömülecek bir [IAudio](../../iaudio/) örneği. |

### Return Value

Yeni oluşturulan [IAudioFrame](../../iaudioframe/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [ShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)