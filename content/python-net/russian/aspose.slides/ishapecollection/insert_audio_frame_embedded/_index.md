---
title: insert_audio_frame_embedded method
second_title: Aspose.Slides для Python через .NET API Reference
description: 
type: docs
url: /ru/aspose.slides/ishapecollection/insert_audio_frame_embedded/
weight: 210
---
## insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream) {#int-float-float-float-float-iorawiobase}
Создаёт новый аудиофрейм с встроенным WAV-файлом и вставляет его в коллекцию фигур по указанному индексу. Встроенный аудио-файл добавляется в коллекцию Presentation.Audios.

### Возвращаемое значение

Недавно созданный [`IAudioFrame`](/slides/python-net/ru/aspose.slides/iaudioframe).

```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio_stream):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому будет вставлен аудиофрейм. |
| x | **float** | Координата x нового аудиофрейма в пунктах. |
| y | **float** | Координата y нового аудиофрейма в пунктах. |
| width | **float** | Ширина нового аудиофрейма в пунктах. |
| height | **float** | Высота нового аудиофрейма в пунктах. |
| audio_stream | **io.RawIOBase** | Входной поток, содержащий WAV-аудиоданные для встраивания. |

## insert_audio_frame_embedded(self, index, x, y, width, height, audio) {#int-float-float-float-float-iaudio}
Создаёт новый аудиофрейм и вставляет его в коллекцию фигур по указанному индексу, используя существующий объект аудио из списка Presentation.Audios.

### Возвращаемое значение

Недавно созданный [`IAudioFrame`](/slides/python-net/ru/aspose.slides/iaudioframe).

```python
def insert_audio_frame_embedded(self, index, x, y, width, height, audio):
    ...
```

| Параметр | Тип | Описание |
| :- | :- | :- |
| index | **int** | Нулевой индекс, по которому будет вставлен аудиофрейм. |
| x | **float** | Координата x нового аудиофрейма в пунктах. |
| y | **float** | Координата y нового аудиофрейма в пунктах. |
| width | **float** | Ширина нового аудиофрейма в пунктах. |
| height | **float** | Высота нового аудиофрейма в пунктах. |
| audio | [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio) | Экземпляр [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio) из коллекции Presentation.Audios для встраивания. |

### См. также
* класс [`IAudio`](/slides/python-net/ru/aspose.slides/iaudio)
* класс [`IAudioFrame`](/slides/python-net/ru/aspose.slides/iaudioframe)
* класс [`IShapeCollection`](/slides/python-net/ru/aspose.slides/ishapecollection)
* модуль [`aspose.slides`](/slides/python-net/ru/aspose.slides)
* библиотека [`Aspose.Slides`](/slides/python-net)