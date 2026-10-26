---
title: HtmlFormatter
second_title: Referencia de la API de Aspose.Slides para Java
description: Representa una plantilla de archivo HTML.
type: docs
url: /es/com.aspose.slides/htmlformatter/
---
**Herencia:**
java.lang.Object

**Todas las interfaces implementadas:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Representa una plantilla de archivo HTML.
## Métodos

| Método | Descripción |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Crea y devuelve un formateador HTML para una vista de documento simple que consiste en secuencias de diapositivas una debajo de otra. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Crea y devuelve un formateador HTML para una presentación de diapositivas simple que muestra las diapositivas una tras otra. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Crea y devuelve un formateador HTML para la generación de HTML personalizada basada en devoluciones de llamada. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```


Crea y devuelve un formateador HTML para una vista de documento simple que consiste en secuencias de diapositivas una debajo de otra.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| css | java.lang.String | Especifica CSS para este archivo. |
| showSlideTitle | boolean | Añade el título de la diapositiva si hay uno sobre la imagen de la diapositiva. |

**Devuelve:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - El objeto [HtmlFormatter](../../com.aspose.slides/htmlformatter).
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```


Crea y devuelve un formateador HTML para una presentación de diapositivas simple que muestra las diapositivas una tras otra.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| css | java.lang.String | Especifica la URL del archivo CCS utilizado. |
| showSlideTitle | boolean | Añade el título de la diapositiva si hay uno sobre la imagen de la diapositiva. |

**Devuelve:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - El objeto [HtmlFormatter](../../com.aspose.slides/htmlformatter).
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```


Crea y devuelve un formateador HTML para la generación de HTML personalizada basada en devoluciones de llamada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Interfaz de devolución de llamada que controla la generación del archivo html. |

**Devuelve:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - El objeto [HtmlFormatter](../../com.aspose.slides/htmlformatter).