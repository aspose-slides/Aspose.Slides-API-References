---
title: ReplaceText()
second_title: Aspose.Slides для C++ справочник API
description: Заменяет все вхождения указанного текста другим указанным текстом.
type: docs
weight: 482
url: /ru/aspose.slides/ipresentation/replacetext/
---
## IPresentation::ReplaceText(System::String, System::String, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) метод

Заменяет все вхождения указанного текста другим указанным текстом.

```cpp
virtual void Aspose::Slides::IPresentation::ReplaceText(System::String oldText, System::String newText, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| oldText | [System::String](../../../system/string/) | Строка, которую нужно заменить. |
| newText | [System::String](../../../system/string/) | Строка, заменяющая все вхождения oldText. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Параметры поиска текста [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../ifindresultcallback/). |
## Примечания

Следующий пример кода показывает, как заменить одну указанную строку другой указанной строкой.
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// Заменить все отдельные вхождения 'the' на '<em><strong>'
presentation->ReplaceText(u"the", u"</strong></em>", textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [ITextSearchOptions](../../itextsearchoptions/)
* Класс [IFindResultCallback](../../ifindresultcallback/)
* Класс [IPresentation](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)