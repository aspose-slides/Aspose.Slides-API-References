---
title: AddFromHtml()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт слайды из HTML-текста и добавляет их в конец коллекции.
type: docs
weight: 144
url: /ru/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Создает слайды из HTML-текста и добавляет их в конец коллекции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML для добавления. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорированы. |
| uri | [System::String](../../../system/string/) | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Return Value

Добавленные слайды.

## ISlideCollection::AddFromHtml(System::String) method

Создает слайды из HTML-текста и добавляет их в конец коллекции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | HTML для добавления. |

### Return Value

Добавленные слайды

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Создает слайды из HTML-текста и добавляет их в конец коллекции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Объект TextReader, который будет использоваться как источник HTML-файла. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорированы. |
| uri | [System::String](../../../system/string/) | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Return Value

Добавленные слайды.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) method

Создает слайды из HTML-текста и добавляет их в конец коллекции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Объект TextReader, который будет использоваться как источник HTML-файла. |

### Return Value

Добавленные слайды

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method

Создает слайды из HTML-текста и добавляет их в конец коллекции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Объект Stream, который будет использоваться как источник HTML-файла. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорированы. |
| uri | [System::String](../../../system/string/) | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Return Value

Добавленные слайды.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) method

Создает слайды из HTML-текста и добавляет их в конец коллекции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Arguments

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Объект Stream, который будет использоваться как источник HTML-файла. |

### Return Value

Добавленные слайды

## See Also

* Тип [ArrayPtr](../../../system/arrayptr/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [ISlide](../../islide/)
* Класс [String](../../../system/string/)
* Класс [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Класс [ISlideCollection](../)
* Класс [TextReader](../../../system.io/textreader/)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)