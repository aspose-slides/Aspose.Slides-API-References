---
title: HtmlFormatter
second_title: Aspose.Slides для Java: справочник API
description: Представляет шаблон HTML-файла.
type: docs
url: /ru/com.aspose.slides/htmlformatter/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Представляет шаблон HTML-файла.
## Методы

| Метод | Описание |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Создает и возвращает HTML-форматтер для простого представления документа, состоящего из последовательности слайдов один под другим. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Создает и возвращает HTML-форматтер для простого слайд-шоу, который отображает слайды один за другим. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Создает и возвращает HTML-форматтер для пользовательской генерации HTML с помощью обратных вызовов. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Создает и возвращает HTML-форматтер для простого представления документа, состоящего из последовательности слайдов один под другим.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| css | java.lang.String | Указывает CSS для данного файла. |
| showSlideTitle | boolean | Добавить заголовок слайда, если он присутствует над изображением слайда. |

**Возвращаемое значение:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Объект [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

Создает и возвращает HTML-форматтер для простого слайд-шоу, который отображает слайды один за другим.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| css | java.lang.String | Указывает URL используемого файла CCS. |
| showSlideTitle | boolean | Добавить заголовок слайда, если он присутствует над изображением слайда. |

**Возвращаемое значение:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Объект [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

Создает и возвращает HTML-форматтер для пользовательской генерации HTML с помощью обратных вызовов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Интерфейс обратного вызова, управляющий генерацией HTML-файла. |

**Возвращаемое значение:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Объект [HtmlFormatter](../../com.aspose.slides/htmlformatter).