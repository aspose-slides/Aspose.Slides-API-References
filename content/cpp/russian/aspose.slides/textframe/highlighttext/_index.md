---
title: HighlightText()
second_title: Aspose.Slides для C++ справочник API
description: Подсвечивает все совпадения образца текста заданным цветом.
type: docs
weight: 131
url: /ru/aspose.slides/textframe/highlighttext/
---
## TextFrame::HighlightText(System::String, System::Drawing::Color) метод

Подсвечивает все совпадения образца текста заданным цветом.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor) override
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Текстовый образец для подсветки. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Цвет для подсветки текста. |

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) метод

Подсвечивает все совпадения образца текста заданным цветом.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Текст для подсветки. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Цвет для подсветки текста. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Параметры подсветки. |

## Примечания

Устарело
:   Используйте HighlightText(string text, Color highlightColor, ITextSearchOptions options) метод вместо этого. Метод будет удалён после выпуска версии 24.10.

Следующий пример кода показывает, как подсветить текст в [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// highlighting all words 'important'
shape->get_TextFrame()->HighlightText(u"title", System::Drawing::Color::get_LightBlue());

auto textHighlightOptions = System::MakeObject<TextHighlightingOptions>();
textHighlightOptions->set_WholeWordsOnly(true);

// highlighting all separate 'the' occurrences
shape->get_TextFrame()->HighlightText(u"to", System::Drawing::Color::get_Violet(), textHighlightOptions);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) метод

Подсвечивает все совпадения образца текста заданным цветом.

```cpp
void Aspose::Slides::TextFrame::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Текст для подсветки. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Цвет для подсветки текста. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Параметры поиска текста [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../ifindresultcallback/). |

## Примечания



Следующий пример кода показывает, как подсветить текст в [TextFrame](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

// подсветка всех слов 'important'
shape->get_TextFrame()->HighlightText(u"important", System::Drawing::Color::get_LightBlue());

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// подсветка всех отдельных вхождений 'the'
shape->get_TextFrame()->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [Color](../../../system.drawing/color/)
* Класс [TextFrame](../)
* Класс [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Класс [ITextSearchOptions](../../itextsearchoptions/)
* Класс [IFindResultCallback](../../ifindresultcallback/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)