---
title: SpreadsheetOptions
second_title: Aspose.Slides für Android über Java API-Referenz
description: Stellt Optionen dar, die verwendet werden können, um zusätzliches Tabellenkalkulationsverhalten anzugeben.
type: docs
url: /de/com.aspose.slides/spreadsheetoptions/
---
**Vererbung:**
java.lang.Object

**Alle implementierten Schnittstellen:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Stellt Optionen dar, die verwendet werden können, um zusätzliches Tabellenkalkulationsverhalten anzugeben.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Initialisiert eine neue Instanz der [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Liest oder setzt bevorzugte Kulturinformationen zur Berechnung einiger Funktionen, die für die Verwendung mit Sprachen gedacht sind, die das Double-Byte-Zeichensatz (DBCS) verwenden. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Liest oder setzt bevorzugte Kulturinformationen zur Berechnung einiger Funktionen, die für die Verwendung mit Sprachen gedacht sind, die das Double-Byte-Zeichensatz (DBCS) verwenden. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und sie nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und sie nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

Initialisiert eine neue Instanz der [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) Klasse.

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

Liest oder setzt bevorzugte Kulturinformationen zur Berechnung einiger Funktionen, die für die Verwendung mit Sprachen gedacht sind, die das Double-Byte-Zeichensatz (DBCS) verwenden.

**Rückgabe:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

Liest oder setzt bevorzugte Kulturinformationen zur Berechnung einiger Funktionen, die für die Verwendung mit Sprachen gedacht sind, die das Double-Byte-Zeichensatz (DBCS) verwenden.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und sie nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Rückgabe:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public final void setRecoverWorkbookFromChartCache(boolean value)
```

Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und sie nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |