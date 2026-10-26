---
title: HtmlFormatter
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje šablonu HTML souboru.
type: docs
url: /cs/com.aspose.slides/htmlformatter/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Represents HTML file template.
## Metody

| Metoda | Popis |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Creates and returns HTML formatter for a simple document view which consists of sequences of slides one below another. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Creates and returns HTML formatter for a simple slide show html which shows slides one after another. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Creates and returns HTML formatter for custom callback-driven html generation. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```


Vytvoří a vrátí HTML formátovač pro jednoduchý dokumentový náhled, který se skládá ze sekvencí snímků jeden pod druhým.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| css | java.lang.String | Určuje CSS pro tento soubor. |
| showSlideTitle | boolean | Přidá název snímku, pokud je nad obrázkem snímku. |

**Návratová hodnota:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Objekt [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```


Vytvoří a vrátí HTML formátovač pro jednoduchý slideshow html, který zobrazuje snímky jeden po druhém.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| css | java.lang.String | Určuje URL souboru CCS, který se používá. |
| showSlideTitle | boolean | Přidá název snímku, pokud je nad obrázkem snímku. |

**Návratová hodnota:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Objekt [HtmlFormatter](../../com.aspose.slides/htmlformatter).

### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```


Vytvoří a vrátí HTML formátovač pro generování html řízené vlastním zpětným voláním.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Rozhraní zpětného volání, které řídí generování html souboru. |

**Návratová hodnota:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Objekt [HtmlFormatter](../../com.aspose.slides/htmlformatter).