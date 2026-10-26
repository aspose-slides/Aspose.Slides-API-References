---
title: add_video method
second_title: Aspose.Slides için Python üzerinden .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Bir başka sunumdan bir video dosyasının kopyasını ekler.

### Döndürür

Eklenen video.



```python
def add_video(self, video):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/tr/aspose.slides/ivideo) | Kaynak video. |


## add_video(self, video_data) {#bytes}
Bir bayt dizisinden bir videoyu sunuma oluşturur ve ekler.

### Döndürür

Eklenen video.



```python
def add_video(self, video_data):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| video_data | **bytes** | Video baytları. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Bir akıştan bir videoyu sunuma oluşturur ve ekler.

### Döndürür

Eklenen [`IVideo`](/slides/python-net/tr/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | **io.RawIOBase** | Video dosyasını eklemek için akış. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/tr/aspose.slides/loadingstreambehavior) | Akışa uygulanacak davranış. |



### Ayrıca Bakınız
* sınıf [`IVideo`](/slides/python-net/tr/aspose.slides/ivideo)
* sınıf [`IVideoCollection`](/slides/python-net/tr/aspose.slides/ivideocollection)
* enum [`LoadingStreamBehavior`](/slides/python-net/tr/aspose.slides/loadingstreambehavior)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)