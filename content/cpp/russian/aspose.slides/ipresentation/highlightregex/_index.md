---
title: HighlightRegex()
second_title: Справочник API Aspose.Slides для C++
description: Выделяет все совпадения регулярного выражения указанным цветом.
type: docs
weight: 469
url: /ru/aspose.slides/ipresentation/highlightregex/
---
## IPresentation::HighlightRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::Drawing::Color, System::SharedPtr\<IFindResultCallback\>) метод

Выделяет все совпадения регулярного выражения указанным цветом.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::Drawing::Color highlightColor, System::SharedPtr<IFindResultCallback> callback)=0
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Регулярное выражение [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) для получения строк, которые нужно выделить. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Цвет для выделения текста. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../ifindresultcallback/). |
## Примечания

Следующий пример кода показывает, как выделять текст в PowerPoint [Presentation](../../presentation/) с помощью регулярного выражения.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// выделение всех слов, содержащих 10 и более символов
presentation->HighlightRegex(regex, System::Drawing::Color::get_Blue(), nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [Color](../../../system.drawing/color/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [IPresentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)