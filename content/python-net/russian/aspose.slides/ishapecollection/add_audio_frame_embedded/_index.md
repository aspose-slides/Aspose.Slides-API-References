---
title: add_audio_frame_embedded method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/add_audio_frame_embedded/
weight: 20
---
## add_audio_frame_embedded(self, x, y, width, height, audio_stream) {#float-float-float-float-iorawiobase}
Создаёт новый аудио-кадр с внедрённым WAV-файлом и добавляет его в конец
            коллекции фигур. Встроенный аудио-файл добавляется в коллекцию Presentation.Audios.

### Возвращаемое значение

Новосозданный [`IAudioFrame`](/slides/python-net/ru/aspose.slides/iaudioframe).



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
| audio_stream | **io.RawIOBase** | Поток ввода, содержащий WAV-данные аудио для встраивания. |


## add_audio_frame_embedded(self, x, y, width, height, audio) {#float-float-float-float-iaudio}
Создаёт новый аудио-кадр и добавляет его в конец коллекции фигур,
            используя существующий объект аудио из списка Presentation.Audios.

### Возвращаемое значение

Новосозданный [`IAudioFrame`](/slides/python-net/ru/aspose.slides/iaudioframe).



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



### См. также
* класс [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio)
* класс [`IAudioFrame`](/slides/python-net/ru/aspose.slides/iaudioframe)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)