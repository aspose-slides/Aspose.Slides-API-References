---
title: HtmlFormatter
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een HTML-sjabloon voor.
type: docs
url: /nl/com.aspose.slides/htmlformatter/
---
**Overerving:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Stelt een HTML-sjabloon voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Maakt een HTML-formatter aan en retourneert deze voor een eenvoudige documentweergave die bestaat uit opeenvolgende dia's onder elkaar. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Maakt een HTML-formatter aan en retourneert deze voor een eenvoudige diavoorstelling-html die dia's één voor één weergeeft. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Maakt een HTML-formatter aan en retourneert deze voor aangepaste, callback-gestuurde HTML-generatie. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Maakt een HTML-formatter aan en retourneert deze voor een eenvoudige documentweergave die bestaat uit opeenvolgende dia's onder elkaar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| css | java.lang.String | Specificeert CSS voor dit bestand. |
| showSlideTitle | boolean | Voeg de titel van de dia toe als er één boven de dia-afbeelding staat. |

**Retourwaarde:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Het [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

Maakt een HTML-formatter aan en retourneert deze voor een eenvoudige diavoorstelling-html die dia's één voor één weergeeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| css | java.lang.String | Specificeert de URL van het gebruikte CCS-bestand. |
| showSlideTitle | boolean | Voeg de titel van de dia toe als er één boven de dia-afbeelding staat. |

**Retourwaarde:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Het [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

Maakt een HTML-formatter aan en retourneert deze voor aangepaste, callback-gestuurde HTML-generatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Callback-interface die de HTML-bestandsgeneratie regelt. |

**Retourwaarde:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Het [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.