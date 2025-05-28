---
title: InsertFromHtml
second_title: Aspose.Sildes для .NET API Reference
description: Создает слайды из HTML-текста и вставляет их в коллекцию по указанной позиции.
type: docs
weight: 140
url: /ru/aspose.slides/slidecollection/insertfromhtml/
---

## InsertFromHtml(int, string, IExternalResourceResolver, string) {#insertfromhtml_7}

Создает слайды из HTML-текста и вставляет их в коллекцию по указанной позиции.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Позиция для вставки. |
| htmlText | String | Html для добавления. |
| resolver | IExternalResourceResolver | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| uri | String | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Возвращаемое значение

Добавленные слайды.

### Смотрите также

* интерфейс [ISlide](../../islide)
* интерфейс [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, IExternalResourceResolver, string, bool) {#insertfromhtml_8}

Создает слайды из HTML-текста и вставляет их в коллекцию по указанной позиции.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Позиция для вставки. |
| htmlText | String | Html для добавления. |
| resolver | IExternalResourceResolver | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| uri | String | URI указанного HTML. Используется для разрешения относительных ссылок. |
| useSlideWithIndexAsStart | Boolean | Этот флаг определяет, как начать вставку: с нового слайда или слайда с указанным индексом. Если **true**, вставка данных начнется с пустого места на слайде с указанным индексом. Если **false**, данные будут добавлены к созданным слайдам. |

### Возвращаемое значение

Добавленные слайды.

### Смотрите также

* интерфейс [ISlide](../../islide)
* интерфейс [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string) {#insertfromhtml_6}

Создает слайды из HTML-текста и вставляет их в коллекцию по указанной позиции.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Позиция для вставки. |
| htmlText | String | Html для добавления. |

### Возвращаемое значение

Добавленные слайды

### Смотрите также

* интерфейс [ISlide](../../islide)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## InsertFromHtml(int, string, bool) {#insertfromhtml_9}

Создает слайды из HTML-текста и вставляет их в коллекцию по указанной позиции.

```csharp
public ISlide[] InsertFromHtml(int index, string htmlText, bool useSlideWithIndexAsStart)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Позиция для вставки. |
| htmlText | String | Html для добавления. |
| useSlideWithIndexAsStart | Boolean | Этот флаг определяет, как начать вставку: с нового слайда или слайда с указанным индексом. Если **true**, вставка данных начнется с пустого места на слайде с указанным индексом. Если **false**, данные будут добавлены к созданным слайдам. |

### Возвращаемое значение

Добавленные слайды

### Смотрите также

* интерфейс [ISlide](../../islide)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader, IExternalResourceResolver, string) {#insertfromhtml_5}

Создает слайды из HTML-текста и вставляет их в коллекцию по указанной позиции.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader, 
    IExternalResourceResolver resolver, string uri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Позиция для вставки. |
| htmlReader | TextReader | Объект TextReader, который будет использоваться в качестве источника HTML-файла. |
| resolver | IExternalResourceResolver | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| uri | String | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Возвращаемое значение

Добавленные слайды.

### Смотрите также

* интерфейс [ISlide](../../islide)
* интерфейс [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## InsertFromHtml(int, TextReader) {#insertfromhtml_4}

Создает слайды из HTML-текста и вставляет их в коллекцию по указанной позиции.

```csharp
public ISlide[] InsertFromHtml(int index, TextReader htmlReader)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Позиция для вставки. |
| htmlReader | TextReader | Объект TextReader, который будет использоваться в качестве источника HTML-файла. |

### Возвращаемое значение

Добавленные слайды

### Смотрите также

* интерфейс [ISlide](../../islide)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string) {#insertfromhtml_1}

Создает слайды из HTML-текста и вставляет их в коллекцию по указанной позиции.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Позиция для вставки. |
| htmlStream | Stream | Объект Stream, который будет использоваться в качестве источника HTML-файла. |
| resolver | IExternalResourceResolver | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| uri | String | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Возвращаемое значение

Добавленные слайды.

### Смотрите также

* интерфейс [ISlide](../../islide)
* интерфейс [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, IExternalResourceResolver, string, bool) {#insertfromhtml_2}

Создает слайды из HTML-текста и вставляет их в коллекцию по указанной позиции.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, IExternalResourceResolver resolver, 
    string uri, bool useSlideWithIndexAsStart)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Позиция для вставки. |
| htmlStream | Stream | Объект Stream, который будет использоваться в качестве источника HTML-файла. |
| resolver | IExternalResourceResolver | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут игнорироваться. |
| uri | String | URI указанного HTML. Используется для разрешения относительных ссылок. |
| useSlideWithIndexAsStart | Boolean | Этот флаг определяет, как начать вставку: с нового слайда или слайда с указанным индексом. Если **true**, вставка данных начнется с пустого места на слайде с указанным индексом. Если **false**, данные будут добавлены к созданным слайдам. |

### Возвращаемое значение

Добавленные слайды.

### Смотрите также

* интерфейс [ISlide](../../islide)
* интерфейс [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream) {#insertfromhtml}

Создает слайды из HTML-текста и вставляет их в коллекцию по указанной позиции.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Позиция для вставки. |
| htmlStream | Stream | Объект Stream, который будет использоваться в качестве источника HTML-файла. |

### Возвращаемое значение

Добавленные слайды

### Смотрите также

* интерфейс [ISlide](../../islide)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

---

## InsertFromHtml(int, Stream, bool) {#insertfromhtml_3}

Создает слайды из HTML-текста и вставляет их в коллекцию по указанной позиции.

```csharp
public ISlide[] InsertFromHtml(int index, Stream htmlStream, bool useSlideWithIndexAsStart)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| index | Int32 | Позиция для вставки. |
| htmlStream | Stream | Объект Stream, который будет использоваться в качестве источника HTML-файла. |
| useSlideWithIndexAsStart | Boolean | Этот флаг определяет, как начать вставку: с нового слайда или слайда с указанным индексом. Если **true**, вставка данных начнется с пустого места на слайде с указанным индексом. Если **false**, данные будут добавлены к созданным слайдам. |

### Возвращаемое значение

Добавленные слайды

### Смотрите также

* интерфейс [ISlide](../../islide)
* класс [SlideCollection](../../slidecollection)
* пространство имен [Aspose.Slides](../../slidecollection)
* сборка [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->