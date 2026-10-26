---
title: HtmlFormatter
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta un modello di file HTML.
type: docs
url: /it/com.aspose.slides/htmlformatter/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
```
public final class HtmlFormatter implements IHtmlFormatter
```

Rappresenta un modello di file HTML.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createDocumentFormatter(String css, boolean showSlideTitle)](#createDocumentFormatter-java.lang.String-boolean-) | Crea e restituisce un formattatore HTML per una semplice vista documento che consiste in sequenze di diapositive una sotto l'altra. |
| [createSlideShowFormatter(String css, boolean showSlideTitle)](#createSlideShowFormatter-java.lang.String-boolean-) | Crea e restituisce un formattatore HTML per una semplice presentazione diapositive che mostra le diapositive una dopo l'altra. |
| [createCustomFormatter(IHtmlFormattingController formattingController)](#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-) | Crea e restituisce un formattatore HTML per la generazione di HTML personalizzata guidata da callback. |
### createDocumentFormatter(String css, boolean showSlideTitle) {#createDocumentFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createDocumentFormatter(String css, boolean showSlideTitle)
```

Crea e restituisce un formattatore HTML per una semplice vista documento che consiste in sequenze di diapositive una sotto l'altra.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| css | java.lang.String | Specifica il CSS per questo file. |
| showSlideTitle | boolean | Aggiunge il titolo della diapositiva se presente sopra l'immagine della diapositiva. |

**Restituisce:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - L'[HtmlFormatter](../../com.aspose.slides/htmlformatter) oggetto.
### createSlideShowFormatter(String css, boolean showSlideTitle) {#createSlideShowFormatter-java.lang.String-boolean-}
```
public static HtmlFormatter createSlideShowFormatter(String css, boolean showSlideTitle)
```

Crea e restituisce un formattatore HTML per una semplice presentazione diapositive che mostra le diapositive una dopo l'altra.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| css | java.lang.String | Specifica l'URL del file CSS utilizzato. |
| showSlideTitle | boolean | Aggiunge il titolo della diapositiva se presente sopra l'immagine della diapositiva. |

**Restituisce:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - L'[HtmlFormatter](../../com.aspose.slides/htmlformatter) oggetto.
### createCustomFormatter(IHtmlFormattingController formattingController) {#createCustomFormatter-com.aspose.slides.IHtmlFormattingController-}
```
public static HtmlFormatter createCustomFormatter(IHtmlFormattingController formattingController)
```

Crea e restituisce un formattatore HTML per la generazione di HTML personalizzata guidata da callback.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formattingController | [IHtmlFormattingController](../../com.aspose.slides/ihtmlformattingcontroller) | Interfaccia di callback che controlla la generazione del file HTML. |

**Restituisce:**
[HtmlFormatter](../../com.aspose.slides/htmlformatter) - L'[HtmlFormatter](../../com.aspose.slides/htmlformatter) oggetto.