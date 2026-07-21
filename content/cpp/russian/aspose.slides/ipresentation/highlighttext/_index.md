---
title: HighlightText()
second_title: Aspose.Slides для C++ справочника API
description: Выделяет все совпадения образца текста указанным цветом.
type: docs
weight: 456
url: /ru/aspose.slides/ipresentation/highlighttext/
---
## IPresentation::HighlightText(System::String, System::Drawing::Color) метод


Выделяет все совпадения образца текста указанным цветом.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Текст для выделения. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Цвет для выделения текста. |
## Примечания



Следующий пример кода демонстрирует, как выделить текст в презентации PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// выделение всех отдельных вхождений 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet());
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## IPresentation::HighlightText(System::String, System::Drawing::Color, System::SharedPtr\<ITextSearchOptions\>, System::SharedPtr\<IFindResultCallback\>) метод


Выделяет все совпадения образца текста указанным цветом.

```cpp
virtual void Aspose::Slides::IPresentation::HighlightText(System::String text, System::Drawing::Color highlightColor, System::SharedPtr<ITextSearchOptions> options, System::SharedPtr<IFindResultCallback> callback)=0
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | Текст для выделения. |
| highlightColor | [System::Drawing::Color](../../../system.drawing/color/) | Цвет для выделения текста. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ITextSearchOptions](../../itextsearchoptions/)\> | Параметры поиска текста [ITextSearchOptions](../../itextsearchoptions/). |
| callback | [System::SharedPtr](../../../system/sharedptr/)\<[IFindResultCallback](../../ifindresultcallback/)\> | Объект обратного вызова для получения результатов поиска [IFindResultCallback](../../ifindresultcallback/). |
## Примечания



Следующий пример кода демонстрирует, как выделить текст в презентации PowerPoint. 
```cpp
auto presentation = System::MakeObject<Presentation>(u"SomePresentation.pptx");

auto textSearchOptions = System::MakeObject<TextSearchOptions>();
textSearchOptions->set_WholeWordsOnly(true);

// выделение всех отдельных вхождений 'the'
presentation->HighlightText(u"the", System::Drawing::Color::get_Violet(), textSearchOptions, nullptr);
presentation->Save(u"SomePresentation-out2.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [Color](../../../system.drawing/color/)
* Класс [IPresentation](../)
* Класс [ITextSearchOptions](../../itextsearchoptions/)
* Класс [IFindResultCallback](../../ifindresultcallback/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)