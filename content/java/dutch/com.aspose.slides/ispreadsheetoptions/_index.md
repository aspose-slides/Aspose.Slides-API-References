---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Java API Reference
description: Represents options which can be used to specify additional spreadsheets behavior.
type: docs
url: /nl/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Stelt opties voor die kunnen worden gebruikt om extra spreadsheet-gedrag te specificeren.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Gets or sets preferred culture information for calculating some functions intended for use with languages that use the double-byte character set (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Gets or sets preferred culture information for calculating some functions intended for use with languages that use the double-byte character set (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


Gets or sets preferred culture information for calculating some functions intended for use with languages that use the double-byte character set (DBCS).

**Retour:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


Gets or sets preferred culture information for calculating some functions intended for use with languages that use the double-byte character set (DBCS).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


Als de gegevensbron voor het diagram een extern werkboek is en deze niet beschikbaar is, wordt deze hersteld uit de diagramcache.

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

**Retour:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


Als de gegevensbron voor het diagram een extern werkboek is en deze niet beschikbaar is, wordt deze hersteld uit de diagramcache.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |