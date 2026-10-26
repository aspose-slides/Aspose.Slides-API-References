---
title: ExportToHtml()
second_title: Справочник API Aspose.Slides для C++
description: Преобразует указанные абзацы в HTML и возвращает его в виде объекта String.
type: docs
weight: 105
url: /ru/aspose.slides/iparagraphcollection/exporttohtml/
---
## IParagraphCollection::ExportToHtml(int32_t, int32_t, System::SharedPtr\<Export::ITextToHtmlConversionOptions\>) метод

Преобразует указанные абзацы в HTML и возвращает его в виде объекта String.

```cpp
virtual System::String Aspose::Slides::IParagraphCollection::ExportToHtml(int32_t firstParagraphIndex, int32_t paragraphsCount, System::SharedPtr<Export::ITextToHtmlConversionOptions> options)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| firstParagraphIndex | **int32_t** | Индекс первого абзаца **int32_t** |
| paragraphsCount | **int32_t** | [Paragraph](../../paragraph/) количество **int32_t** |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)\> | Параметры преобразования [Export::ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/) |

### Возвращаемое значение

Сгенерированный HTML.

## См. также

* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [ITextToHtmlConversionOptions](../../../aspose.slides.export/itexttohtmlconversionoptions/)
* Класс [IParagraphCollection](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)