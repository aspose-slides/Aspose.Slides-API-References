---
title: add_video method
second_title: Referensi API Aspose.Slides untuk Python via .NET
description: 
type: docs
url: /id/aspose.slides/ivideocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Menambahkan salinan file video dari presentasi lain.

### Mengembalikan

Video yang ditambahkan.



```python
def add_video(self, video):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/id/aspose.slides/ivideo) | Video sumber. |


## add_video(self, video_data) {#bytes}
Membuat dan menambahkan video ke presentasi dari array byte.

### Mengembalikan

Video yang ditambahkan.



```python
def add_video(self, video_data):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| video_data | **bytes** | Byte video. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Membuat dan menambahkan video ke presentasi dari aliran.

### Mengembalikan

Ditambahkan [`IVideo`](/slides/python-net/id/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| stream | **io.RawIOBase** | Aliran untuk menambahkan file video dari. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/id/aspose.slides/loadingstreambehavior) | Perilaku yang akan diterapkan pada aliran. |



### Lihat Juga
* class [`IVideo`](/slides/python-net/id/aspose.slides/ivideo)
* class [`IVideoCollection`](/slides/python-net/id/aspose.slides/ivideocollection)
* enumeration [`LoadingStreamBehavior`](/slides/python-net/id/aspose.slides/loadingstreambehavior)
* module [`aspose.slides`](/slides/python-net/id/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)