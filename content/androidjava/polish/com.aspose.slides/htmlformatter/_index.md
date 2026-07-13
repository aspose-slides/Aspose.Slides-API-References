---
title: HtmlFormatter
second_title: Aspose.Slides dla Androida – odniesienie do API Java
description: Reprezentuje szablon pliku HTML.
type: docs
url: /pl/com.aspose.slides/htmlformatter/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Reprezentuje szablon pliku HTML.
## Metody

| Metoda | Opis |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Tworzy i zwraca formatator HTML dla prostego widoku dokumentu, który składa się z kolejnych slajdów jeden pod drugim. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Tworzy i zwraca formatator HTML dla prostego pokazu slajdów w HTML, który wyświetla slajdy jeden po drugim. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Tworzy i zwraca formatator HTML dla niestandardowego generowania HTML sterowanego wywołaniami zwrotnymi. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```


Tworzy i zwraca formatator HTML dla prostego widoku dokumentu, który składa się z kolejnych slajdów jeden pod drugim.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| css | java.lang.String | Określa CSS dla tego pliku. |
| showSlideTitle | boolean | Dodaje tytuł slajdu, jeśli istnieje nad obrazem slajdu. |

**Zwraca:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Obiekt [HtmlFormatter](../../com.aspose.slides/htmlformatter).
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```


Tworzy i zwraca formatator HTML dla prostego pokazu slajdów w HTML, który wyświetla slajdy jeden po drugim.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| css | java.lang.String | Określa URL pliku CSS używanego. |
| showSlideTitle | boolean | Dodaje tytuł slajdu, jeśli istnieje nad obrazem slajdu. |

**Zwraca:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Obiekt [HtmlFormatter](../../com.aspose.slides/htmlformatter).
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```


Tworzy i zwraca formatator HTML dla niestandardowego generowania HTML sterowanego wywołaniami zwrotnymi.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Interfejs zwrotny, który kontroluje generowanie pliku html. |

**Zwraca:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Obiekt [HtmlFormatter](../../com.aspose.slides/htmlformatter).