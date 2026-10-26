---
title: AddAudio()
second_title: Aspose.Slides for C++ справочник API
description: Добавляет копию аудиофайла из другой презентации.
type: docs
weight: 53
url: /ru/aspose.slides/audiocollection/addaudio/
---
## AudioCollection::AddAudio(System::SharedPtr\<IAudio\>) метод

Добавляет копию аудиофайла из другой презентации.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<IAudio> audio) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Исходный аудио. |

### Возвращаемое значение

Добавленное аудио.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) метод

Создаёт и добавляет аудио в презентацию из потока.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, из которого добавляется аудио. |

### Возвращаемое значение

Добавленное аудио.

## AudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) метод

Создаёт и добавляет аудио в презентацию из потока.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, из которого добавляется видео аудио. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Поведение, которое будет применено к потоку. |

### Возвращаемое значение

Добавленное аудио.

## AudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) метод

Создаёт и добавляет аудио в презентацию из массива байтов.

```cpp
System::SharedPtr<IAudio> Aspose::Slides::AudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) байт. |

### Возвращаемое значение

Добавленное аудио.

## См. также

* Перечисление [LoadingStreamBehavior](../../loadingstreambehavior/)
* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Типовое определение [ArrayPtr](../../../system/arrayptr/)
* Класс [IAudio](../../iaudio/)
* Класс [AudioCollection](../)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)