---
title: HtmlFormatter
second_title: Aspose.Slides для Android через справочник Java API
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
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Создаёт и возвращает HTML-форматировщик для простого представления документа, состоящего из последовательностей слайдов, расположенных один под другим. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Создаёт и возвращает HTML-форматировщик для простой презентации HTML, которая показывает слайды один за другим. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Создаёт и возвращает HTML-форматировщик для пользовательской генерации HTML на основе обратных вызовов. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Создаёт и возвращает HTML-форматировщик для простого представления документа, состоящего из последовательностей слайдов, расположенных один под другим.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| css | java.lang.String | Указывает CSS для данного файла. |
| showSlideTitle | boolean | Добавляет заголовок слайда, если он присутствует над изображением слайда. |

**Возвращаемое значение:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - объект [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

Создаёт и возвращает HTML-форматировщик для простой презентации HTML, которая показывает слайды один за другим.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| css | java.lang.String | Указывает URL используемого CSS-файла. |
| showSlideTitle | boolean | Добавляет заголовок слайда, если он присутствует над изображением слайда. |

**Возвращаемое значение:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - объект [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

Создаёт и возвращает HTML-форматировщик для пользовательской генерации HTML на основе обратных вызовов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Интерфейс обратного вызова, управляющий генерацией HTML-файла. |

**Возвращаемое значение:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - объект [HtmlFormatter](../../com.aspose.slides/htmlformatter).