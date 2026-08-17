---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Java API Reference
description: Stellt Optionen dar, die verwendet werden können, um zusätzliches Tabellenverhalten anzugeben.
type: docs
url: /de/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Stellt Optionen dar, die verwendet werden können, um zusätzliches Tabellenverhalten anzugeben.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Liefert oder legt die bevorzugte Kulturinformation für die Berechnung einiger Funktionen fest, die für Sprachen mit doppelbytezeichensatz (DBCS) vorgesehen sind. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Liefert oder legt die bevorzugte Kulturinformation für die Berechnung einiger Funktionen fest, die für Sprachen mit doppelbytezeichensatz (DBCS) vorgesehen sind. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Wenn die Datenquelle für das Diagramm eine externe Arbeitsmappe ist und nicht verfügbar ist, wird sie aus dem Diagramm-Cache wiederhergestellt. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```

Liefert oder legt die bevorzugte Kulturinformation für die Berechnung einiger Funktionen fest, die für Sprachen mit doppelbytezeichensatz (DBCS) vorgesehen sind.

**Rückgabewert:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```

Liefert oder legt die bevorzugte Kulturinformation für die Berechnung einiger Funktionen fest, die für Sprachen mit doppelbytezeichensatz (DBCS) vorgesehen sind.

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