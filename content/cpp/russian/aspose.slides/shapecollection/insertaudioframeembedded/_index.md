---
title: InsertAudioFrameEmbedded()
second_title: Aspose.Slides для справки по API C++
description: "Создаёт новый аудиофрейм с вложенным WAV-файлом и вставляет его в коллекцию фигур в указанном индексе. Встроенный аудио добавляется в коллекцию Presentation::get_Audios."
type: docs
weight: 300
url: /ru/aspose.slides/shapecollection/insertaudioframeembedded/
---
## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<System::IO::Stream\>) метод

Создаёт новый аудиофрейм с вложенным WAV-файлом и вставляет его в коллекцию фигур в указанном индексе. Встроенный аудио добавляется в коллекцию [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<System::IO::Stream> audio_stream) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нуль-базовый индекс, в котором будет вставлен аудиофрейм. |
| x | **float** | Координата x нового аудиофрейма в пунктах. |
| y | **float** | Координата y нового аудиофрейма в пунктах. |
| width | **float** | Ширина нового аудиофрейма в пунктах. |
| height | **float** | Высота нового аудиофрейма в пунктах. |
| audio_stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток ввода, содержащий данные WAV-аудио для встраивания. |

### Возвращаемое значение

Новосозданный [IAudioFrame](../../iaudioframe/).

## ShapeCollection::InsertAudioFrameEmbedded(int32_t, float, float, float, float, System::SharedPtr\<IAudio\>) метод

Создаёт новый аудиофрейм и вставляет его в коллекцию фигур в указанном индексе, используя существующий объект аудио из списка [Presentation::get_Audios](../../presentation/get_audios/).

```cpp
System::SharedPtr<IAudioFrame> Aspose::Slides::ShapeCollection::InsertAudioFrameEmbedded(int32_t index, float x, float y, float width, float height, System::SharedPtr<IAudio> audio) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Нуль-базовый индекс, в котором будет вставлен аудиофрейм. |
| x | **float** | Координата x нового аудиофрейма в пунктах. |
| y | **float** | Координата y нового аудиофрейма в пунктах. |
| width | **float** | Ширина нового аудиофрейма в пунктах. |
| height | **float** | Высота нового аудиофрейма в пунктах. |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Экземпляр [IAudio](../../iaudio/) из коллекции [Presentation::get_Audios](../../presentation/get_audios/) для встраивания. |

### Возвращаемое значение

Новосозданный [IAudioFrame](../../iaudioframe/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IAudioFrame](../../iaudioframe/)
* Класс [Stream](../../../system.io/stream/)
* Класс [ShapeCollection](../)
* Класс [IAudio](../../iaudio/)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)