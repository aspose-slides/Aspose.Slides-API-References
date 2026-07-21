---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет закрытые субтитры WebVTT в конец коллекции.
type: docs
weight: 27
url: /ru/aspose.slides/captionscollection/add/
---
## CaptionsCollection::Add(System::String, System::String) метод

Добавляет закрытые субтитры WebVTT в конец коллекции.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::String filePath) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Метка закрытых субтитров. |
| filePath | [System::String](../../../system/string/) | Путь к файлу WebVTT. |

### Возвращаемое значение

Добавленный экземпляр [ICaptions](../../icaptions/).

## CaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) метод

Добавляет закрытые субтитры WebVTT в конец коллекции из потока.

```cpp
System::SharedPtr<ICaptions> Aspose::Slides::CaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | Метка закрытых субтитров. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Входной поток, содержащий данные в формате WebVTT. |

### Возвращаемое значение

Добавленный экземпляр [ICaptions](../../icaptions/).

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [ICaptions](../../icaptions/)
* Класс [String](../../../system/string/)
* Класс [CaptionsCollection](../)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)