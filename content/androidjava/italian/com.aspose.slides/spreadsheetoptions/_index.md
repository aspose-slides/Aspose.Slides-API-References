---
title: SpreadsheetOptions
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta le opzioni che possono essere usate per specificare un comportamento aggiuntivo dei fogli di calcolo.
type: docs
url: /it/com.aspose.slides/spreadsheetoptions/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Rappresenta le opzioni che possono essere usate per specificare un comportamento aggiuntivo dei fogli di calcolo.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Inizializza una nuova istanza della classe [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions). |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Ottiene o imposta le informazioni sulla cultura preferita per calcolare alcune funzioni destinate all'uso con lingue che utilizzano il set di caratteri a doppio byte (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Ottiene o imposta le informazioni sulla cultura preferita per calcolare alcune funzioni destinate all'uso con lingue che utilizzano il set di caratteri a doppio byte (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Se la fonte dati per il grafico è una cartella di lavoro esterna e non è disponibile, verrà recuperata dalla cache del grafico. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Se la fonte dati per il grafico è una cartella di lavoro esterna e non è disponibile, verrà recuperata dalla cache del grafico. |

### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

Inizializza una nuova istanza della classe [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions).

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

Ottiene o imposta le informazioni sulla cultura preferita per calcolare alcune funzioni destinate all'uso con lingue che utilizzano il set di caratteri a doppio byte (DBCS).

**Restituisce:**
java.util.Locale

### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

Ottiene o imposta le informazioni sulla cultura preferita per calcolare alcune funzioni destinate all'uso con lingue che utilizzano il set di caratteri a doppio byte (DBCS).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

Se la fonte dati per il grafico è una cartella di lavoro esterna e non è disponibile, verrà recuperata dalla cache del grafico.

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
public final void setRecoverWorkbookFromChartCache(boolean value)
```

Se la fonte dati per il grafico è una cartella di lavoro esterna e non è disponibile, verrà recuperata dalla cache del grafico.

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