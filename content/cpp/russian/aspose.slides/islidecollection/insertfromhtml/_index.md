---
title: InsertFromHtml()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.
type: docs
weight: 157
url: /ru/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) метод

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlText | [System::String](../../../system/string/) | HTML для добавления. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект-обратный вызов, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| uri | [System::String](../../../system/string/) | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Возвращаемое значение

Добавленные слайды.

## ISlideCollection::InsertFromHtml(int32_t, System::String) метод

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlText | [System::String](../../../system/string/) | HTML для добавления. |

### Возвращаемое значение

Добавленные слайды

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) метод

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Объект TextReader, который будет использоваться как источник HTML-файла. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект-обратный вызов, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| uri | [System::String](../../../system/string/) | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Возвращаемое значение

Добавленные слайды.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) метод

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Объект TextReader, который будет использоваться как источник HTML-файла. |

### Возвращаемое значение

Добавленные слайды

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) метод

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Объект Stream, который будет использоваться как источник HTML-файла. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект-обратный вызов, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| uri | [System::String](../../../system/string/) | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Возвращаемое значение

Добавленные слайды.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) метод

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Объект Stream, который будет использоваться как источник HTML-файла. |

### Возвращаемое значение

Добавленные слайды

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) метод

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlText | [System::String](../../../system/string/) | HTML для добавления. |
| useSlideWithIndexAsStart | **bool** | Этот флаг определяет, как начинать вставку: с новой слайда или со слайда с указанным индексом. Если **true**, то вставка данных начнётся с пустого места на слайде с указанным индексом. Если **false**, данные будут добавлены в созданные слайды. |

### Возвращаемое значение

Добавленные слайды

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) метод

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlText | [System::String](../../../system/string/) | HTML для добавления. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект-обратный вызов, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| uri | [System::String](../../../system/string/) | URI указанного HTML. Используется для разрешения относительных ссылок. |
| useSlideWithIndexAsStart | **bool** | Этот флаг определяет, как начинать вставку: с новой слайда или со слайда с указанным индексом. Если **true**, то вставка данных начнётся с пустого места на слайде с указанным индексом. Если **false**, данные будут добавлены в созданные слайды. |

### Возвращаемое значение

Добавленные слайды.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) метод

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Объект Stream, который будет использоваться как источник HTML-файла. |
| useSlideWithIndexAsStart | **bool** | Этот флаг определяет, как начинать вставку: с новой слайда или со слайда с указанным индексом. Если **true**, то вставка данных начнётся с пустого места на слайде с указанным индексом. Если **false**, данные будут добавлены в созданные слайды. |

### Возвращаемое значение

Добавленные слайды

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) метод

Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Объект Stream, который будет использоваться как источник HTML-файла. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект-обратный вызов, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| uri | [System::String](../../../system/string/) | URI указанного HTML. Используется для разрешения относительных ссылок. |
| useSlideWithIndexAsStart | **bool** | Этот флаг определяет, как начинать вставку: с новой слайда или со слайда с указанным индексом. Если **true**, то вставка данных начнётся с пустого места на слайде с указанным индексом. Если **false**, данные будут добавлены в созданные слайды. |

### Возвращаемое значение

Добавленные слайды.

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [String](../../../system/string/)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Class [ISlideCollection](../)
* Class [TextReader](../../../system.io/textreader/)
* Class [Stream](../../../system.io/stream/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)