---
title: HtmlFormatter
second_title: Aspose.Slides für Java API-Referenz
description: Stellt eine HTML-Dateivorlage dar.
type: docs
url: /de/com.aspose.slides/htmlformatter/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Stellt eine HTML-Dateivorlage dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Erstellt und gibt einen HTML-Formatter für eine einfache Dokumentenansicht zurück, die aus einer Reihe von Folien besteht, die untereinander angeordnet sind. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Erstellt und gibt einen HTML-Formatter für ein einfaches Slide-Show-HTML zurück, das Folien nacheinander anzeigt. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Erstellt und gibt einen HTML-Formatter für eine benutzerdefinierte, callback-gesteuerte HTML-Generierung zurück. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Erstellt und gibt einen HTML-Formatter für eine einfache Dokumentenansicht zurück, die aus einer Reihe von Folien besteht, die untereinander angeordnet sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| css | java.lang.String | Legt das CSS für diese Datei fest. |
| showSlideTitle | boolean | Fügt den Folientitel hinzu, falls einer über dem Folienbild vorhanden ist. |

**Rückgabewert:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) – Das [HtmlFormatter](../../com.aspose.slides/htmlformatter)-Objekt.
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

Erstellt und gibt einen HTML-Formatter für ein einfaches Slide-Show-HTML zurück, das Folien nacheinander anzeigt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| css | java.lang.String | Gibt die URL der verwendeten CSS-Datei an. |
| showSlideTitle | boolean | Fügt den Folientitel hinzu, falls einer über dem Folienbild vorhanden ist. |

**Rückgabewert:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) – Das [HtmlFormatter](../../com.aspose.slides/htmlformatter)-Objekt.
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

Erstellt und gibt einen HTML-Formatter für eine benutzerdefinierte, callback-gesteuerte HTML-Generierung zurück.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Callback-Schnittstelle, die die HTML-Dateigerstellung steuert. |

**Rückgabewert:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) – Das [HtmlFormatter](../../com.aspose.slides/htmlformatter)-Objekt.