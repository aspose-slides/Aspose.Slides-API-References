---
title: InsertAudioFrameEmbedded()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт новый аудиофрейм с внедрённым WAV-файлом и вставляет его в коллекцию фигур по указанному индексу. Встроенный аудио-файл добавляется в коллекцию Presentation.Audios.
type: docs
weight: 261
url: /ru/aspose.slides/ishapecollection/insertaudioframeembedded/
---
## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) метод

Создаёт новый аудиофрейм с внедрённым WAV-файлом и вставляет его в коллекцию фигур по указанному индексу. Встроенный аудио-файл добавляется в коллекцию Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой (отсчёт с нуля) индекс, по которому вставить аудиофрейм. |
| x | **float** | Координата x нового аудиофрейма, в пунктах. |
| y | **float** | Координата y нового аудиофрейма, в пунктах. |
| width | **float** | Ширина нового аудиофрейма, в пунктах. |
| height | **float** | Высота нового аудиофрейма, в пунктах. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Входной поток, содержащий WAV-аудиоданные для внедрения. |

### Возвращаемое значение

Недавно созданный [IAudioFrame](../../iaudioframe/).

## IShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) метод

Создаёт новый аудиофрейм и вставляет его в коллекцию фигур по указанному индексу, используя существующий объект аудио из списка Presentation.Audios.

```cpp
virtual System::SharedPtr<IAudioFrame> Aspose::Slides::IShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нулевой (отсчёт с нуля) индекс, по которому вставить аудиофрейм. |
| x | **float** | Координата x нового аудиофрейма, в пунктах. |
| y | **float** | Координата y нового аудиофрейма, в пунктах. |
| width | **float** | Ширина нового аудиофрейма, в пунктах. |
| height | **float** | Высота нового аудиофрейма, в пунктах. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Экземпляр [IAudio](../../iaudio/) из коллекции Presentation.Audios для внедрения. |

### Возвращаемое значение

Недавно созданный [IAudioFrame](../../iaudioframe/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAudioFrame](../../iaudioframe/)
* Класс [Stream](../../../system.io/stream/)
* Класс [IShapeCollection](../)
* Класс [IAudio](../../iaudio/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)