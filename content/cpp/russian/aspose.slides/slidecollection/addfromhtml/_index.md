---
title: AddFromHtml()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт слайды из HTML-текста и добавляет их в конец коллекции.
type: docs
weight: 196
url: /ru/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) метод

Создает слайды из HTML-текста и добавляет их в конец коллекции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html to add. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Возвращаемое значение

Added slides.

## SlideCollection::AddFromHtml(System::String) метод

Создает слайды из HTML-текста и добавляет их в конец коллекции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Html to add. |

### Возвращаемое значение

Added slides

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) метод

Создает слайды из HTML-текста и добавляет их в конец коллекции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader object which will be used as a source of a HTML file. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Возвращаемое значение

Added slides.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) метод

Создает слайды из HTML-текста и добавляет их в конец коллекции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | TextReader object which will be used as a source of a HTML file. |

### Возвращаемое значение

Added slides

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) метод

Создает слайды из HTML-текста и добавляет их в конец коллекции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream object which will be used as a source of a HTML file. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | A callback object used to fetch external objects. If this parameter is null all external objects will be ignored. |
| uri | [System::String](../../../system/string/) | An URI of the specified HTML. Used to resolve relative links. |

### Возвращаемое значение

Added slides.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) метод

Создает слайды из HTML-текста и добавляет их в конец коллекции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | A Stream object which will be used as a source of a HTML file. |

### Возвращаемое значение

Added slides

## Замечания

```cpp
// Создайте экземпляр класса Presentation.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // Вызовите метод AddFromHtml и передайте HTML-файл.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Используйте метод Save, чтобы сохранить файл как документ PowerPoint.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [ISlide](../../islide/)
* Класс [String](../../../system/string/)
* Класс [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Класс [SlideCollection](../)
* Класс [TextReader](../../../system.io/textreader/)
* Класс [Stream](../../../system.io/stream/)
* Пространство имен [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)