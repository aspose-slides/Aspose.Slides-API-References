---
title: FoundResult()
second_title: Справочник API Aspose.Slides для C++
description: Метод-обратного вызова, получающий данные о найденном тексте.
type: docs
weight: 1
url: /ru/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) метод

Метод-обратного вызова, который получает данные о найденном тексте.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | Объект [ITextFrame](../../itextframe/), в котором был найден текст. |
| sourceText | [System::String](../../../system/string/) | Исходный текст, в котором был найден текст. |
| foundText | [System::String](../../../system/string/) | Найденный текст. |
| textPosition | **int32_t** | Позиция найденного текста. |

## См. также

* typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ITextFrame](../../itextframe/)
* Класс [String](../../../system/string/)
* Класс [IFindResultCallback](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)