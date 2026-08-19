---
title: HtmlFormatter
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje šablonu souboru HTML.
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

Reprezentuje šablonu souboru HTML.
## Metody

| Metoda | Popis |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Vytvoří a vrátí HTML formátovač pro jednoduchý dokumentový pohled, který se skládá ze sekvence snímků jeden pod druhým. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Vytvoří a vrátí HTML formátovač pro jednoduchou slideshow HTML, která zobrazuje snímky po sobě. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Vytvoří a vrátí HTML formátovač pro vlastní generování HTML řízené zpětným voláním. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Vytvoří a vrátí HTML formátovač pro jednoduchý dokumentový pohled, který se skládá ze sekvence snímků jeden pod druhým.

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

Vytvoří a vrátí HTML formátovač pro jednoduchou slideshow HTML, která zobrazuje snímky po sobě.

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

Vytvoří a vrátí HTML formátovač pro vlastní generování HTML řízené zpětným voláním.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Rozhraní zpětného volání, které řídí generování souboru HTML. |

**Návratová hodnota:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - Objekt [HtmlFormatter](../../com.aspose.slides/htmlformatter).