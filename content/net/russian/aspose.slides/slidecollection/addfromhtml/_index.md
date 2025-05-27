---
title: AddFromHtml
second_title: Aspose.Slides для .NET Справочник по API
description: Создает слайды из HTML текста и добавляет их в конец коллекции.
type: docs
weight: 70
url: /ru/aspose.slides/slidecollection/addfromhtml/
---

## AddFromHtml(string, IExternalResourceResolver, string) {#addfromhtml_5}

Создает слайды из HTML текста и добавляет их в конец коллекции.

```csharp
public ISlide[] AddFromHtml(string htmlText, IExternalResourceResolver resolver, string uri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlText | String | HTML для добавления. |
| resolver | IExternalResourceResolver | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут проигнорированы. |
| uri | String | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Возвращаемое значение

Добавленные слайды.

### См. также

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(string) {#addfromhtml_4}

Создает слайды из HTML текста и добавляет их в конец коллекции.

```csharp
public ISlide[] AddFromHtml(string htmlText)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlText | String | HTML для добавления. |

### Возвращаемое значение

Добавленные слайды

### См. также

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader, IExternalResourceResolver, string) {#addfromhtml_3}

Создает слайды из HTML текста и добавляет их в конец коллекции.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader, IExternalResourceResolver resolver, string uri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlReader | TextReader | Объект TextReader, который будет использован в качестве источника файла HTML. |
| resolver | IExternalResourceResolver | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут проигнорированы. |
| uri | String | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Возвращаемое значение

Добавленные слайды.

### См. также

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(TextReader) {#addfromhtml_2}

Создает слайды из HTML текста и добавляет их в конец коллекции.

```csharp
public ISlide[] AddFromHtml(TextReader htmlReader)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlReader | TextReader | Объект TextReader, который будет использован в качестве источника файла HTML. |

### Возвращаемое значение

Добавленные слайды

### См. также

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream, IExternalResourceResolver, string) {#addfromhtml_1}

Создает слайды из HTML текста и добавляет их в конец коллекции.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream, IExternalResourceResolver resolver, string uri)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlStream | Stream | Объект Stream, который будет использован в качестве источника файла HTML. |
| resolver | IExternalResourceResolver | Объект обратного вызова, используемый для получения внешних объектов. Если этот параметр равен null, все внешние объекты будут проигнорированы. |
| uri | String | URI указанного HTML. Используется для разрешения относительных ссылок. |

### Возвращаемое значение

Добавленные слайды.

### См. также

* interface [ISlide](../../islide)
* interface [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

---

## AddFromHtml(Stream) {#addfromhtml}

Создает слайды из HTML текста и добавляет их в конец коллекции.

```csharp
public ISlide[] AddFromHtml(Stream htmlStream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| htmlStream | Stream | Объект Stream, который будет использован в качестве источника файла HTML. |

### Возвращаемое значение

Добавленные слайды

### Примеры

```csharp
[C#]
// Создайте экземпляр класса Presentation.
using (var presentation = new Presentation())
{
    using (var htmlStream = File.OpenRead("page.html"))
    {
        // Вызовите метод AddFromHtml и передайте файл HTML.
        presentation.Slides.AddFromHtml(htmlStream);
    }
    // Используйте метод Save, чтобы сохранить файл как документ PowerPoint.
    presentation.Save("MyPresentation.pptx", SaveFormat.Pptx);
}
```

### См. также

* interface [ISlide](../../islide)
* class [SlideCollection](../../slidecollection)
* namespace [Aspose.Slides](../../slidecollection)
* assembly [Aspose.Slides](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->