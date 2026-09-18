---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Belirtilen dizinde gömülü bir WAV dosyasıyla yeni bir ses çerçevesi oluşturur ve şekil koleksiyonuna ekler. Gömülü ses, Presentation.Audios koleksiyonuna eklenir.

### Döndürür

Yeni oluşturulan [`IAudioFrame`](/slides/python-net/tr/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Ses çerçevesinin ekleneceği sıfır-bazlı indeks. |
| x | **float** | Yeni ses çerçevesinin x koordinatı, nokta biriminde. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, nokta biriminde. |
| width | **float** | Yeni ses çerçevesinin genişliği, nokta biriminde. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, nokta biriminde. |
| audio_stream | **io.RawIOBase** | Gömülecek WAV ses verisini içeren bir giriş akışı. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Mevcut bir ses nesnesini kullanarak yeni bir ses çerçevesi oluşturur ve şekil koleksiyonuna belirtilen dizinde ekler.

### Döndürür

Yeni oluşturulan [`IAudioFrame`](/slides/python-net/tr/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | **int** | Ses çerçevesinin ekleneceği sıfır-bazlı indeks. |
| x | **float** | Yeni ses çerçevesinin x koordinatı, nokta biriminde. |
| y | **float** | Yeni ses çerçevesinin y koordinatı, nokta biriminde. |
| width | **float** | Yeni ses çerçevesinin genişliği, nokta biriminde. |
| height | **float** | Yeni ses çerçevesinin yüksekliği, nokta biriminde. |
| audio | [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio) | Gömmek için Presentation.Audios koleksiyonundan bir [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio) örneği. |



### Ayrıca Bakınız
* sınıf [`IAudio`](/slides/python-net/tr/aspose.slides/iaudio)
* sınıf [`IAudioFrame`](/slides/python-net/tr/aspose.slides/iaudioframe)
* sınıf [`ShapeCollection`](/slides/python-net/tr/aspose.slides/shapecollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)