---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options which can be used to specify additional spreadsheets behavior.
type: docs
url: /nl/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Represents options which can be used to specify additional spreadsheets behavior.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Haalt of stelt de voorkeurs-cultuurinformatie in voor het berekenen van sommige functies die bedoeld zijn voor talen die de dubbelbyte-karakterset (DBCS) gebruiken. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Haalt of stelt de voorkeurs-cultuurinformatie in voor het berekenen van sommige functies die bedoeld zijn voor talen die de dubbelbyte-karakterset (DBCS) gebruiken. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Als de gegevensbron voor de grafiek een extern werkmap is en deze niet beschikbaar is, wordt deze hersteld uit de grafiekcache. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Als de gegevensbron voor de grafiek een extern werkmap is en deze niet beschikbaar is, wordt deze hersteld uit de grafiekcache. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


Haalt of stelt de voorkeurs-cultuurinformatie in voor het berekenen van sommige functies die bedoeld zijn voor talen die de dubbelbyte-karakterset (DBCS) gebruiken.

**Retourwaarde:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


Haalt of stelt de voorkeurs-cultuurinformatie in voor het berekenen van sommige functies die bedoeld zijn voor talen die de dubbelbyte-karakterset (DBCS) gebruiken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


Als de gegevensbron voor de grafiek een extern werkmap is en deze niet beschikbaar is, wordt deze hersteld uit de grafiekcache.

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


**Retourwaarde:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


Als de gegevensbron voor de grafiek een extern werkmap is en deze niet beschikbaar is, wordt deze hersteld uit de grafiekcache.

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