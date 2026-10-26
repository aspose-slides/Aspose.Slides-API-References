---
title: InsertFromHtml()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.
type: docs
weight: 209
url: /ru/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) метод


Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlText | [System::String](../../../system/string/) | HTML для добавления. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект-callback, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут проигнорированы. |
| uri | [System::String](../../../system/string/) | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Возвращаемое значение

Добавленные слайды.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) метод


Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlText | [System::String](../../../system/string/) | HTML для добавления. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект-callback, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут проигнорированы. |
| uri | [System::String](../../../system/string/) | URI указанного HTML. Используется для разрешения относительных ссылок. |
| useSlideWithIndexAsStart | **bool** | Этот флаг определяет, как начать вставку: с нового слайда или со слайда с указанным индексом. Если **true**, вставка данных начнётся с пустого пространства на слайде с указанным индексом. Если **false**, данные будут добавлены к созданным слайдам. |

### Возвращаемое значение

Добавленные слайды.

## SlideCollection::InsertFromHtml(int32_t, System::String) метод


Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlText | [System::String](../../../system/string/) | HTML для добавления. |

### Возвращаемое значение

Добавленные слайды.

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) метод


Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlText | [System::String](../../../system/string/) | HTML для добавления. |
| useSlideWithIndexAsStart | **bool** | Этот флаг определяет, как начать вставку: с нового слайда или со слайда с указанным индексом. Если **true**, вставка данных начнётся с пустого пространства на слайде с указанным индексом. Если **false**, данные будут добавлены к созданным слайдам. |

### Возвращаемое значение

Добавленные слайды.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) метод


Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Объект TextReader, который будет использоваться как источник HTML-файла. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект-callback, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут проигнорированы. |
| uri | [System::String](../../../system/string/) | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Возвращаемое значение

Добавленные слайды.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) метод


Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Объект TextReader, который будет использоваться как источник HTML-файла. |

### Возвращаемое значение

Добавленные слайды.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) метод


Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Объект Stream, который будет использоваться как источник HTML-файла. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект-callback, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут проигнорированы. |
| uri | [System::String](../../../system/string/) | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Возвращаемое значение

Добавленные слайды.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) метод


Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Объект Stream, который будет использоваться как источник HTML-файла. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Объект-callback, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут проигнорированы. |
| uri | [System::String](../../../system/string/) | URI указанного HTML. Используется для разрешения относительных ссылок. |
| useSlideWithIndexAsStart | **bool** | Этот флаг определяет, как начать вставку: с нового слайда или со слайда с указанным индексом. Если **true**, вставка данных начнётся с пустого пространства на слайде с указанным индексом. Если **false**, данные будут добавлены к созданным слайдам. |

### Возвращаемое значение

Добавленные слайды.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) метод


Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Объект Stream, который будет использоваться как источник HTML-файла. |

### Возвращаемое значение

Добавленные слайды.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) метод


Создаёт слайды из HTML-текста и вставляет их в коллекцию в указанной позиции.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | **int32_t** | Позиция для вставки. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Объект Stream, который будет использоваться как источник HTML-файла. |
| useSlideWithIndexAsStart | **bool** | Этот флаг определяет, как начать вставку: с нового слайда или со слайда с указанным индексом. Если **true**, вставка данных начнётся с пустого пространства на слайде с указанным индексом. Если **false**, данные будут добавлены к созданным слайдам. |

### Возвращаемое значение

Добавленные слайды.

## См. также

* Тип-определение [ArrayPtr](../../../system/arrayptr/)
* Тип-определение [SharedPtr](../../../system/sharedptr/)
* Класс [ISlide](../../islide/)
* Класс [String](../../../system/string/)
* Класс [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Класс [SlideCollection](../)
* Класс [TextReader](../../../system.io/textreader/)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)