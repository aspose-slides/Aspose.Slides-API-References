---
title: GetPresentationInfo()
second_title: Aspose.Slides для C++ справка по API
description: Создаёт новый объект PresentationInfo из файла и привязывает к нему презентацию.
type: docs
weight: 27
url: /ru/aspose.slides/presentationfactory/getpresentationinfo/
---
## PresentationFactory::GetPresentationInfo(System::String) метод

Создаёт новый объект [PresentationInfo](../../presentationinfo/) из файла и привязывает презентацию к нему.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::String file) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) файл. |

### Возвращаемое значение

[Presentation](../../presentation/) информация, привязанная к презентации.

## PresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) метод

Создаёт новый объект [PresentationInfo](../../presentationinfo/) из потока и привязывает презентацию к нему. Получает информацию о презентации в указанном потоке.

```cpp
System::SharedPtr<IPresentationInfo> Aspose::Slides::PresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) поток. |

### Возвращаемое значение

[Presentation](../../presentation/) информация, привязанная к презентации.

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IPresentationInfo](../../ipresentationinfo/)
* Класс [String](../../../system/string/)
* Класс [PresentationFactory](../)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)