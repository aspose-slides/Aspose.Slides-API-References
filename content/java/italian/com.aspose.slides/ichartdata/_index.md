---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Rappresenta i dati utilizzati per la creazione di un grafico.
type: docs
url: /it/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Rappresenta i dati utilizzati per la creazione di un grafico.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Ottiene la fabbrica di celle per creare celle utilizzate per le serie o le categorie del grafico. |
| [getSeries()](#getSeries--) | Ottiene le serie. |
| [getSeriesGroups()](#getSeriesGroups--) | Ottiene i gruppi di serie. |
| [getCategories()](#getCategories--) | Ottiene le categorie primarie (o sia le categorie primarie che secondarie se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Se false, la proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà (\#getCategories.getCategories) vengono utilizzati sia per le serie primarie che secondarie. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Se false, la proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà (\#getCategories.getCategories) vengono utilizzati sia per le serie primarie che secondarie. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Ottiene le categorie secondarie se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è true. |
| [readWorkbookStream()](#readWorkbookStream--) | Scrive la cartella di lavoro Excel contenuta internamente in uno stream in memoria. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Inizializza la cartella di lavoro Excel contenuta internamente con il valore specificato dall'utente. |
| [setRange(String formula)](#setRange-java.lang.String-) | Imposta l'intervallo di dati del grafico. |
| [getRange()](#getRange--) | Ottiene l'intervallo di dati del grafico. |
| [getDataSourceType()](#getDataSourceType--) | Rappresenta l'origine dati del grafico |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Rappresenta il percorso della cartella di lavoro esterna se l'origine dati è esterna, altrimenti null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Ottiene il tipo della cartella di lavoro incorporata. |
| [switchRowColumn()](#switchRowColumn--) | Scambia i dati sull'asse. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Imposta la cartella di lavoro esterna come origine dati per il grafico. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Imposta la cartella di lavoro esterna come origine dati per il grafico. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Ottiene la fabbrica di celle per creare celle usate per le serie o le categorie del grafico. Solo lettura [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Restituisce:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Ottiene le serie. Solo lettura [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Restituisce:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Ottiene i gruppi di serie. Solo lettura [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Ogni gruppo di serie contiene serie con tipi combinabili. I gruppi di tipi di serie combinabili sono definiti e descritti con l'enum CombinableSeriesTypesGroup. Inoltre, ogni gruppo di serie contiene serie che vengono tracciate o sugli assi primari o sugli assi secondari (non entrambi i casi nello stesso gruppo). Quindi, il principio di raggruppamento delle serie è un raggruppamento per gruppi di tipo sopra menzionati e per tipo di tracciamento primario/secondario.

**Restituisce:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Ottiene le categorie primarie (o sia le categorie primarie che secondarie se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è false). Solo lettura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è false, allora la proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati in questa proprietà (\#getCategories.getCategories) vengono usati sia per le serie primarie che secondarie. Se la proprietà è true, i dati nella proprietà (\#getSecondaryCategories.getSecondaryCategories) sono usati per le serie secondarie e i dati in questa proprietà (\#getCategories.getCategories) sono usati per le serie primarie.

**Restituisce:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Se false, la proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà (\#getCategories.getCategories) vengono utilizzati sia per le serie primarie che secondarie. Se true, i dati nella proprietà (\#getSecondaryCategories.getSecondaryCategories) sono usati per le serie secondarie e i dati nella proprietà (\#getCategories.getCategories) sono usati per le serie primarie. Lettura/scrittura boolean.

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

**Restituisce:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

Se false, la proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà (\#getCategories.getCategories) vengono utilizzati sia per le serie primarie che secondarie. Se true, i dati nella proprietà (\#getSecondaryCategories.getSecondaryCategories) sono usati per le serie secondarie e i dati nella proprietà (\#getCategories.getCategories) sono usati per le serie primarie. Lettura/scrittura boolean.

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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

Ottiene le categorie secondarie se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è true. Solo lettura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è false, questa proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà (\#getCategories.getCategories) sono usati sia per le serie primarie che secondarie. Se la proprietà è true, i dati in questa proprietà (\#getSecondaryCategories.getSecondaryCategories) sono usati per le serie secondarie e i dati nella proprietà (\#getCategories.getCategories) sono usati per le serie primarie.

**Restituisce:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Scrive la cartella di lavoro Excel contenuta internamente in uno stream in memoria.

**Restituisce:**
byte[] - Restituisce un array di byte contenente una copia della cartella di lavoro Excel contenuta internamente.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Inizializza la cartella di lavoro Excel contenuta internamente con il valore specificato dall'utente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ms | byte[] | Lo stream fornito dall'utente contenente l'intera cartella di lavoro Excel. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Imposta l'intervallo di dati del grafico. Le serie e le categorie verranno aggiornate in base al nuovo intervallo di dati. Se il numero di serie nell'intervallo di dati è maggiore del numero di serie nei dati del grafico, verranno aggiunte serie aggiuntive con lo stesso tipo dell'ultima serie nella collezione corrente alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formula | java.lang.String | La formula dell'intervallo di dati delle celle. Es.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

Ottiene l'intervallo di dati del grafico.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Restituisce:**
java.lang.String - Formula dell'intervallo di dati delle celle. Es.: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Rappresenta l'origine dati del grafico

**Restituisce:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Rappresenta il percorso della cartella di lavoro esterna se l'origine dati è esterna, altrimenti null

**Restituisce:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Ottiene il tipo della cartella di lavoro incorporata. Restituisce [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) se DataSourceType (\#getDataSourceType.getDataSourceType) è [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Solo lettura [WorkbookType](../../com.aspose.slides/workbooktype).

**Restituisce:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Scambia i dati sull'asse. I dati tracciati sull'asse X saranno spostati sull'asse Y e viceversa.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Imposta la cartella di lavoro esterna come origine dati per il grafico. I dati del grafico saranno aggiornati dalla cartella di lavoro di destinazione.

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

**Parametri:**
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

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| workbookPath | java.lang.String | Percorso della cartella di lavoro di destinazione |
| updateChartData | boolean | Se il valore è false verrà aggiornato solo il percorso della cartella di lavoro. I dati del grafico non verranno caricati né aggiornati dalla cartella di lavoro di destinazione. Può essere usato quando la cartella di lavoro di destinazione non esiste o non è disponibile. Se il valore è true i dati del grafico verranno aggiornati dalla cartella di lavoro di destinazione. |