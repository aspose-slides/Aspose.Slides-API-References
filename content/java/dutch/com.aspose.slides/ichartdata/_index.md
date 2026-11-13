---
title: IChartData
second_title: Aspose.Slides voor Java API Referentie
description: Stelt de gegevens voor die worden gebruikt voor het plotten van een grafiek.
type: docs
url: /nl/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Stelt de gegevens voor die worden gebruikt voor het plotten van een grafiek.
## Methoden

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Haalt de cellenfabriek op om cellen te maken die worden gebruikt voor grafiekseries of -categorieën. |
| [getSeries()](#getSeries--) | Haalt de series op. |
| [getSeriesGroups()](#getSeriesGroups--) | Haalt de groepen van series op. |
| [getCategories()](#getCategories--) | Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) eigenschap false is). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Als false, dan geeft de eigenschap (\#getSecondaryCategories.getSecondaryCategories) null terug en worden de gegevens in eigenschap (\#getCategories.getCategories) zowel voor primaire als secundaire series gebruikt. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Als false, dan geeft de eigenschap (\#getSecondaryCategories.getSecondaryCategories) null terug en worden de gegevens in eigenschap (\#getCategories.getCategories) zowel voor primaire als secundaire series gebruikt. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Haalt de secundaire categorieën op als de eigenschap (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true is. |
| [readWorkbookStream()](#readWorkbookStream--) | Schrijft de intern opgenomen Excel-werkmap naar een geheugenstroom. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialiseert de intern opgenomen Excel-werkmap met door de gebruiker opgegeven waarde. |
| [setRange(String formula)](#setRange-java.lang.String-) | Stel grafiekgegevensbereik in. |
| [getRange()](#getRange--) | Haalt het grafiekgegevensbereik op. |
| [getDataSourceType()](#getDataSourceType--) | Vertegenwoordigt gegevensbron van de grafiek |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Vertegenwoordigt pad naar extern werkboek als de gegevensbron extern is, anders null. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Haalt het type van het ingesloten werkboek op. |
| [switchRowColumn()](#switchRowColumn--) | Wissel de gegevens over de as. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Stelt extern werkboek in als gegevensbron voor de grafiek. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Stelt extern werkboek in als gegevensbron voor de grafiek. |
| [refreshData()](#refreshData--) | Ververs de grafiekgegevens door deze opnieuw te laden vanuit het bronwerkboek. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Haalt de cellenfabriek op om cellen te maken die worden gebruikt voor grafiekseries of -categorieën. Alleen-lezen [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Retour:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Haalt de series op. Alleen-lezen [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Retour:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Haalt de groepen van series op. Alleen-lezen [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Elke groep van series bevat series met combinerenbare types. Groepen van combinerenbare seriestypes worden gedefinieerd en beschreven met de enum CombinableSeriesTypesGroup. Ook bevat elke groep van series series die worden geplot op de primaire assen of op de secundaire assen (niet beide gevallen in één groep). Dus het principe van seriesgroepering is een groepering volgens de bovengenoemde typegroepen en volgens het type plotten primair/secundair. 2) Een groep van series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep (“series group properties”). “Series group properties” in de class ChartSeriesGroup is lezen/schrijven. Elke “series group property” kan een alleen-lezen projectie hebben in de class ChartSeries.

**Retour:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) eigenschap false is). Alleen-lezen [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // gerelateerde categorieën zijn series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // gerelateerde categorieën zijn series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Als de eigenschap (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false is, dan geeft de eigenschap (\#getSecondaryCategories.getSecondaryCategories) null terug en worden de gegevens in deze eigenschap (\#getCategories.getCategories) zowel voor primaire als secundaire series gebruikt. Als de eigenschap (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true is, dan worden de gegevens in eigenschap (\#getSecondaryCategories.getSecondaryCategories) gebruikt voor secundaire series en worden de gegevens in deze eigenschap (\#getCategories.getCategories) gebruikt voor primaire series.

**Retour:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Als false, dan geeft de eigenschap (\#getSecondaryCategories.getSecondaryCategories) null terug en worden de gegevens in eigenschap (\#getCategories.getCategories) zowel voor primaire als secundaire series gebruikt. Als true, dan worden de gegevens in eigenschap (\#getSecondaryCategories.getSecondaryCategories) gebruikt voor secundaire series en worden de gegevens in eigenschap (\#getCategories.getCategories) gebruikt voor primaire series. Lezen/schrijven boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // gerelateerde categorieën zijn series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // gerelateerde categorieën zijn series.getChart().getChartData().getCategories()
>  }
> ```

**Retour:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

Als false, dan geeft de eigenschap (\#getSecondaryCategories.getSecondaryCategories) null terug en worden de gegevens in eigenschap (\#getCategories.getCategories) zowel voor primaire als secundaire series gebruikt. Als true, dan worden de gegevens in eigenschap (\#getSecondaryCategories.getSecondaryCategories) gebruikt voor secundaire series en worden de gegevens in eigenschap (\#getCategories.getCategories) gebruikt voor primaire series. Lezen/schrijven boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // gerelateerde categorieën zijn series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // gerelateerde categorieën zijn series.getChart().getChartData().getCategories()
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

Haalt de secundaire categorieën op als de eigenschap (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true is. Alleen-lezen [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // gerelateerde categorieën zijn series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // gerelateerde categorieën zijn series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Als de eigenschap (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false is, dan geeft deze eigenschap (\#getSecondaryCategories.getSecondaryCategories) null terug en worden de gegevens in eigenschap (\#getCategories.getCategories) zowel voor primaire als secundaire series gebruikt. Als de eigenschap (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true is, dan worden de gegevens in deze eigenschap (\#getSecondaryCategories.getSecondaryCategories) gebruikt voor secundaire series en worden de gegevens in eigenschap (\#getCategories.getCategories) gebruikt voor primaire series.

**Retour:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Schrijft de intern opgenomen Excel-werkmap naar een geheugenstroom.

**Retour:**
byte[] - Retourneert een byte-array die een kopie van de intern opgenomen Excel-werkmap bevat.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Initialiseert de intern opgenomen Excel-werkmap met door de gebruiker opgegeven waarde.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | De door de gebruiker geleverde stroom die de volledige Excel-werkmap bevat. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Stel het grafiekgegevensbereik in. Series en categorieën worden bijgewerkt op basis van het nieuwe bereik. Als het aantal series in het gegevensbereik groter is dan het aantal series in de grafiekgegevens, dan worden extra series met hetzelfde type als de laatste serie in de huidige collectie aan het einde van de collectie toegevoegd.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | De formule van het cellen-gegevensbereik. Bijv: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

Haalt het grafiekgegevensbereik op.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Retour:**
java.lang.String - Formule van het cellen-gegevensbereik. Bijv: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Vertegenwoordigt gegevensbron van de grafiek

**Retour:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Vertegenwoordigt pad naar extern werkboek als de gegevensbron extern is, anders null

**Retour:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Haalt het type van het ingesloten werkboek op. Retourneert [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) als DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) is. Alleen-lezen [WorkbookType](../../com.aspose.slides/workbooktype).

**Retour:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Wissel de gegevens over de as. Gegevens die op de X-as worden geplot, verplaatsen zich naar de Y-as en omgekeerd.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Stelt extern werkboek in als gegevensbron voor de grafiek. Grafiekgegevens worden bijgewerkt vanuit het doelwerkboek.

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
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Pad naar het doelwerkboek |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Stelt extern werkboek in als gegevensbron voor de grafiek.

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
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Pad naar het doelwerkboek |
| updateChartData | boolean | Als de waarde false is, wordt alleen het pad van het werkboek bijgewerkt. Grafiekgegevens worden niet geladen en bijgewerkt vanuit het doelwerkboek. Kan worden gebruikt wanneer het doelwerkboek niet bestaat of niet beschikbaar is. Als de waarde true is, worden grafiekgegevens bijgewerkt vanuit het doelwerkboek. |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```

Ververs de grafiekgegevens door deze opnieuw te laden vanuit het bronwerkboek.

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