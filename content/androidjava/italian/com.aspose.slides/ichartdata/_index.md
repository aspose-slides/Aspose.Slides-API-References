---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Rappresenta i dati utilizzati per il tracciamento di un grafico.
type: docs
url: /it/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Rappresenta i dati utilizzati per il tracciamento di un grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Gets the cells factory to create cells used for chart series or categories. |
| [getSeries()](#getSeries--) | Gets the series. |
| [getSeriesGroups()](#getSeriesGroups--) | Gets the groups of series. |
| [getCategories()](#getCategories--) | Gets the primary categories (or both primary and secondary categories if (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | If false then (\#getSecondaryCategories.getSecondaryCategories) property return null and data in (\#getCategories.getCategories) property is used both for primary and secondary series. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | If false then (\#getSecondaryCategories.getSecondaryCategories) property return null and data in (\#getCategories.getCategories) property is used both for primary and secondary series. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Gets the secondary categories if (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) property is true. |
| [readWorkbookStream()](#readWorkbookStream--) | Writes the internally contained Excel workbook it into an in-memory stream. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initializes the internally contained Excel workbook with user-specified value. |
| [setRange(String formula)](#setRange-java.lang.String-) | Set chart data range. |
| [getRange()](#getRange--) | Gets chart data range. |
| [getDataSourceType()](#getDataSourceType--) | Represents data source of the chart |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Represents external workbook path if data source is external, null otherwise |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Gets the type of the embedded workbook. |
| [switchRowColumn()](#switchRowColumn--) | Swap the data over the axis. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Sets external workbook as a data source for the chart. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Sets external workbook as a data source for the chart. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Ottiene la fabbrica di celle per creare celle utilizzate per le serie o le categorie del grafico. Sola lettura [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Restituisce:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Ottiene le serie. Sola lettura [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Restituisce:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Ottiene i gruppi di serie. Sola lettura [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Each group of series contains series with combinable types. Groups of combinable series types defined and described with CombinableSeriesTypesGroup enum. Also each group of series contains series witch is plotted whether on primary axes or on secondary axes (not both cases in one group). So, principle of series grouping is a grouping by type groups mentioned above and by primary/secondary plotting type. 2) Group of series contains some series properies whitch is common for each series in group ("series group properties"). "Series group properties" in ChartSeriesGroup class is read/write. Each of "series group properties" can have a read-only projection in ChartSeries class.

**Restituisce:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Ottiene le categorie primarie (o sia le categorie primarie che secondarie se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è false). Sola lettura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è false, allora la proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati in questa proprietà (\#getCategories.getCategories) vengono usati sia per le serie primarie sia per le serie secondarie. Se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è true, allora i dati nella proprietà (\#getSecondaryCategories.getSecondaryCategories) vengono usati per le serie secondarie e i dati in questa proprietà (\#getCategories.getCategories) vengono usati per le serie primarie.

**Restituisce:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Se false allora la proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà (\#getCategories.getCategories) vengono usati sia per le serie primarie sia per le serie secondarie. Se true, i dati nella proprietà (\#getSecondaryCategories.getSecondaryCategories) vengono usati per le serie secondarie e i dati nella proprietà (\#getCategories.getCategories) vengono usati per le serie primarie. Lettura/scrittura boolean.

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

Se false allora la proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà (\#getCategories.getCategories) vengono usati sia per le serie primarie sia per le serie secondarie. Se true, i dati nella proprietà (\#getSecondaryCategories.getSecondaryCategories) vengono usati per le serie secondarie e i dati nella proprietà (\#getCategories.getCategories) vengono usati per le serie primarie. Lettura/scrittura boolean.

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

Ottiene le categorie secondarie se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è true. Sola lettura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è false, allora questa proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà (\#getCategories.getCategories) vengono usati sia per le serie primarie sia per le serie secondarie. Se la proprietà (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) è true, allora i dati in questa proprietà (\#getSecondaryCategories.getSecondaryCategories) vengono usati per le serie secondarie e i dati nella proprietà (\#getCategories.getCategories) vengono usati per le serie primarie.

**Restituisce:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Scrive la cartella di lavoro Excel contenuta internamente in un flusso in memoria.

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
| ms | byte[] | Il flusso fornito dall'utente contenente l'intera cartella di lavoro Excel. |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Imposta l'intervallo di dati del grafico. Le serie e le categorie verranno aggiornate in base al nuovo intervallo di dati. Se il numero di serie nell'intervallo di dati è maggiore del conteggio delle serie nei dati del grafico, allora verranno aggiunte serie aggiuntive con lo stesso tipo dell'ultima serie nella collezione corrente alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formula | java.lang.String | La formula dell'intervallo di dati delle celle. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
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
java.lang.String - Formula dell'intervallo di dati delle celle. E.g: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Rappresenta la sorgente dati del grafico

**Restituisce:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Rappresenta il percorso del workbook esterno se la sorgente dati è esterna, altrimenti null

**Restituisce:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Ottiene il tipo del workbook incorporato. Restituisce [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) se DataSourceType (\#getDataSourceType.getDataSourceType) è [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Sola lettura [WorkbookType](../../com.aspose.slides/workbooktype).

**Restituisce:**
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

Imposta il workbook esterno come sorgente dati per il grafico. I dati del grafico saranno aggiornati dal workbook di destinazione.

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
| workbookPath | java.lang.String | Percorso del workbook di destinazione |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Imposta il workbook esterno come sorgente dati per il grafico.

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
| workbookPath | java.lang.String | Percorso del workbook di destinazione |
| updateChartData | boolean | Se il valore è false, verrà aggiornato solo il percorso del workbook. I dati del grafico non saranno caricati né aggiornati dal workbook di destinazione. Può essere usato quando il workbook di destinazione non esiste o non è disponibile. Se il valore è true, i dati del grafico saranno aggiornati dal workbook di destinazione. |