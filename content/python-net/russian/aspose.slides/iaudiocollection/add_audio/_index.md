---
title: add_audio method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/iaudiocollection/add_audio/
weight: 10
---
## add_audio(self, audio) {#iaudio}
Добавляет копию аудиофайла из другой презентации.

### Returns
Добавленное аудио.

```python
def add_audio(self, audio):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| audio | [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio) | Исходное аудио. |

## add_audio(self, stream) {#iorawiobase}
Создаёт и добавляет аудио в презентацию из потока.

### Returns
Добавленное аудио.

```python
def add_audio(self, stream):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Поток, из которого добавить аудио. |

## add_audio(self, audio_data) {#bytes}
Создаёт и добавляет аудио в презентацию из массива байтов.

### Returns
Добавленное аудио.

```python
def add_audio(self, audio_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| audio_data | **bytes** | Байты аудио. |

## add_audio(self, stream, loading_stream_behavior) {#iorawiobase-loadingstreambehavior}
Создаёт и добавляет аудио в презентацию из потока.

### Returns
Добавленное аудио.

```python
def add_audio(self, stream, loading_stream_behavior):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| stream | **io.RawIOBase** | Поток, из которого добавить аудио-видео. |
| loading_stream_behavior | [`LoadingStreamBehavior`](/slides/python-net/ru/aspose.slides/loadingstreambehavior) | Поведение, которое будет применено к потоку. |

### See Also
* класс [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio)
* класс [`IAudioCollection`](/slides/python-net/ru/aspose.slides/iaudiocollection)
* перечисление [`LoadingStreamBehavior`](/slides/python-net/ru/aspose.slides/loadingstreambehavior)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)