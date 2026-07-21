---
title: HighlightRegex()
second_title: Справочник API Aspose.Slides для C++
description: Выделяет все совпадения регулярного выражения указанным цветом.
type: docs
weight: 131
url: /ru/aspose.slides/itextframe/highlightregex/
---
## ITextFrame::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) метод

Выделяет все совпадения регулярного выражения указанным цветом.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Регулярное выражение [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) для получения строк, которые нужно выделить. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Цвет для выделения текста. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../ifindresultcallback/). |
## Примечания

Следующий пример кода показывает, как выделить текст в [TextFrame](../../textframe/) с помощью регулярного выражения. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// highlighting all words with 10 or more characters
shape->get_TextFrame()->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## ITextFrame::HighlightRegex(System::String, System::Drawing::Color, System::SharedPtr\<ITextHighlightingOptions\>) метод

Выделяет все совпадения регулярного выражения указанным цветом.

```cpp
virtual void Aspose::Slides::ITextFrame::HighlightRegex(System::String regex, System::Drawing::Color highlightColor, System::SharedPtr<ITextHighlightingOptions> options)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | [System::String](../../../system/string/) | Текст регулярного выражения для получения текста, который нужно выделить. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Цвет для выделения текста. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextHighlightingOptions](../../itexthighlightingoptions/)\> | Параметры выделения. |

Устарело
:   Используйте вместо этого метод HighlightRegex(Regex regex, Color highlightColor, IFindResultCallback callback). Метод будет удалён после выпуска версии 24.10.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Regex](../../../system.text.regularexpressions/regex/)
* Класс [Color](../../../system.drawing/color/)
* Класс [IFindResultCallback](../../ifindresultcallback/)
* Класс [ITextFrame](../)
* Класс [String](../../../system/string/)
* Класс [ITextHighlightingOptions](../../itexthighlightingoptions/)
* Пространство имен [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)