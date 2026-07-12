---
title: HtmlFormatter
second_title: Aspose.Slides für Android über Java API Referenz
description: Stellt eine HTML-Dateivorlage dar.
type: docs
url: /de/com.aspose.slides/htmlformatter/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Represents HTML file template.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Erstellt und gibt einen HTML-Formatter für eine einfache Dokumentansicht zurück, die aus einer Folge von Folien besteht, die untereinander angeordnet sind. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Erstellt und gibt einen HTML-Formatter für eine einfache Diashow-HTML zurück, die die Folien nacheinander anzeigt. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Erstellt und gibt einen HTML-Formatter für eine benutzerdefinierte, callback-gesteuerte HTML-Generierung zurück. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Erstellt und gibt einen HTML-Formatter für eine einfache Dokumentansicht zurück, die aus einer Folge von Folien besteht, die untereinander angeordnet sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| css | java.lang.String | Gibt das CSS für diese Datei an. |
| showSlideTitle | boolean | Fügt den Folientitel hinzu, falls einer über dem Folienbild vorhanden ist. |

**Rückgabe:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

Erstellt und gibt einen HTML-Formatter für eine einfache Diashow-HTML zurück, die die Folien nacheinander anzeigt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| css | java.lang.String | Gibt die URL der verwendeten CCS-Datei an. |
| showSlideTitle | boolean | Fügt den Folientitel hinzu, falls einer über dem Folienbild vorhanden ist. |

**Rückgabe:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

Erstellt und gibt einen HTML-Formatter für eine benutzerdefinierte, callback-gesteuerte HTML-Generierung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Callback-Schnittstelle, die die HTML-Dateierstellung steuert. |

**Rückgabe:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - The [HtmlFormatter](../../com.aspose.slides/htmlformatter) object.