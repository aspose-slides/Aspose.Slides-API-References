---
title: HtmlFormatter
second_title: Aspose.Slides för Java API-referens
description: Representerar HTML-filmall.
type: docs
url: /sv/com.aspose.slides/htmlformatter/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Representerar HTML-filmall.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Skapar och returnerar en HTML-formaterare för en enkel dokumentvy som består av sekvenser av bilder staplade under varandra. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Skapar och returnerar en HTML-formaterare för ett enkelt bildspels-HTML som visar bilder en efter en. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Skapar och returnerar en HTML-formaterare för anpassad, återanropsstyrd HTML-generering. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```


Skapar och returnerar en HTML-formaterare för en enkel dokumentvy som består av sekvenser av bilder staplade under varandra.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| css | java.lang.String | Anger CSS för den här filen. |
| showSlideTitle | boolean | Lägg till bildtitel om det finns en ovanför bild på sliden. |

**Returnerar:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Objektet [HtmlFormatter](../../com.aspose.slides/htmlformatter).
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```


Skapar och returnerar en HTML-formaterare för ett enkelt bildspels-HTML som visar bilder en efter en.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| css | java.lang.String | Anger URL för den använda CCS-filen. |
| showSlideTitle | boolean | Lägg till bildtitel om det finns en ovanför bild på sliden. |

**Returnerar:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Objektet [HtmlFormatter](../../com.aspose.slides/htmlformatter).
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```


Skapar och returnerar en HTML-formaterare för anpassad, återanropsstyrd HTML-generering.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Återanropsgränssnitt som kontrollerar HTML-filgenerering. |

**Returnerar:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Objektet [HtmlFormatter](../../com.aspose.slides/htmlformatter).