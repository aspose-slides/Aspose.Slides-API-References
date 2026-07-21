---
title: ReplaceRegex()
second_title: Aspose.Slides для C++ справка по API
description: Заменяет все совпадения регулярного выражения указанной строкой.
type: docs
weight: 495
url: /ru/aspose.slides/ipresentation/replaceregex/
---
## IPresentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) method

Заменяет все совпадения регулярного выражения указанной строкой.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Регулярное выражение [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) для получения строк, которые нужно заменить. |
| newText | [System::String](../../../system/string/) | Строка, заменяющая все вхождения строк, которые нужно заменить. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../ifindresultcallback/). |

## Remarks

Следующий пример кода показывает, как заменить текст, используя регулярное выражение, указанной строкой.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Replace all words with 10 or more characters with '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Regex](../../../system.text.regularexpressions/regex/)
* Класс [String](../../../system/string/)
* Класс [IFindResultCallback](../../ifindresultcallback/)
* Класс [IPresentation](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)