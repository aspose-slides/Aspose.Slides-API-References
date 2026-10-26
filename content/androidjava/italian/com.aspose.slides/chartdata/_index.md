---
title: ChartData
second_title: Aspose.Slides per Android via Java API Reference
description: Rappresenta i dati utilizzati per la creazione di un grafico.
type: docs
url: /it/com.aspose.slides/chartdata/
---
**Eredità:**
java.lang.Object, com.aspose.slides.DomObject

**Tutte le interfacce implementate:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Rappresenta i dati utilizzati per la creazione di un grafico.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Ottiene la fabbrica di celle per creare celle utilizzate per le serie o le categorie del grafico. |
| [getSeries()](#getSeries--) | Ottiene le serie. |
| [getSeriesGroups()](#getSeriesGroups--) | Ottiene i gruppi di serie. |
| [getCategories()](#getCategories--) | Ottiene le categorie primarie (o sia le categorie primarie che secondarie se la proprietà \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) è false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Se false allora la proprietà \#getSecondaryCategories.getSecondaryCategories restituisce null e i dati nella proprietà \#getCategories.getCategories sono usati sia per le serie primarie che secondarie. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Se false allora la proprietà \#getSecondaryCategories.getSecondaryCategories restituisce null e i dati nella proprietà \#getCategories.getCategories sono usati sia per le serie primarie che secondarie. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Ottiene le categorie secondarie se la proprietà \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) è true. |
| [readWorkbookStream()](#readWorkbookStream--) | Scrive la cartella di lavoro Excel contenuta internamente in un flusso in memoria. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Inizializza la cartella di lavoro Excel contenuta internamente con il valore specificato dall'utente. |
| [getDataSourceType()](#getDataSourceType--) | Rappresenta il percorso del workbook esterno se la fonte dei dati è esterna, altrimenti null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Rappresenta la sorgente dati del grafico. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Ottiene il tipo del workbook incorporato. |
| [getRange()](#getRange--) | Ottiene l'intervallo dei dati del grafico. |
| [setRange(String formula)](#setRange-java.lang.String-) | Imposta l'intervallo dei dati del grafico. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Imposta il workbook esterno come sorgente dati per il grafico. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Imposta il workbook esterno come sorgente dati per il grafico. |
| [switchRowColumn()](#switchRowColumn--) | Scambia i dati sull'asse. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```


Ottiene la fabbrica di celle per creare celle utilizzate per le serie o le categorie del grafico. Solo lettura [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Restituisce:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```


Ottiene le serie. Solo lettura [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Restituisce:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```


Ottiene i gruppi di serie. Solo lettura [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Ogni gruppo di serie contiene serie con tipi combinabili. I gruppi di tipi di serie combinabili sono definiti e descritti con l'enum CombinableSeriesTypesGroup. Inoltre, ogni gruppo di serie contiene serie che vengono tracciate sia sull'asse primario sia su quello secondario (non entrambi i casi nello stesso gruppo). Pertanto, il principio del raggruppamento delle serie è un raggruppamento per i gruppi di tipo sopra menzionati e per il tipo di tracciamento primario/secondario. 2) Un gruppo di serie contiene alcune proprietà delle serie che sono comuni a tutte le serie del gruppo ("series group properties"). Le "series group properties" nella classe ChartSeriesGroup sono di lettura/scrittura. Ognuna delle "series group properties" può avere una proiezione di sola lettura nella classe ChartSeries.

**Restituisce:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```


Ottiene le categorie primarie (o sia le categorie primarie che secondarie se la proprietà \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) è false). Solo lettura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Se la proprietà \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) è false allora la proprietà (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà \#getCategories.getCategories sono usati sia per le serie primarie che secondarie. Se la proprietà \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) è true allora i dati nella proprietà (\#getSecondaryCategories.getSecondaryCategories) sono usati per le serie secondarie e i dati nella proprietà \#getCategories.getCategories sono usati per le serie primarie.

**Restituisce:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```


Se false allora la proprietà \#getSecondaryCategories.getSecondaryCategories restituisce null e i dati nella proprietà \#getCategories.getCategories sono usati sia per le serie primarie che secondarie. Se true allora i dati nella proprietà \#getSecondaryCategories.getSecondaryCategories sono usati per le serie secondarie e i dati nella proprietà \#getCategories.getCategories sono usati per le serie primarie. Lettura/scrittura boolean.

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
public final void setUseSecondaryCategories(boolean value)
```


Se false allora la proprietà \#getSecondaryCategories.getSecondaryCategories restituisce null e i dati nella proprietà \#getCategories.getCategories sono usati sia per le serie primarie che secondarie. Se true allora i dati nella proprietà \#getSecondaryCategories.getSecondaryCategories sono usati per le serie secondarie e i dati nella proprietà \#getCategories.getCategories sono usati per le serie primarie. Lettura/scrittura boolean.

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
public final IChartCategoryCollection getSecondaryCategories()
```


Ottiene le categorie secondarie se la proprietà \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) è true. Solo lettura [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Se la proprietà \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) è false allora questa (\#getSecondaryCategories.getSecondaryCategories) restituisce null e i dati nella proprietà \#getCategories.getCategories sono usati sia per le serie primarie che secondarie. Se la proprietà \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) è true allora i dati in questa \#getSecondaryCategories.getSecondaryCategories sono usati per le serie secondarie e i dati nella \#getCategories.getCategories sono usati per le serie primarie.

**Restituisce:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```


Scrive la cartella di lavoro Excel contenuta internamente in un flusso in memoria.

**Restituisce:**
byte[] - Restituisce un'istanza di array di byte contenente una copia della cartella di lavoro Excel contenuta internamente.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```


Inizializza la cartella di lavoro Excel contenuta internamente con il valore specificato dall'utente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ms | byte[] | Il flusso fornito dall'utente contenente l'intera cartella di lavoro Excel. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```


Rappresenta il percorso del workbook esterno se la fonte dei dati è esterna, altrimenti null.

**Restituisce:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```


Rappresenta la sorgente dati del grafico.

**Restituisce:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```


Ottiene il tipo del workbook incorporato. Restituisce [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) se DataSourceType (\#getDataSourceType.getDataSourceType) è [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Solo lettura [WorkbookType](../../com.aspose.slides/workbooktype).

**Restituisce:**
int
### getRange() {#getRange--}
```
public final String getRange()
```


Ottiene l'intervallo dei dati del grafico.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>       String result = ((ChartData)chart.getChartData()).getRange();
>   } finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Restituisce:**
java.lang.String - Formula dell'intervallo di dati delle celle. Es.: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```


Imposta l'intervallo dei dati del grafico. Le serie e le categorie saranno aggiornate in base al nuovo intervallo di dati. Se il numero di serie nell'intervallo di dati supera il conteggio delle serie nei dati del grafico, saranno aggiunte serie aggiuntive con lo stesso tipo dell'ultima serie nella collezione corrente, alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formula | java.lang.String | La formula dell'intervallo di dati delle celle. Es.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
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
>     if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| workbookPath | java.lang.String | Percorso al workbook di destinazione |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```


Imposta il workbook esterno come sorgente dati per il grafico.

--------------------

> ```
> Presentation pres = new Presentation();
>  try
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 600, true);
>      IChartData chartData = chart.getChartData();
>      ((ChartData).setExternalWorkbook("http://path/doesnt/exists", false);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| workbookPath | java.lang.String | Percorso al workbook di destinazione |
| updateChartData | boolean | Se il valore è false, verrà aggiornato solo il percorso del workbook. I dati del grafico non saranno caricati e aggiornati dal workbook di destinazione. Può essere usato quando il workbook di destinazione non esiste o non è disponibile. Se il valore è true, i dati del grafico saranno aggiornati dal workbook di destinazione. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```


Scambia i dati sull'asse. I dati tracciati sull'asse X saranno spostati sull'asse Y e viceversa.