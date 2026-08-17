---
title: IParagraphCollection
second_title: Справка API Aspose.Slides для Java
description: Представляет коллекцию абзацев.
type: docs
url: /ru/com.aspose.slides/iparagraphcollection/
---
**Все реализованные интерфейсы:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraphCollection extends System.Collections.Generic.IGenericEnumerable<IParagraph>, ISlideComponent
```

Представляет коллекцию абзацев.
## Методы

| Метод | Описание |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Получает элемент по заданному индексу. |
| [getCount()](#getCount--) | Получает количество фактически содержащихся в коллекции элементов. |
| [add(IParagraph value)](#add-com.aspose.slides.IParagraph-) | Добавляет Paragraph в конец коллекции. |
| [add(IParagraphCollection value)](#add-com.aspose.slides.IParagraphCollection-) | Добавляет содержимое ParagraphCollection в конец коллекции. |
| [insert(int index, IParagraph value)](#insert-int-com.aspose.slides.IParagraph-) | Вставляет Paragraph в коллекцию по заданному индексу. |
| [insert(int index, IParagraphCollection value)](#insert-int-com.aspose.slides.IParagraphCollection-) | Вставляет содержимое ParagraphCollection в коллекцию по заданному индексу. |
| [clear()](#clear--) | Удаляет все элементы из коллекции. |
| [removeAt(int index)](#removeAt-int-) | Удаляет элемент по заданному индексу в коллекции. |
| [remove(IParagraph item)](#remove-com.aspose.slides.IParagraph-) | Удаляет первое вхождение конкретного абзаца. |
| [addFromHtml(String text)](#addFromHtml-java.lang.String-) | Добавляет текст из указанной HTML-строки в коллекцию. |
| [addFromHtml(String text, IExternalResourceResolver resolver, String uri)](#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-) | Добавляет текст из указанной HTML-строки в коллекцию. |
| [exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)](#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-) | Преобразует указанные абзацы в HTML и возвращает его как объект String. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IParagraph get_Item(int index)
```

Получает элемент по заданному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int |  |

**Возвращаемое значение:**
[IParagraph](../../com.aspose.slides/iparagraph)
### getCount() {#getCount--}
```
public abstract int getCount()
```

Получает количество фактически содержащихся в коллекции элементов. Только для чтения int.

**Возвращаемое значение:**
int
### add(IParagraph value) {#add-com.aspose.slides.IParagraph-}
```
public abstract void add(IParagraph value)
```

Добавляет Paragraph в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph, который будет добавлен в конец коллекции. |
### add(IParagraphCollection value) {#add-com.aspose.slides.IParagraphCollection-}
```
public abstract int add(IParagraphCollection value)
```

Добавляет содержимое ParagraphCollection в конец коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | ParagraphCollection, который будет добавлен в конец коллекции. |

**Возвращаемое значение:**
int — индекс, по которому Paragraph был добавлен, или -1, если нечего добавлять.
### insert(int index, IParagraph value) {#insert-int-com.aspose.slides.IParagraph-}
```
public abstract void insert(int index, IParagraph value)
```

Вставляет Paragraph в коллекцию по заданному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой (начинающий с нуля) индекс, по которому должен быть вставлен Paragraph. |
| value | [IParagraph](../../com.aspose.slides/iparagraph) | Paragraph для вставки. |
### insert(int index, IParagraphCollection value) {#insert-int-com.aspose.slides.IParagraphCollection-}
```
public abstract void insert(int index, IParagraphCollection value)
```

Вставляет содержимое ParagraphCollection в коллекцию по заданному индексу.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой (начинающий с нуля) индекс, по которому должны быть вставлены абзацы. |
| value | [IParagraphCollection](../../com.aspose.slides/iparagraphcollection) | Абзацы для вставки. |
### clear() {#clear--}
```
public abstract void clear()
```

Удаляет все элементы из коллекции.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Удаляет элемент по заданному индексу в коллекции.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой (начинающий с нуля) индекс элемента, который нужно удалить. |
### remove(IParagraph item) {#remove-com.aspose.slides.IParagraph-}
```
public abstract boolean remove(IParagraph item)
```

Удаляет первое вхождение конкретного абзаца.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| item | [IParagraph](../../com.aspose.slides/iparagraph) | Абзац, который нужно удалить из коллекции. |

**Возвращаемое значение:**
boolean — true, если элемент был успешно удалён; иначе false.
### addFromHtml(String text) {#addFromHtml-java.lang.String-}
```
public abstract void addFromHtml(String text)
```

Добавляет текст из указанной HTML-строки в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | HTML-текст. |
### addFromHtml(String text, IExternalResourceResolver resolver, String uri) {#addFromHtml-java.lang.String-com.aspose.slides.IExternalResourceResolver-java.lang.String-}
```
public abstract void addFromHtml(String text, IExternalResourceResolver resolver, String uri)
```

Добавляет текст из указанной HTML-строки в коллекцию.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| text | java.lang.String | HTML-текст. |
| resolver | [IExternalResourceResolver](../../com.aspose.slides/iexternalresourceresolver) | Объект-коллбек Resolver, который разрешает URI и получает связанные объекты. |
| uri | java.lang.String | URI для добавления HTML-документа. Используется для разрешения относительных ссылок.

--------------------

Указание resolver может потенциально привести к уязвимости. Используйте с осторожностью. |
### exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options) {#exportToHtml-int-int-com.aspose.slides.ITextToHtmlConversionOptions-}
```
public abstract String exportToHtml(int firstParagraphIndex, int paragraphsCount, ITextToHtmlConversionOptions options)
```

Преобразует указанные абзацы в HTML и возвращает его как объект String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| firstParagraphIndex | int | Индекс первого абзаца int |
| paragraphsCount | int | Количество абзацев int |
| options | [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) | Параметры конвертации [ITextToHtmlConversionOptions](../../com.aspose.slides/itexttohtmlconversionoptions) |

**Возвращаемое значение:**
java.lang.String — Сгенерированный HTML.