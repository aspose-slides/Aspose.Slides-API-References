---
title: AddFromHtml()
second_title: Справка API Aspose.Slides для C++
description: Добавляет текст из указанной HTML-строки в коллекцию.
type: docs
weight: 92
url: /ru/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) метод

Добавляет текст из указанной HTML-строки в коллекцию.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-текст. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) метод

Добавляет текст из указанной HTML-строки в коллекцию.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Параметры

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML-текст. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект обратного вызова разрешения, который разрешает URI и получает указанные объекты. |
| uri | [System::String](../../../system/string/) | URI для добавления HTML-документа. Используется для разрешения относительных ссылок. |
## Примечания

Указание resolver может потенциально привести к уязвимости. Используйте с осторожностью.
## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IParagraphCollection](../)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)