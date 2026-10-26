---
title: SpreadsheetOptions
second_title: Aspose.Slides voor Android via Java API-referentie
description: Geeft opties weer die gebruikt kunnen worden om extra spreadsheetgedrag te specificeren.
type: docs
url: /nl/com.aspose.slides/spreadsheetoptions/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Stelt opties voor die gebruikt kunnen worden om extra spreadsheetgedrag te specificeren.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Initialiseert een nieuw exemplaar van de klasse [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions). |
## Methodes

| Methode | Beschrijving |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Haalt of stelt de voorkeurscultuur-informatie in voor het berekenen van enkele functies die bedoeld zijn voor gebruik met talen die de double-byte character set (DBCS) gebruiken. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Haalt of stelt de voorkeurscultuur-informatie in voor het berekenen van enkele functies die bedoeld zijn voor gebruik met talen die de double-byte character set (DBCS) gebruiken. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Als de gegevensbron voor de grafiek een extern werkboek is en het niet beschikbaar is, wordt het hersteld vanuit de grafiekcache. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Als de gegevensbron voor de grafiek een extern werkboek is en het niet beschikbaar is, wordt het hersteld vanuit de grafiekcache. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```


Initialiseert een nieuw exemplaar van de klasse [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions).

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```


Haalt of stelt de voorkeurscultuur-informatie in voor het berekenen van enkele functies die bedoeld zijn voor gebruik met talen die de double-byte character set (DBCS) gebruiken.

**Retour:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```


Haalt of stelt de voorkeurscultuur-informatie in voor het berekenen van enkele functies die bedoeld zijn voor gebruik met talen die de double-byte character set (DBCS) gebruiken.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```


Als de gegevensbron voor de grafiek een extern werkboek is en het niet beschikbaar is, wordt het hersteld vanuit de grafiekcache.

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
public final void setRecoverWorkbookFromChartCache(boolean value)
```


Als de gegevensbron voor de grafiek een extern werkboek is en het niet beschikbaar is, wordt het hersteld vanuit de grafiekcache.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |