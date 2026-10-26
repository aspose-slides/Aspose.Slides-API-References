---
title: add_video method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/videocollection/add_video/
weight: 10
---
## add_video(self, video) {#ivideo}
Добавляет копию видеофайла из другой презентации.

### Возвращаемое значение

Добавленное видео.



```python
def add_video(self, video):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| video | [`IVideo`](/slides/python-net/ru/aspose.slides/ivideo) | Исходное видео. |


## add_video(self, video_data) {#bytes}
Создаёт и добавляет видео в презентацию из массива байтов.

### Возвращаемое значение

Добавленное видео.



```python
def add_video(self, video_data):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| video_data | **bytes** | Байты видео. |


## add_video(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Создаёт и добавляет видео в презентацию из потока.

### Возвращаемое значение

Добавлен [`IVideo`](/slides/python-net/ru/aspose.slides/ivideo).



```python
def add_video(self, stream, loading_stream_behavior):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Поток, из которого добавляется видеофайл. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/ru/aspose.slides/loadingstreambehavior) | Поведение, которое будет применено к потоку. |



### См. также
* класс [`IVideo`](/slides/python-net/ru/aspose.slides/ivideo)
* перечисление [`LoadingStreamBehavior`](/slides/python-net/ru/aspose.slides/loadingstreambehavior)
* класс [`VideoCollection`](/slides/python-net/ru/aspose.slides/videocollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)