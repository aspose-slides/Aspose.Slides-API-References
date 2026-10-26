---
title: AddFromHtml()
second_title: Aspose.Slides для C++ справочник API
description: Добавляет текст из указанной HTML-строки в коллекцию.
type: docs
weight: 157
url: /ru/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) метод

Добавляет текст из указанной HTML-строки в коллекцию.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-текст. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) метод

Добавляет текст из указанной HTML-строки в коллекцию.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-текст. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект обратного вызова разрешателя, который разрешает URI и получает связанные объекты. |
| uri | [System::String](../../../system/string/) | URI для добавления HTML-документа. Используется для разрешения относительных ссылок. |

## Примечания

Указание разрешателя может потенциально создать уязвимость. Используйте с осторожностью.

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [String](../../../system/string/)
* Класс [ParagraphCollection](../)
* Класс [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)