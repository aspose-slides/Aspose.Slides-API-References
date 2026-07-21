---
title: AddVideo()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет копию видеофайла из другой презентации.
type: docs
weight: 53
url: /ru/aspose.slides/videocollection/addvideo/
---
## VideoCollection::AddVideo(System::SharedPtr\<IVideo\>) метод

Добавляет копию видеофайла из другой презентации.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<IVideo> video) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| video | [System::SharedPtr](../../../system/sharedptr/)\<[IVideo](../../ivideo/)\> | Исходное видео. |

### Возвращаемое значение

Добавленное видео.

## VideoCollection::AddVideo(System::SharedPtr\<System::IO::Stream\>, LoadingStreamBehavior) метод

Создаёт и добавляет видео в презентацию из потока.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::SharedPtr<System::IO::Stream> stream, LoadingStreamBehavior loadingStreamBehavior) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Поток, из которого добавляется видеофайл. |
| loadingStreamBehavior | [LoadingStreamBehavior](../../loadingstreambehavior/) | Поведение, которое будет применено к потоку. |

### Возвращаемое значение

Добавлен [IVideo](../../ivideo/).

## VideoCollection::AddVideo(System::ArrayPtr\<uint8_t\>) метод


Создаёт и добавляет видео в презентацию из массива байтов.

```cpp
System::SharedPtr<IVideo> Aspose::Slides::VideoCollection::AddVideo(System::ArrayPtr<uint8_t> videoData) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| videoData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Video](../../video/) байт. |

### Возвращаемое значение

Добавленное видео.

## Смотрите также

* Enum [LoadingStreamBehavior](../../loadingstreambehavior/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [IVideo](../../ivideo/)
* Класс [VideoCollection](../)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)