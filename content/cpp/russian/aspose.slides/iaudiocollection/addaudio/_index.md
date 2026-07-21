---
title: AddAudio()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет копию аудиофайла из другой презентации.
type: docs
weight: 14
url: /ru/aspose.slides/iaudiocollection/addaudio/
---
## IAudioCollection::AddAudio(System::SharedPtr\<IAudio\>) метод

Добавляет копию аудиофайла из другой презентации.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<IAudio> audio)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| audio | [System::SharedPtr](../../../system/sharedptr/)\<[IAudio](../../iaudio/)\> | Исходное аудио. |

### Возвращаемое значение

Добавленное аудио.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>) метод

Создаёт и добавляет аудио в презентацию из потока.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, из которого добавляется аудио. |

### Возвращаемое значение

Добавленное аудио.

Устарело
:   Используйте AddAudio(Stream stream, LoadingStreamBehavior loadingStreamBehavior). Метод будет удалён в версии 17.10.

## IAudioCollection::AddAudio(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) метод

Создаёт и добавляет аудио в презентацию из потока.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, из которого добавляется видео-аудио. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Поведение, которое будет применено к потоку. |

### Возвращаемое значение

Добавленное аудио.

## IAudioCollection::AddAudio(System::ArrayPtr\<uint8_t\>) метод

Создаёт и добавляет аудио в презентацию из массива байтов.

```cpp
virtual System::SharedPtr<IAudio> Aspose::Slides::IAudioCollection::AddAudio(System::ArrayPtr<uint8_t> audioData)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| audioData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Audio](../../audio/) байт. |

### Возвращаемое значение

Добавленное аудио.

## См. также

* Перечисление [LoadingStreamBehavior](../../loadingstreambehavior/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [IAudio](../../iaudio/)
* Класс [IAudioCollection](../)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)