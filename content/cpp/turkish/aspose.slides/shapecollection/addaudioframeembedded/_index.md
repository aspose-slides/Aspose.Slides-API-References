---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides C++ API Referansı
description: "Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. Gömülü ses, Presentation::get_Audios koleksiyonuna eklenir."
type: docs
weight: 287
url: /tr/aspose.slides/shapecollection/addaudioframeembedded/
---
## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) yöntemi

Gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. Gömülü ses [Presentation::get_Audios](../../presentation/get_audios/) koleksiyonuna eklenir.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni ses çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni ses çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, nokta cinsinden. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Gömülecek WAV ses verilerini içeren bir giriş akışı. |

### Dönüş Değeri

Yeni oluşturulan [IAudioFrame](../../iaudioframe/).

## Açıklamalar

Aşağıdaki örnekler [Audio](../../audio/) Çerçevesi oluşturmayı gösterir. 
```cpp
// Bir sunum dosyasını temsil eden bir sunum sınıfı örnekler
auto pres = System::MakeObject<Presentation>();

// İlk slaytı alır
auto slide = pres->get_Slides()->idx_get(0);
// WAV ses dosyasını akışa yükler
System::SharedPtr<System::IO::FileStream> fstr = System::MakeObject<System::IO::FileStream>(u"sampleaudio.wav", System::IO::FileMode::Open, System::IO::FileAccess::Read);

// Ses çerçevesini ekler
System::SharedPtr<IAudioFrame> audioFrame = slide->get_Shapes()->AddAudioFrameEmbedded(50.0f, 150.0f, 100.0f, 100.0f, fstr);
// Sesin oynatma modunu ve ses seviyesini ayarlar
audioFrame->set_PlayMode(AudioPlayModePreset::Auto);
audioFrame->set_Volume(AudioVolumeMode::Loud);

// PowerPoint dosyasını diske yazar
pres->Save(u"AudioFrameEmbed_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) yöntemi

Mevcut bir ses nesnesini [Presentation::get_Audios](../../presentation/get_audios/) listesinden kullanarak yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler.

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | **float** | Yeni ses çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni ses çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, nokta cinsinden. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | [Presentation::get_Audios](../../presentation/get_audios/) koleksiyonundan bir [IAudio](../../iaudio/) örneği. |

### Dönüş Değeri

Yeni oluşturulan [IAudioFrame](../../iaudioframe/).

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAudioFrame](../../iaudioframe/)
* Class [Stream](../../../system.io/stream/)
* Class [ShapeCollection](../)
* Class [IAudio](../../iaudio/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)