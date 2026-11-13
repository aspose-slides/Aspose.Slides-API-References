---
title: IChartData
second_title: Aspose.Slides for Java Riferimento API
description: Rappresenta i dati usati per la creazione di un grafico.
type: docs
url: /it/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Rappresenta i dati usati per la creazione di un grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Ottiene il factory delle celle per creare celle usate per le serie del grafico o per le categorie. |
| [getSeries()](#getSeries--) | Ottiene le serie. |
| [getSeriesGroups()](#getSeriesGroups--) | Ottiene i gruppi di serie. |
| [getCategories()](#getCategories--) | Ottiene le categorie primarie (o sia le categorie primarie che secondarie se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è falsa). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Se falso, la proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà (\#getCategories.getCategories) vengono usati sia per le serie primarie che secondarie. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Se falso, la proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà (\#getCategories.getCategories) vengono usati sia per le serie primarie che secondarie. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Ottiene le categorie secondarie se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è vera. |
| [readWorkbookStream()](#readWorkbookStream--) | Scrive la cartella di lavoro Excel contenuta internamente in un flusso in memoria. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Inizializza la cartella di lavoro Excel contenuta internamente con il valore specificato dall'utente. |
| [setRange(String formula)](#setRange-java.lang.String-) | Imposta l'intervallo dei dati del grafico. |
| [getRange()](#getRange--) | Ottiene l'intervallo dei dati del grafico. |
| [getDataSourceType()](#getDataSourceType--) | Rappresenta l'origine dati del grafico |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Rappresenta il percorso della cartella di lavoro esterna se l'origine dati è esterna, altrimenti null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Ottiene il tipo della cartella di lavoro incorporata. |
| [switchRowColumn()](#switchRowColumn--) | Scambia i dati sull'asse. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Imposta la cartella di lavoro esterna come origine dati per il grafico. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Imposta la cartella di lavoro esterna come origine dati per il grafico. |
| [refreshData()](#refreshData--) | Aggiorna i dati del grafico ricaricandoli dalla cartella di lavoro di origine. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Ottiene il factory delle celle per creare celle usate per le serie del grafico o per le categorie. Solo lettura [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Returns:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Ottiene le serie. Solo lettura [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Returns:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Ottiene i gruppi di serie. Solo lettura [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Ogni gruppo di serie contiene serie con tipi combinabili. I gruppi di tipi di serie combinabili sono definiti e descritti con l'enumerazione CombinableSeriesTypesGroup. Inoltre, ogni gruppo di serie contiene serie che vengono tracciate sia sugli assi primari sia sugli assi secondari (non entrambi i casi nello stesso gruppo). Pertanto, il principio del raggruppamento delle serie è un raggruppamento per i gruppi di tipo sopra menzionati e per il tipo di tracciamento primario/secondario. 2) Un gruppo di serie contiene alcune proprietà delle serie che sono comuni a tutte le serie del gruppo ("proprietà del gruppo di serie"). Le "proprietà del gruppo di serie" nella classe ChartSeriesGroup sono lettura/scrittura. Ognuna delle "proprietà del gruppo di serie" può avere una proiezione solo lettura nella classe ChartSeries.

**Returns:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Ottiene le categorie primarie (o sia le categorie primarie che secondarie se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è falsa). Solo lettura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // le categorie correlate sono series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // le categorie correlate sono series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Se (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è falsa, la proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà (\#getCategories.getCategories) vengono usati sia per le serie primarie che secondarie. Se la proprietà è vera, i dati nella proprietà (\#getSecondaryCategories.getSecondaryCategories) vengono usati per le serie secondarie e i dati nella proprietà (\#getCategories.getCategories) vengono usati per le serie primarie.

**Returns:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Se falso, la proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà (\#getCategories.getCategories) vengono usati sia per le serie primarie che secondarie. Se vero, i dati nella proprietà (\#getSecondaryCategories.getSecondaryCategories) vengono usati per le serie secondarie e i dati nella proprietà (\#getCategories.getCategories) vengono usati per le serie primarie. Booleano lettura/scrittura.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // le categorie correlate sono series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // le categorie correlate sono series.getChart().getChartData().getCategories()
>  }
> ```

**Returns:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

Se falso, la proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà (\#getCategories.getCategories) vengono usati sia per le serie primarie che secondarie. Se vero, i dati nella proprietà (\#getSecondaryCategories.getSecondaryCategories) vengono usati per le serie secondarie e i dati nella proprietà (\#getCategories.getCategories) vengono usati per le serie primarie. Booleano lettura/scrittura.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // le categorie correlate sono series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // le categorie correlate sono series.getChart().getChartData().getCategories()
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

Ottiene le categorie secondarie se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è vera. Solo lettura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // le categorie correlate sono series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // le categorie correlate sono series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Se (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è falsa, questa proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà (\#getCategories.getCategories) vengono usati sia per le serie primarie che secondarie. Se la proprietà è vera, i dati in questa proprietà (\#getSecondaryCategories.getSecondaryCategories) vengono usati per le serie secondarie e i dati nella proprietà (\#getCategories.getCategories) vengono usati per le serie primarie.

**Returns:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Scrive la cartella di lavoro Excel contenuta internamente in un flusso in memoria.

**Returns:**
byte[] - Restituisce un array di byte contenente una copia della cartella di lavoro Excel contenuta internamente.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Inizializza la cartella di lavoro Excel contenuta internamente con il valore specificato dall'utente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ms | byte[] | Il flusso fornito dall'utente contenente l'intera cartella di lavoro Excel. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Imposta l'intervallo dei dati del grafico. Le serie e le categorie verranno aggiornate in base al nuovo intervallo di dati. Se il numero di serie nell'intervallo di dati è maggiore del conteggio delle serie nei dati del grafico, verranno aggiunte serie aggiuntive con lo stesso tipo dell'ultima serie nella collezione corrente alla fine della collezione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formula | java.lang.String | La formula dell'intervallo dei dati delle celle. Es.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

Ottiene l'intervallo dei dati del grafico.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Returns:**
java.lang.String - Formula dell'intervallo dei dati delle celle. Es.: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Rappresenta l'origine dati del grafico

**Returns:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Rappresenta il percorso della cartella di lavoro esterna se l'origine dati è esterna, altrimenti null

**Returns:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Ottiene il tipo della cartella di lavoro incorporata. Restituisce [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) se DataSourceType (\#getDataSourceType.getDataSourceType) è [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Solo lettura [WorkbookType](../../com.aspose.slides/workbooktype).

**Returns:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Scambia i dati sull'asse. I dati tracciati sull'asse X verranno spostati sull'asse Y e viceversa.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Imposta la cartella di lavoro esterna come origine dati per il grafico. I dati del grafico verranno aggiornati dalla cartella di lavoro di destinazione.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("../../workbook.xlsx");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| workbookPath | java.lang.String | Percorso della cartella di lavoro di destinazione |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Imposta la cartella di lavoro esterna come origine dati per il grafico.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>     IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>     IChartData chartData = chart.getChartData();
>     ((ChartData)chartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| workbookPath | java.lang.String | Percorso della cartella di lavoro di destinazione |
| updateChartData | boolean | Se il valore è false, verrà aggiornato solo il percorso della cartella di lavoro. I dati del grafico non verranno caricati né aggiornati dalla cartella di lavoro di destinazione. Può essere usato quando la cartella di lavoro di destinazione non esiste o non è disponibile. Se il valore è true, i dati del grafico verranno aggiornati dalla cartella di lavoro di destinazione. |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```

Aggiorna i dati del grafico ricaricandoli dal workbook di origine.

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```