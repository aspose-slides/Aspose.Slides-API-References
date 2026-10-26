---
title: ReplaceText()
second_title: Справочник API Aspose.Slides для C++
description: Заменяет все вхождения указанного текста другим указанным текстом.
type: docs
weight: 170
url: /ru/aspose.slides/textframe/replacetext/
---
## TextFrame::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) метод

Заменяет все вхождения указанного текста другим указанным текстом.

```cpp
void Aspose::Slides::TextFrame::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | Строка, подлежащая замене. |
| newText | [System::String](../../../system/string/) | Строка, заменяющая все вхождения oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Параметры поиска текста [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Объект обратного вызова для сохранения результата операции замены [IFindResultCallback](../../ifindresultcallback/). |
## Примечания

Следующий пример кода показывает, как заменить одну указанную строку другой указанной строкой.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");
auto shape = System::ExplicitCast<AutoShape>(presentation->get_Slide(0)->get_Shape(0));

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Заменить все отдельные вхождения 'the' на '<em><strong>'
shape->get_TextFrame()->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [ITextSearchOptions](../../itextsearchoptions/)
* Класс [IFindResultCallback](../../ifindresultcallback/)
* Класс [TextFrame](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)