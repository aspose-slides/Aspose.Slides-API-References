---
title: add_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Yeni bir ses çerçevesi oluşturur ve gömülü bir WAV dosyasıyla şekil koleksiyonunun sonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir.

### Döndürür

Yeni oluşturulan [`IAudioFrame`](/slides/python-net/tr/aspose.slides/iaudioframe).

```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Yeni ses çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni ses çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, nokta cinsinden. |
| audio_stream | **io.RawIOBase** | Gömülecek WAV ses verilerini içeren giriş akışı. |

## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Yeni bir ses çerçevesi oluşturur ve Presentation.Audios listesindeki mevcut bir ses nesnesini kullanarak şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`IAudioFrame`](/slides/python-net/tr/aspose.slides/iaudioframe).

```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Yeni ses çerçevesinin x koordinatı, nokta cinsinden. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, nokta cinsinden. |
| width | **float** | Yeni ses çerçevesinin genişliği, nokta cinsinden. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, nokta cinsinden. |
| audio | [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio) | Presentation.Audios koleksiyonundan bir [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio) örneği. |

### Bakınız
* sınıf [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio)
* sınıf [`IAudioFrame`](/slides/python-net/tr/aspose.slides/iaudioframe)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)