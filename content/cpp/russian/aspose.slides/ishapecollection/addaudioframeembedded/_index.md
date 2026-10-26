---
title: AddAudioFrameEmbedded()
second_title: Aspose.Slides для C++ справочник API
description: Создает новый аудиофрейм с вложенным WAV-файлом и добавляет его в конец коллекции фигур. Встроенный аудио-файл добавляется в коллекцию Presentation.Audios.
type: docs
weight: 248
url: /ru/aspose.slides/ishapecollection/addaudioframeembedded/
---
## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<System::IO::Stream\>) method


Создает новый аудиофрейм с вложенным WAV-файлом и добавляет его в конец коллекции фигур. Встроенный аудиофайл добавляется в коллекцию Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | X-координата нового аудиофрейма, в пунктах. |
| y | **float** | Y-координата нового аудиофрейма, в пунктах. |
| width | **float** | Ширина нового аудиофрейма, в пунктах. |
| height | **float** | Высота нового аудиофрейма, в пунктах. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток ввода, содержащий WAV-аудиоданные для встраивания. |

### Возвращаемое значение

The newly created [IAudioFrame](../../iaudioframe/).

## IShapeCollection::AddAudioFrameEmbedded(float, float, float, float, System::SharedPtr\<IAudio\>) method


Создает новый аудиофрейм и добавляет его в конец коллекции фигур, используя существующий объект аудио из списка Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::AddAudioFrameEmbedded(float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```


### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| x | **float** | X-координата нового аудиофрейма, в пунктах. |
| y | **float** | Y-координата нового аудиофрейма, в пунктах. |
| width | **float** | Ширина нового аудиофрейма, в пунктах. |
| height | **float** | Высота нового аудиофрейма, в пунктах. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Экземпляр [IAudio](../../iaudio/) из коллекции Presentation.Audios. |

### Возвращаемое значение

The newly created [IAudioFrame](../../iaudioframe/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAudioFrame](../../iaudioframe/)
* Класс [Stream](../../../system.io/stream/)
* Класс [IShapeCollection](../)
* Класс [IAudio](../../iaudio/)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)