---
title: CreateMemoryStreamWrapper()
second_title: Aspose.Slides для C++ — справочник API
description: Создаёт обёртку MemoryStream.
type: docs
weight: 1
url: /ru/aspose.slides/istreamwrapperfactory/creatememorystreamwrapper/
---
## IStreamWrapperFactory::CreateMemoryStreamWrapper() метод

Создаёт обёртку MemoryStream.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper()=0
```

### Возвращаемое значение

Обёртка потока для COM-интерфейса [IStreamWrapper](../../istreamwrapper/)

## IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr\<uint8_t\>) метод

Создаёт обёртку MemoryStream на основе указанного массива байтов.

```cpp
virtual System::SharedPtr<IStreamWrapper> Aspose::Slides::IStreamWrapperFactory::CreateMemoryStreamWrapper(System::ArrayPtr<uint8_t> buffer)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Массив байтов **uint8_t**[] |

### Возвращаемое значение

Обёртка потока для COM-интерфейса [IStreamWrapper](../../istreamwrapper/)

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Тип [ArrayPtr](../../../system/arrayptr/)
* Класс [IStreamWrapper](../../istreamwrapper/)
* Класс [IStreamWrapperFactory](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)