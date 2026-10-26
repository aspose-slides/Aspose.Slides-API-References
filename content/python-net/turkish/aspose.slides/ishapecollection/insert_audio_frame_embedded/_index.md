---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Yeni bir ses çerçevesi oluşturur ve gömülü bir WAV dosyasıyla belirtilen indekste şekil koleksiyonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir.

### Döndürür

Yeni oluşturulan [`IAudioFrame`](/slides/python-net/tr/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Ses çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| audio_stream | **io.RawIOBase** | Gömülecek WAV ses verilerini içeren bir girdi akışı. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Yeni bir ses çerçevesi oluşturur ve mevcut bir ses nesnesini Presentation.Audios listesinden kullanarak belirtilen indekste şekil koleksiyonuna ekler.

### Döndürür

Yeni oluşturulan [`IAudioFrame`](/slides/python-net/tr/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Ses çerçevesinin ekleneceği sıfır tabanlı indeks. |
| x | **float** | Yeni ses çerçevesinin x koordinatı, puan cinsinden. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, puan cinsinden. |
| width | **float** | Yeni ses çerçevesinin genişliği, puan cinsinden. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, puan cinsinden. |
| audio | [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio) | Presentation.Audios koleksiyonundan gömülecek bir [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio) örneği. |



### İlgili
* sınıf [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio)
* sınıf [`IAudioFrame`](/slides/python-net/tr/aspose.slides/iaudioframe)
* sınıf [`IShapeCollection`](/slides/python-net/tr/aspose.slides/ishapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)