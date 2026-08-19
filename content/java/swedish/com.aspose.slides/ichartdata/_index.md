---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Representerar data som används för att rita ett diagram.
type: docs
url: /sv/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Representerar data som används för att rita ett diagram.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Hämtar cellfabriken för att skapa celler som används för diagramserier eller -kategorier. |
| [getSeries()](#getSeries--) | Hämtar serierna. |
| [getSeriesGroups()](#getSeriesGroups--) | Hämtar grupper av serier. |
| [getCategories()](#getCategories--) | Hämtar de primära kategorierna (eller både primära och sekundära kategorier om egenskapen (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) är falsk). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Om falsk returnerar egenskapen (\#getSecondaryCategories.getSecondaryCategories) null och data i egenskapen (\#getCategories.getCategories) används både för primära och sekundära serier. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Om falsk returnerar egenskapen (\#getSecondaryCategories.getSecondaryCategories) null och data i egenskapen (\#getCategories.getCategories) används både för primära och sekundära serier. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Hämtar de sekundära kategorierna om egenskapen (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) är sann. |
| [readWorkbookStream()](#readWorkbookStream--) | Skriver den internt inneslutna Excel-arbetsboken till ett minnesström. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initierar den internt inneslutna Excel-arbetsboken med ett användarspecificerat värde. |
| [setRange(String formula)](#setRange-java.lang.String-) | Ställer in diagramdataintervall. |
| [getRange()](#getRange--) | Hämtar diagramdataintervall. |
| [getDataSourceType()](#getDataSourceType--) | Representerar datakälla för diagrammet |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Representerar extern arbetsboksökväg om datakällan är extern, annars null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Hämtar typen av den inbäddade arbetsboken. |
| [switchRowColumn()](#switchRowColumn--) | Byter data över axeln. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Ställer in extern arbetsbok som datakälla för diagrammet. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Ställer in extern arbetsbok som datakälla för diagrammet. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Hämtar cellfabriken för att skapa celler som används för diagramserier eller -kategorier. Skrivskyddad [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Returnerar:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Hämtar serierna. Skrivskyddad [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Returnerar:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Hämtar grupper av serier. Skrivskyddad [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Varje seriegrupp innehåller serier med kombinerbara typer. Grupper av kombinerbara serietyper definieras och beskrivs med enum-typen CombinableSeriesTypesGroup. Dessutom innehåller varje seriegrupp serier som plottas antingen på primära axlar eller på sekundära axlar (inte båda i samma grupp). Så principen för seriegroupering är en gruppering efter ovanstående typgrupper och efter primär/sekundär plottningstyp. 2) En seriegrupp innehåller vissa serieegenskaper som är gemensamma för varje serie i gruppen ("seriegruppsegenskaper"). "Seriegruppsegenskaper" i klassen ChartSeriesGroup är läs/skriv. Varje "seriegruppsegenskap" kan ha en skrivskyddad projektion i klassen ChartSeries.

**Returnerar:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Hämtar de primära kategorierna (eller både primära och sekundära kategorier om egenskapen (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) är falsk). Skrivskyddad [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // relaterade kategorier är series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // relaterade kategorier är series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Om egenskapen (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) är falsk returnerar egenskapen (\#getSecondaryCategories.getSecondaryCategories) null och data i egenskapen (\#getCategories.getCategories) används både för primära och sekundära serier. Om egenskapen är sann används data i egenskapen (\#getSecondaryCategories.getSecondaryCategories) för sekundära serier och data i egenskapen (\#getCategories.getCategories) för primära serier.

**Returnerar:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Om falsk returnerar egenskapen (\#getSecondaryCategories.getSecondaryCategories) null och data i egenskapen (\#getCategories.getCategories) används både för primära och sekundära serier. Om sann används data i egenskapen (\#getSecondaryCategories.getSecondaryCategories) för sekundära serier och data i egenskapen (\#getCategories.getCategories) för primära serier. Läs/skriv boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // relaterade kategorier är series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // relaterade kategorier är series.getChart().getChartData().getCategories()
>  }
> ```

**Returnerar:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

Om falsk returnerar egenskapen (\#getSecondaryCategories.getSecondaryCategories) null och data i egenskapen (\#getCategories.getCategories) används både för primära och sekundära serier. Om sann används data i egenskapen (\#getSecondaryCategories.getSecondaryCategories) för sekundära serier och data i egenskapen (\#getCategories.getCategories) för primära serier. Läs/skriv boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // relaterade kategorier är series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // relaterade kategorier är series.getChart().getChartData().getCategories()
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

Hämtar de sekundära kategorierna om egenskapen (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) är sann. Skrivskyddad [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // relaterade kategorier är series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // relaterade kategorier är series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Om egenskapen (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) är falsk returnerar egenskapen (\#getSecondaryCategories.getSecondaryCategories) null och data i egenskapen (\#getCategories.getCategories) används både för primära och sekundära serier. Om egenskapen är sann används data i egenskapen (\#getSecondaryCategories.getSecondaryCategories) för sekundära serier och data i egenskapen (\#getCategories.getCategories) för primära serier.

**Returnerar:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Skriver den internt inneslutna Excel-arbetsboken till ett minnesström.

**Returnerar:**
byte[] - Returnerar en byte-array som innehåller en kopia av den internt inneslutna Excel-arbetsboken.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Initierar den internt inneslutna Excel-arbetsboken med ett användarspecificerat värde.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ms | byte[] | Den användarskapade strömmen som innehåller hela Excel-arbetsboken. |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Ställer in diagramdataintervall. Serier och kategorier uppdateras baserat på det nya intervallet. Om antalet serier i intervallet är större än antalet serier i diagramdata läggs extra serier med samma typ som den sista serien i den nuvarande samlingen till i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formula | java.lang.String | Formeln för cellintervallet. Till exempel: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
### getRange() {#getRange--}
```
public abstract String getRange()
```

Hämtar diagramdataintervall.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Returnerar:**
java.lang.String - Formeln för cellintervallet. Till exempel: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Representerar datakälla för diagrammet

**Returnerar:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Representerar extern arbetsboksökväg om datakällan är extern, annars null

**Returnerar:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Hämtar typen av den inbäddade arbetsboken. Returnerar [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) om DataSourceType (\#getDataSourceType.getDataSourceType) är [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Skrivskyddad [WorkbookType](../../com.aspose.slides/workbooktype).

**Returnerar:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Byter data över axeln. Data som diagrammeras på X-axeln flyttas till Y-axeln och omvänt.
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Ställer in extern arbetsbok som datakälla för diagrammet. Diagramdata uppdateras från mål-arbetsboken.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| workbookPath | java.lang.String | Sökväg till mål-arbetsboken |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Ställer in extern arbetsbok som datakälla för diagrammet.

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

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| workbookPath | java.lang.String | Sökväg till mål-arbetsboken |
| updateChartData | boolean | Om värdet är falskt uppdateras endast arbetsboksökvägen. Diagramdata laddas inte och uppdateras inte från mål-arbetsboken. Kan användas när mål-arbetsboken inte finns eller inte är tillgänglig. Om värdet är sant uppdateras diagramdata från mål-arbetsboken. |