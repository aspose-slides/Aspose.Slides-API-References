---
title: HtmlFormatter
second_title: Aspose.Slides para Android mediante la referencia de la API Java
description: Representa la plantilla de archivo HTML.
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

Representa la plantilla de archivo HTML.
## Métodos

| Método | Descripción |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Crea y devuelve un formateador HTML para una vista de documento simple que consiste en secuencias de diapositivas una debajo de otra. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Crea y devuelve un formateador HTML para una presentación de diapositivas simple que muestra las diapositivas una tras otra. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Crea y devuelve un formateador HTML para una generación de html impulsada por devolución de llamada personalizada. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Crea y devuelve un formateador HTML para una vista de documento simple que consiste en secuencias de diapositivas una debajo de otra.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| css | java.lang.String | Especifica CSS para este archivo. |
| showSlideTitle | boolean | Agregar el título de la diapositiva si hay uno encima de la imagen de la diapositiva. |

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
| showSlideTitle | boolean | Agregar el título de la diapositiva si hay uno encima de la imagen de la diapositiva. |

**Devuelve:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - El objeto [HtmlFormatter](../../com.aspose.slides/htmlformatter).
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

Crea y devuelve un formateador HTML para una generación de html impulsada por devolución de llamada personalizada.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Interfaz de devolución de llamada que controla la generación del archivo html. |

**Devuelve:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - El objeto [HtmlFormatter](../../com.aspose.slides/htmlformatter).