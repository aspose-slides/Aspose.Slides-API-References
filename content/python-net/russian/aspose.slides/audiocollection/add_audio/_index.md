---
title: add_audio method
second_title: Aspose.Slides для Python через .NET API справка
description: 
type: docs
url: /ru/aspose.slides/audiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
Добавляет копию аудиофайла из другой презентации.

### Возвращаемое значение

Добавленное аудио.



```python
def add_audio(self, audio):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio) | Исходный аудио. |


## add_audio(self, stream) {#iorawiobase}
Создаёт и добавляет аудио в презентацию из потока.

### Возвращаемое значение

Добавленное аудио.



```python
def add_audio(self, stream):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Поток, из которого добавляется аудио. |


## add_audio(self, audio_data) {#bytes}
Создаёт и добавляет аудио в презентацию из массива байтов.

### Возвращаемое значение

Добавленное аудио.



```python
def add_audio(self, audio_data):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| audio_data | **bytes** | Байты аудио. |


## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Создаёт и добавляет аудио в презентацию из потока.

### Возвращаемое значение

Добавленное аудио.



```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| stream | **io.RawIOBase** | Поток, из которого добавляется аудио видео. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/ru/aspose.slides/loadingstreambehavior) | Поведение, которое будет применено к потоку. |



### См. также
* класс [`AudioCollection`](/slides/python-net/ru/aspose.slides/audiocollection)
* класс [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio)
* перечисление [`LoadingStreamBehavior`](/slides/python-net/ru/aspose.slides/loadingstreambehavior)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)