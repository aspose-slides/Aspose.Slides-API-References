---
title: HtmlFormatter
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een HTML-bestandssjabloon voor.
type: docs
url: /nl/com.aspose.slides/htmlformatter/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Stelt een HTML-bestandssjabloon voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Maakt en retourneert een HTML-formatter voor een eenvoudige documentweergave die bestaat uit een reeks dia's onder elkaar. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Maakt en retourneert een HTML-formatter voor een eenvoudige diavoorstelling-html die dia's één voor één toont. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Maakt en retourneert een HTML-formatter voor aangepaste, callback-gedreven HTML-generatie. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Maakt en retourneert een HTML-formatter voor een eenvoudige documentweergave die bestaat uit een reeks dia's onder elkaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| css | java.lang.String | Specificeert CSS voor dit bestand. |
| showSlideTitle | boolean | Voegt de dia-titel toe als er één boven de dia-afbeelding staat. |

**Retourwaarde:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Het [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

Maakt en retourneert een HTML-formatter voor een eenvoudige diavoorstelling-html die dia's één voor één toont.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| css | java.lang.String | Specificeert URL van het gebruikte CCS-bestand. |
| showSlideTitle | boolean | Voegt de dia-titel toe als er één boven de dia-afbeelding staat. |

**Retourwaarde:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Het [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

Maakt en retourneert een HTML-formatter voor aangepaste, callback-gedreven HTML-generatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Callback-interface die de generatie van het HTML-bestand regelt. |

**Retourwaarde:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Het [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.