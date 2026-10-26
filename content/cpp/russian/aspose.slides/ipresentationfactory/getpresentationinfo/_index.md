---
title: GetPresentationInfo()
second_title: Aspose.Slides для C++ справка API
description: Получает информацию о презентации в указанном файле.
type: docs
weight: 14
url: /ru/aspose.slides/ipresentationfactory/getpresentationinfo/
---
## IPresentationFactory::GetPresentationInfo(System::String) метод


Получает информацию о презентации в указанном файле.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::String file)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | [Presentation](../../presentation/) файл. |

### Возвращаемое значение

[Presentation](../../presentation/) информация

## IPresentationFactory::GetPresentationInfo(System::SharedPtr\<System::IO::Stream\>) метод


Получает информацию о презентации в указанном потоке.

```cpp
virtual System::SharedPtr<IPresentationInfo> Aspose::Slides::IPresentationFactory::GetPresentationInfo(System::SharedPtr<System::IO::Stream> stream)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | [Presentation](../../presentation/) поток. |

### Возвращаемое значение

[Presentation](../../presentation/) информация.

## Смотрите также

* Определение типа [SharedPtr](../../../system/sharedptr/)
* Класс [IPresentationInfo](../../ipresentationinfo/)
* Класс [String](../../../system/string/)
* Класс [IPresentationFactory](../)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)