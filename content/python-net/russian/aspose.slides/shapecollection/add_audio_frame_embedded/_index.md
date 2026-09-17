---
title: add_audio_frame_embedded method
second_title: Aspose.Slides для Python через .NET справочник API
description: 
type: docs
url: /ru/aspose.slides/shapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Создает новый аудио-кадр с вложенным WAV-файлом и добавляет его в конец коллекции фигур. Встроенный аудио-файл добавляется в коллекцию Presentation.Audios.

### Возвращаемое значение

Созданный [`IAudioFrame`](/slides/python-net/ru/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio_stream):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x нового аудио-кадра в пунктах. |
| y | **float** | Координата y нового аудио-кадра в пунктах. |
| width | **float** | Ширина нового аудио-кадра в пунктах. |
| height | **float** | Высота нового аудио-кадра в пунктах. |
| audio_stream | **io.RawIOBase** | Входной поток, содержащий WAV-аудиоданные для встраивания. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Создает новый аудио-кадр и добавляет его в конец коллекции фигур, используя существующий объект аудио из списка Presentation.Audios.

### Возвращаемое значение

Созданный [`IAudioFrame`](/slides/python-net/ru/aspose.slides/iaudioframe).



```python
def add_audio_frame_embedded(self, x, y, width, height, audio):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| x | **float** | Координата x нового аудио-кадра в пунктах. |
| y | **float** | Координата y нового аудио-кадра в пунктах. |
| width | **float** | Ширина нового аудио-кадра в пунктах. |
| height | **float** | Высота нового аудио-кадра в пунктах. |
| audio | [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio) | Экземпляр [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio) из коллекции Presentation.Audios. |



### Смотрите также
* класс [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio)
* класс [`IAudioFrame`](/slides/python-net/ru/aspose.slides/iaudioframe)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)