---
title: HighlightText()
second_title: Aspose.Slides для C++ справочник API
description: Выделяет все совпадения образца текста указанным цветом.
type: docs
weight: 105
url: /ru/aspose.slides/itextframe/highlighttext/
---
## ITextFrame::HighlightText(System::String, System::Drawing::Color) метод

Выделяет все совпадения образца текста указанным цветом.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Текст для выделения. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Цвет для выделения текста. |

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) метод

Выделяет все совпадения образца текста указанным цветом.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Текст для выделения. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Цвет для выделения текста. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Параметры выделения. |

Устаревший
:   Используйте HighlightText(string text, Color highlightColor, ITextSearchOptions options, IFindResultCallback callback) метод instead. Метод будет удалён после выпуска версии 24.10.

## ITextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) метод

Выделяет все совпадения образца текста указанным цветом.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Текст для выделения. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Цвет для выделения текста. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Параметры поиска текста [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../ifindresultcallback/). |

## Примечания

Следующий пример кода демонстрирует, как выделить текст в [TextFrame](../../textframe/). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [Color](../../../system.drawing/color/)
* Класс [ITextFrame](../)
* Класс [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Класс [ITextSearchOptions](../../itextsearchoptions/)
* Класс [IFindResultCallback](../../ifindresultcallback/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)