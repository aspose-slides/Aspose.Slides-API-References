---
title: Add()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет закрытые субтитры WebVTT в конец коллекции.
type: docs
weight: 27
url: /ru/aspose.slides/icaptionscollection/add/
---
## ICaptionsCollection::Add(System::String, System::String) метод

Adds WebVTT closed captions to the end of the collection.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::String filePath)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | The label of the closed captions. |
| filePath | [System::String](../../../system/string/) | The path to the WebVTT file. |

### Возвращаемое значение

Возвращаемый экземпляр [ICaptions](../../icaptions/).

## ICaptionsCollection::Add(System::String, System::SharedPtr\<System::IO::Stream\>) метод

Adds WebVTT closed captions to the end of the collection from a stream.

```cpp
virtual System::SharedPtr<ICaptions> Aspose::Slides::ICaptionsCollection::Add(System::String label, System::SharedPtr<System::IO::Stream> stream)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| label | [System::String](../../../system/string/) | The label of the closed captions. |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | The input stream containing data in WebVTT format. |

### Возвращаемое значение

Возвращаемый экземпляр [ICaptions](../../icaptions/).

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ICaptions](../../icaptions/)
* Class [String](../../../system/string/)
* Class [ICaptionsCollection](../)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)