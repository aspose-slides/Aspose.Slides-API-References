---
title: HighlightRegex()
second_title: Aspose.Slides для C++ справочник API
description: Выделяет все совпадения регулярного выражения указанным цветом.
type: docs
weight: 157
url: /ru/aspose.slides/textframe/highlightregex/
---
## TextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) метод

Выделяет все совпадения регулярного выражения указанным цветом.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Текст регулярного выражения для получения текста, который необходимо выделить. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Цвет, которым нужно выделить текст. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Параметры выделения. |

## Примечания

Устарело
:   Используйте вместо этого метод HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback). Этот метод будет удалён после выпуска версии 24.10.

В следующем примере кода показано, как выделить текст в [TextFrame](../) с помощью регулярного выражения. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto options = System::MakeObject<TextHighlightingOptions>();

// выделение всех слов, содержащих 10 или более символов
shape->get_TextFrame()->HighlightRegex(u"\\b[^\\s]{10,}\\b", System::Drawing::Color::get_Blue(), options);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## TextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) метод

Выделяет все совпадения регулярного выражения указанным цветом.

```cpp
void Aspose::Slides::TextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Регулярное выражение [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) для получения строк, которые нужно выделить. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Цвет, которым нужно выделить текст. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../ifindresultcallback/). |

## Примечания

В следующем примере кода показано, как выделить текст в [TextFrame](../) с помощью регулярного выражения. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");
// выделение всех слов, содержащих 10 или более символов
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [Color](../../../system.drawing/color/)
* Class [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Class [TextFrame](../)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)