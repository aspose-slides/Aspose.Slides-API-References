---
title: insert_audio_frame_embedded method
second_title: Справочник API Aspose.Slides для Python через .NET
description: 
type: docs
url: /ru/aspose.slides/shapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Создает новый аудиофрейм с встроенным WAV-файлом и вставляет его в коллекцию shape в указанном индексе. Встроенный аудио добавляется в коллекцию Presentation.Audios.

### Возвращаемое значение

Созданный [`IAudioFrame`](/slides/python-net/ru/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, в котором следует вставить аудиофрейм. |
| x | **float** | Координата x нового аудиофрейма в пунктах. |
| y | **float** | Координата y нового аудиофрейма в пунктах. |
| width | **float** | Ширина нового аудиофрейма в пунктах. |
| height | **float** | Высота нового аудиофрейма в пунктах. |
| audio_stream | **io.RawIOBase** | Входной поток, содержащий WAV-данные для встраивания. |


## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Создает новый аудиофрейм и вставляет его в коллекцию shape в указанном индексе, используя существующий объект audio из списка Presentation.Audios.

### Возвращаемое значение

Созданный [`IAudioFrame`](/slides/python-net/ru/aspose.slides/iaudioframe).



```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```


| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, в котором следует вставить аудиофрейм. |
| x | **float** | Координата x нового аудиофрейма в пунктах. |
| y | **float** | Координата y нового аудиофрейма в пунктах. |
| width | **float** | Ширина нового аудиофрейма в пунктах. |
| height | **float** | Высота нового аудиофрейма в пунктах. |
| audio | [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio) | Экземпляр [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio) из коллекции Presentation.Audios для встраивания. |



### См. также
* класс [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio)
* класс [`IAudioFrame`](/slides/python-net/ru/aspose.slides/iaudioframe)
* класс [`ShapeCollection`](/slides/python-net/ru/aspose.slides/shapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)