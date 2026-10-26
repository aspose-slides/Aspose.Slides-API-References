---
title: ReplaceRegex()
second_title: Справочник API Aspose.Slides для C++
description: Заменяет все совпадения регулярного выражения указанной строкой.
type: docs
weight: 534
url: /ru/aspose.slides/presentation/replaceregex/
---
## Presentation::ReplaceRegex(System::SharedPtr\<System::Text::RegularExpressions::Regex\>, System::String, System::SharedPtr\<IFindResultCallback\>) method


Заменяет все совпадения регулярного выражения указанной строкой.

```cpp
void Aspose::Slides::Presentation::ReplaceRegex(System::SharedPtr<System::Text::RegularExpressions::Regex> regex, System::String newText, System::SharedPtr<IFindResultCallback> callback) override
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| regex | [System::SharedPtr](../../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/)\> | Регулярное выражение [System::Text::RegularExpressions::Regex](../../../system.text.regularexpressions/regex/) для получения строк, которые нужно заменить. |
| newText | [System::String](../../../system/string/) | Строка, которой заменяются все вхождения заменяемых строк. |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../ifindresultcallback/). |
## Примечания



Следующий пример кода демонстрирует, как заменить текст с помощью регулярного выражения указанной строкой. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto regex = System::MakeObject<System::Text::RegularExpressions::Regex>(u"\\b[^\\s]{10,}\\b");

// Заменить все слова длиной 10 и более символов на '<em><strong>'
presentation->ReplaceRegex(regex, u"</strong></em>", nullptr);
presentation->Save(u"SomePresentation-out.pptx", SaveFormat::Pptx);
```

## Смотрите также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [Regex](../../../system.text.regularexpressions/regex/)
* Класс [String](../../../system/string/)
* Класс [IFindResultCallback](../../ifindresultcallback/)
* Класс [Presentation](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)