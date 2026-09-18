---
title: add_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Yerleşik bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve şekil koleksiyonunun sonuna ekler. Yerleşik ses, Presentation.Audios koleksiyonuna eklenir.

### Döndürür

Yeni oluşturulan [`IAudioFrame`](/slides/python-net/tr/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| audio_stream | **io.RawIOBase** | Yerleştirilecek WAV ses verilerini içeren bir giriş akışı. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Yeni bir ses çerçevesi oluşturur ve Presentation.Audios listesindeki mevcut bir ses nesnesi kullanarak şekil koleksiyonunun sonuna ekler.

### Döndürür

Yeni oluşturulan [`IAudioFrame`](/slides/python-net/tr/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | **float** | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| audio | [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio) | Presentation.Audios koleksiyonundan bir [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio) örneği. |



### Bakınız
* sınıf [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio)
* sınıf [`IAudioFrame`](/slides/python-net/tr/aspose.slides/iaudioframe)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)