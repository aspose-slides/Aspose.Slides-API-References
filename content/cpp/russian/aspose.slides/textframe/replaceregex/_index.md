---
title: ReplaceRegex()
second_title: Aspose.Slides для C++ справочник API
description: Заменяет все совпадения регулярного выражения указанной строкой.
type: docs
weight: 183
url: /ru/aspose.slides/textframe/replaceregex/
---
## TextFrame::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) метод

Заменяет все совпадения регулярного выражения указанной строкой.

```cpp
void Aspose::Slides::TextFrame::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Регулярное выражение [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) для получения строк, подлежащих замене. |
| newText | [System::String](../../../system/string/) | Строка, заменяющая все вхождения строк, подлежащих замене. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Объект обратного вызова для сохранения результата операции замены [IFindResultCallback](../../ifindresultcallback/). |
## Примечания

Следующий пример кода показывает, как заменить текст с помощью регулярного выражения указанной строкой. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
shape->get_TextFrame()->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Regex](../../../system.text.regularexpressions/regex/)
* Class [String](../../../system/string/)
* Class [IFindResultCallback](../../ifindresultcallback/)
* Class [TextFrame](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)