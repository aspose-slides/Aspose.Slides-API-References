---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Representerar data som används för att plotta ett diagram.
type: docs
url: /sv/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Representerar data som används för att plotta ett diagram.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Hämtar cellfabriken för att skapa celler som används för diagramserier eller kategorier. |
| [getSeries()](#getSeries--) | Hämtar serierna. |
| [getSeriesGroups()](#getSeriesGroups--) | Hämtar grupperna av serier. |
| [getCategories()](#getCategories--) | Hämtar de primära kategorierna (eller både primära och sekundära kategorier om egenskapen (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) är falsk). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Om falskt returnerar egenskapen (\#getSecondaryCategories.getSecondaryCategories) null och data i egenskapen (\#getCategories.getCategories) används både för primära och sekundära serier. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Om falskt returnerar egenskapen (\#getSecondaryCategories.getSecondaryCategories) null och data i egenskapen (\#getCategories.getCategories) används både för primära och sekundära serier. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Hämtar de sekundära kategorierna om egenskapen (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) är sann. |
| [readWorkbookStream()](#readWorkbookStream--) | Skriver den internt innehållna Excel-arbetsboken till en minnesström. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initierar den internt innehållna Excel-arbetsboken med ett användarspecificerat värde. |
| [setRange(String formula)](#setRange-java.lang.String-) | Ställer in diagrammets dataintervall. |
| [getRange()](#getRange--) | Hämtar diagrammets dataintervall. |
| [getDataSourceType()](#getDataSourceType--) | Representerar datakällan för diagrammet |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Representerar sökvägen till extern arbetsbok om datakällan är extern, annars null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Hämtar typen av den inbäddade arbetsboken. |
| [switchRowColumn()](#switchRowColumn--) | Byter data över axeln. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Anger extern arbetsbok som datakälla för diagrammet. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Anger extern arbetsbok som datakälla för diagrammet. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Hämtar cellfabriken för att skapa celler som används för diagramserier eller kategorier. Skrivskyddad [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

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

Hämtar grupperna av serier. Skrivskyddad [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Varje grupp av serier innehåller serier med kombinerbara typer. Grupper av kombinerbara serietyper definieras och beskrivs med enumen CombinableSeriesTypesGroup. Dessutom innehåller varje grupp av serier serier som plottas antingen på primära axlar eller på sekundära axlar (inte båda i samma grupp). Principen för seriegroupering är alltså gruppering efter ovan nämnda typgrupper samt efter primär/sekundär plottningstyp. 2) En grupp av serier innehåller några serieegenskaper som är gemensamma för varje serie i gruppen ("series group properties"). "Series group properties" i klassen ChartSeriesGroup är Läs/skriv. Varje av "series group properties" kan ha en skrivskyddad projection i klassen ChartSeries.

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

Om (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) är falsk så returnerar egenskapen (\#getSecondaryCategories.getSecondaryCategories) null och data i egenskapen (\#getCategories.getCategories) används både för primära och sekundära serier. Om (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) är sann så används data i egenskapen (\#getSecondaryCategories.getSecondaryCategories) för sekundära serier och data i egenskapen (\#getCategories.getCategories) för primära serier.

**Returnerar:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Om falskt returnerar egenskapen (\#getSecondaryCategories.getSecondaryCategories) null och data i egenskapen (\#getCategories.getCategories) används både för primära och sekundära serier. Om sant så används data i egenskapen (\#getSecondaryCategories.getSecondaryCategories) för sekundära serier och data i egenskapen (\#getCategories.getCategories) för primära serier. Läs/skriv boolean.

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

Om falskt returnerar egenskapen (\#getSecondaryCategories.getSecondaryCategories) null och data i egenskapen (\#getCategories.getCategories) används både för primära och sekundära serier. Om sant så används data i egenskapen (\#getSecondaryCategories.getSecondaryCategories) för sekundära serier och data i egenskapen (\#getCategories.getCategories) för primära serier. Läs/skriv boolean.

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

**Parameter** | **Typ** | **Beskrivning**
--- | --- | ---
value | boolean | 

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

Om (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) är falsk så returnerar egenskapen (\#getSecondaryCategories.getSecondaryCategories) null och data i egenskapen (\#getCategories.getCategories) används både för primära och sekundära serier. Om (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) är sann så används data i egenskapen (\#getSecondaryCategories.getSecondaryCategories) för sekundära serier och data i egenskapen (\#getCategories.getCategories) för primära serier.

**Returnerar:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Skriver den internt innehållna Excel-arbetsboken till en minnesström.

**Returnerar:**
byte[] - Returnerar en byte-array som innehåller en kopia av den internt innehållna Excel-arbetsboken.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Initierar den internt innehållna Excel-arbetsboken med ett användarspecificerat värde.

**Parameter** | **Typ** | **Beskrivning**
--- | --- | ---
ms | byte[] | Den användarskickade strömmen som innehåller hela Excel-arbetsboken.
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Ställer in diagrammets dataintervall. Serier och kategorier kommer att uppdateras baserat på det nya dataintervallet. Om antalet serier i dataintervallet är större än antalet serier i diagramdata så kommer ytterligare serier med samma typ som den sista serien i den aktuella samlingen att läggas till i slutet av samlingen.

**Parameter** | **Typ** | **Beskrivning**
--- | --- | ---
formula | java.lang.String | Cellernas dataintervallformel. T.ex.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5".
### getRange() {#getRange--}
```
public abstract String getRange()
```

Hämtar diagrammets dataintervall.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Returnerar:**
java.lang.String - Cellernas dataintervallformel. T.ex.: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Representerar datakällan för diagrammet

**Returnerar:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Representerar sökvägen till extern arbetsbok om datakällan är extern, annars null

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

Byter data över axeln. Data som diagrammas på X-axeln kommer att flyttas till Y-axeln och vice versa.
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Anger extern arbetsbok som datakälla för diagrammet. Diagramdata kommer att uppdateras från den angivna arbetsboken.

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

**Parameter** | **Typ** | **Beskrivning**
--- | --- | ---
workbookPath | java.lang.String | Sökväg till målarbetsboken
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Anger extern arbetsbok som datakälla för diagrammet.

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

**Parameter** | **Typ** | **Beskrivning**
--- | --- | ---
workbookPath | java.lang.String | Sökväg till målarbetsboken
updateChartData | boolean | Om värdet är falskt uppdateras endast arbetsbokens sökväg. Diagramdata kommer inte att läsas in och uppdateras från målarbetsboken. Kan användas när målarbetsboken inte finns eller inte är tillgänglig. Om värdet är sant uppdateras diagramdata från målarboken.