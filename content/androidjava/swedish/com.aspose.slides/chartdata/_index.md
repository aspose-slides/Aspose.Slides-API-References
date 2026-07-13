---
title: ChartData
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar data som används för att plotta ett diagram.
type: docs
url: /sv/com.aspose.slides/chartdata/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Representerar data som används för att plotta ett diagram.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Hämtar cellfabriken för att skapa celler som används för diagramserier eller kategorier. |
| [getSeries()](#getSeries--) | Hämtar serierna. |
| [getSeriesGroups()](#getSeriesGroups--) | Hämtar grupperna av serier. |
| [getCategories()](#getCategories--) | Hämtar de primära kategorierna (eller både primära och sekundära kategorier om \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) egenskap är falsk). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Om falskt så returnerar \#getSecondaryCategories.getSecondaryCategories egenskap null och data i \#getCategories.getCategories egenskap används både för primära och sekundära serier. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Om falskt så returnerar \#getSecondaryCategories.getSecondaryCategories egenskap null och data i \#getCategories.getCategories egenskap används både för primära och sekundära serier. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Hämtar de sekundära kategorierna om \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) egenskap är sann. |
| [readWorkbookStream()](#readWorkbookStream--) | Skriver den internt innehållna Excel-arbetsboken till ett minnesström. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initierar den internt innehållna Excel-arbetsboken med ett användarspecificerat värde. |
| [getDataSourceType()](#getDataSourceType--) | Representerar sökvägen till extern arbetsbok om extern datakälla, annars null |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Representerar datakällan för diagrammet |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Hämtar typen av den inbäddade arbetsboken. |
| [getRange()](#getRange--) | Hämtar diagrammets dataintervall. |
| [setRange(String formula)](#setRange-java.lang.String-) | Sätt diagrammets dataintervall. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Ställer in extern arbetsbok som datakälla för diagrammet. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Ställer in extern arbetsbok som datakälla för diagrammet. |
| [switchRowColumn()](#switchRowColumn--) | Byt data över axeln. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Hämtar cellfabriken för att skapa celler som används för diagramserier eller kategorier. Skrivskyddad [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Returnerar:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Hämtar serierna. Skrivskyddad [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Returnerar:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Hämtar grupperna av serier. Skrivskyddad [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Varje grupp av serier innehåller serier med kombinerbara typer. Grupper av kombinerbara serietyper definieras och beskrivs med enumen CombinableSeriesTypesGroup. Dessutom innehåller varje grupp serier som plottas antingen på primära eller sekundära axlar (inte båda i samma grupp). Så principen för seriegroupering är en gruppering efter typgrupperna ovan och efter primär/sekundär plottningstyp. 2) En grupp av serier innehåller vissa serieegenskaper som är gemensamma för varje serie i gruppen ("seriegruppsegenskaper"). "Seriegruppsegenskaper" i klassen ChartSeriesGroup är läs/skriv. Varje av "seriegruppsegenskaper" kan ha en skrivskyddad projektion i klassen ChartSeries.

**Returnerar:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Hämtar de primära kategorierna (eller både primära och sekundära kategorier om \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) egenskap är falsk). Skrivskyddad [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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
```

--------------------

Om \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) egenskap är falsk så (\#getSecondaryCategories.getSecondaryCategories) egenskap returnerar null och data i denna \#getCategories.getCategories egenskap används både för primära och sekundära serier. Om \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) egenskap är sann så data i (\#getSecondaryCategories.getSecondaryCategories) egenskap används för sekundära serier och data i denna \#getCategories.getCategories egenskap används för primära serier.

**Returnerar:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Om falskt så \#getSecondaryCategories.getSecondaryCategories egenskap returnerar null och data i \#getCategories.getCategories egenskap används både för primära och sekundära serier. Om sant så används data i \#getSecondaryCategories.getSecondaryCategories egenskap för sekundära serier och data i \#getCategories.getCategories egenskap för primära serier. Läs/skriv boolean.

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
public final void setUseSecondaryCategories(boolean value)
```

Om falskt så \#getSecondaryCategories.getSecondaryCategories egenskap returnerar null och data i \#getCategories.getCategories egenskap används både för primära och sekundära serier. Om sant så används data i \#getSecondaryCategories.getSecondaryCategories egenskap för sekundära serier och data i \#getCategories.getCategories egenskap för primära serier. Läs/skriv boolean.

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
public final IChartCategoryCollection getSecondaryCategories()
```

Hämtar de sekundära kategorierna om \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) egenskap är sann. Skrivskyddad [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Om \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) egenskap är falsk så denna (\#getSecondaryCategories.getSecondaryCategories) egenskap returnerar null och data i \#getCategories.getCategories egenskap används både för primära och sekundära serier. Om \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) egenskap är sann så data i denna \#getSecondaryCategories.getSecondaryCategories egenskap används för sekundära serier och data i \#getCategories.getCategories egenskap används för primära serier.

**Returnerar:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Skriver den internt innehållna Excel-arbetsboken till ett minnesström.

**Returnerar:**
byte[] - Returnerar en bytearray som innehåller en kopia av den internt innehållna Excel-arbetsboken.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Initierar den internt innehållna Excel-arbetsboken med ett användarspecificerat värde.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ms | byte[] | Den användar-tillhandahållna strömmen som innehåller hela Excel-arbetsboken. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Representerar sökvägen till extern arbetsbok om extern datakälla, annars null

**Returnerar:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Representerar datakällan för diagrammet

**Returnerar:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Hämtar typen av den inbäddade arbetsboken. Returnerar [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) om DataSourceType (\#getDataSourceType.getDataSourceType) är [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Skrivskyddad [WorkbookType](../../com.aspose.slides/workbooktype).

**Returnerar:**
int
### getRange() {#getRange--}
```
public final String getRange()
```

Hämtar diagrammets dataintervall.

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


**Returnerar:**
java.lang.String - Cells data range formula. E.g: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Sätt diagrammets dataintervall. Serier och kategorier uppdateras baserat på det nya intervallet. Om antalet serier i intervallet är större än antalet serier i diagrammets data läggs ytterligare serier med samma typ som den sista serien i den aktuella samlingen till i slutet av samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formula | java.lang.String | Formeln för cellernas dataintervall. E.g: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Ställer in extern arbetsbok som datakälla för diagrammet. Diagramdata uppdateras från målarbetsboken.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| workbookPath | java.lang.String | Sökväg till målarbetsboken |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Ställer in extern arbetsbok som datakälla för diagrammet.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| workbookPath | java.lang.String | Sökväg till målarbetsboken |
| updateChartData | boolean | Om värdet är falskt uppdateras endast arbetsbokens sökväg. Diagramdata laddas inte och uppdateras inte från målarboken. Kan användas när målarboken inte finns eller inte är tillgänglig. Om värdet är sant uppdateras diagramdata från målarboken. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Byt data över axeln. Data som plottas på X-axeln flyttas till Y-axeln och vice-versa.