---
title: add_video method
second_title: Aspose.Slides for Python via .NET API Referansı
description: 
type: docs
url: /tr/aspose.slides/videocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Başka bir sunumdan bir video dosyasının kopyasını ekler.

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
Bir sunuma bir video oluşturur ve ekler, bayt dizisinden.

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
Bir akıştan bir video oluşturur ve sunuma ekler.

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
* enumerasyon [`LoadingStreamBehavior`](/slides/python-net/tr/aspose.slides/loadingstreambehavior)
* sınıf [`VideoCollection`](/slides/python-net/tr/aspose.slides/videocollection)
* modül [`aspose.slides`](/slides/python-net/tr/aspose.slides)
* kütüphane [`Aspose.Slides`](/slides/python-net)