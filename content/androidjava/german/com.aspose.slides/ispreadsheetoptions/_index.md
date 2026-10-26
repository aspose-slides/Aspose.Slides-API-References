---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Stellt Optionen dar, die verwendet werden können, um das Verhalten zusätzlicher Tabellenkalkulationen zu spezifizieren.
type: docs
url: /de/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Stellt Optionen dar, die verwendet werden können, um das Verhalten zusätzlicher Tabellenkalkulationen zu spezifizieren.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Liest oder legt bevorzugte Kulturinformationen für die Berechnung einiger Funktionen fest, die für Sprachen mit doppeltem Byte-Zeichensatz (DBCS) vorgesehen sind. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Liest oder legt bevorzugte Kulturinformationen für die Berechnung einiger Funktionen fest, die für Sprachen mit doppeltem Byte-Zeichensatz (DBCS) vorgesehen sind. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


Liest oder legt bevorzugte Kulturinformationen für die Berechnung einiger Funktionen fest, die für Sprachen mit doppeltem Byte-Zeichensatz (DBCS) vorgesehen sind.

**Rückgabewert:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


Liest oder legt bevorzugte Kulturinformationen für die Berechnung einiger Funktionen fest, die für Sprachen mit doppeltem Byte-Zeichensatz (DBCS) vorgesehen sind.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt.

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

**Rückgabewert:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt.

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