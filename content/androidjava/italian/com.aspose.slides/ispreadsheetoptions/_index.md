---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta le opzioni che possono essere utilizzate per specificare un comportamento aggiuntivo dei fogli di calcolo.
type: docs
url: /it/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Rappresenta le opzioni che possono essere utilizzate per specificare un comportamento aggiuntivo dei fogli di calcolo.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Ottiene o imposta le informazioni sulla cultura preferita per calcolare alcune funzioni destinate all'uso con lingue che utilizzano il set di caratteri a doppio byte (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Ottiene o imposta le informazioni sulla cultura preferita per calcolare alcune funzioni destinate all'uso con lingue che utilizzano il set di caratteri a doppio byte (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Se la fonte dati per il grafico è una cartella di lavoro esterna e non è disponibile, verrà ripristinata dalla cache del grafico. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Se la fonte dati per il grafico è una cartella di lavoro esterna e non è disponibile, verrà ripristinata dalla cache del grafico. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


Ottiene o imposta le informazioni sulla cultura preferita per calcolare alcune funzioni destinate all'uso con lingue che utilizzano il set di caratteri a doppio byte (DBCS).

**Restituisce:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


Ottiene o imposta le informazioni sulla cultura preferita per calcolare alcune funzioni destinate all'uso con lingue che utilizzano il set di caratteri a doppio byte (DBCS).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


Se la fonte dati per il grafico è una cartella di lavoro esterna e non è disponibile, verrà ripristinata dalla cache del grafico.

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


**Restituisce:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


Se la fonte dati per il grafico è una cartella di lavoro esterna e non è disponibile, verrà ripristinata dalla cache del grafico.

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


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |