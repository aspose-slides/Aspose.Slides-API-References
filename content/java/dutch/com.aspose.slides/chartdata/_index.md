---
title: ChartData
second_title: Aspose.Slides voor Java API-referentie
description: Stelt gegevens voor die worden gebruikt voor het plotten van een diagram.
type: docs
url: /nl/com.aspose.slides/chartdata/
---
**Erfenis:**
java.lang.Object, com.aspose.slides.DomObject

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Stelt gegevens voor die worden gebruikt voor het plotten van een diagram.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Haalt de cellenfabriek op om cellen te maken die worden gebruikt voor diagramreeksen of -categorieën. |
| [getSeries()](#getSeries--) | Haalt de series op. |
| [getSeriesGroups()](#getSeriesGroups--) | Haalt de groepen van series op. |
| [getCategories()](#getCategories--) | Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) eigenschap false is). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Als false dan \#getSecondaryCategories.getSecondaryCategories eigenschap null retourneert en gegevens in \#getCategories.getCategories eigenschap zowel voor primaire als secundaire series worden gebruikt. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Als false dan \#getSecondaryCategories.getSecondaryCategories eigenschap null retourneert en gegevens in \#getCategories.getCategories eigenschap zowel voor primaire als secundaire series worden gebruikt. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Haalt de secundaire categorieën op als \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) eigenschap true is. |
| [readWorkbookStream()](#readWorkbookStream--) | Schrijft de intern opgenomen Excel-werkmap naar een in-memorystream. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialiseert de intern opgenomen Excel-werkmap met een door de gebruiker opgegeven waarde. |
| [getDataSourceType()](#getDataSourceType--) | Stelt het externe werkmappad voor als externe gegevensbron, anders null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Stelt de gegevensbron van de grafiek voor. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Haalt het type van de ingesloten werkmap op. |
| [getRange()](#getRange--) | Haalt het gegevensbereik van de grafiek op. |
| [setRange(String formula)](#setRange-java.lang.String-) | Stelt het gegevensbereik van de grafiek in. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Stelt externe werkmap in als gegevensbron voor de grafiek. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Stelt externe werkmap in als gegevensbron voor de grafiek. |
| [refreshData()](#refreshData--) | Verversen de grafiekgegevens door ze opnieuw te laden vanuit de bronwerkmap. |
| [switchRowColumn()](#switchRowColumn--) | Wissel de gegevens over de as. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Haalt de cellenfabriek op om cellen te maken die worden gebruikt voor diagramreeksen of -categorieën. Alleen-lezen [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Retour:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Haalt de series op. Alleen-lezen [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Retour:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Haalt de groepen van series op. Alleen-lezen [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Elke groep van series bevat series met combineerbare typen. Groepen van combineerbare serietypen worden gedefinieerd en beschreven met de enum CombinableSeriesTypesGroup. Daarnaast bevat elke groep van series series die worden geplot op de primaire as of op de secundaire as (niet beide gevallen in één groep). Dus het principe van seriesgroepering is een groepering op basis van de hierboven genoemde typegroepen en op basis van primaire/secundaire plottype. 2) Een groep van series bevat enkele series-eigenschappen die gemeenschappelijk zijn voor elke serie in de groep ("series-groep-eigenschappen"). "Series-groep-eigenschappen" in de klasse ChartSeriesGroup zijn lees-/schrijfbaar. Elke "series-groep-eigenschap" kan een alleen-lezen weergave hebben in de klasse ChartSeries.

**Retour:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) eigenschap false is). Alleen-lezen [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Als \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) eigenschap false is, dan retourneert (\#getSecondaryCategories.getSecondaryCategories) eigenschap null en worden gegevens in deze \#getCategories.getCategories eigenschap zowel voor primaire als secundaire series gebruikt. Als \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) eigenschap true is, dan worden gegevens in (\#getSecondaryCategories.getSecondaryCategories) eigenschap gebruikt voor secundaire series en gegevens in deze \#getCategories.getCategories eigenschap voor primaire series.

**Retour:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Als false dan \#getSecondaryCategories.getSecondaryCategories eigenschap null retourneert en gegevens in \#getCategories.getCategories eigenschap zowel voor primaire als secundaire series worden gebruikt. Als true dan worden gegevens in \#getSecondaryCategories.getSecondaryCategories eigenschap gebruikt voor secundaire series en gegevens in \#getCategories.getCategories eigenschap voor primaire series. Lees/schrijf boolean.

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
public final void setUseSecondaryCategories(boolean value)
```

Als false dan \#getSecondaryCategories.getSecondaryCategories eigenschap null retourneert en gegevens in \#getCategories.getCategories eigenschap zowel voor primaire als secundaire series worden gebruikt. Als true dan worden gegevens in \#getSecondaryCategories.getSecondaryCategories eigenschap gebruikt voor secundaire series en gegevens in \#getCategories.getCategories eigenschap voor primaire series. Lees/schrijf boolean.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

Haalt de secundaire categorieën op als \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) eigenschap true is. Alleen-lezen [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Als \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) eigenschap false is, dan retourneert dit (\#getSecondaryCategories.getSecondaryCategories) eigenschap null en worden gegevens in \#getCategories.getCategories eigenschap zowel voor primaire als secundaire series gebruikt. Als \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) eigenschap true is, dan worden gegevens in dit (\#getSecondaryCategories.getSecondaryCategories) eigenschap gebruikt voor secundaire series en gegevens in \#getCategories.getCategories eigenschap voor primaire series.

**Retour:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Schrijft de intern opgenomen Excel-werkmap naar een in-memorystream.

**Retour:**
byte[] - Retourneert een instantie van een byte-array die een kopie van de intern opgenomen Excel-werkmap bevat.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Initialiseert de intern opgenomen Excel-werkmap met een door de gebruiker opgegeven waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ms | byte[] | De door de gebruiker geleverde stream die de volledige Excel-werkmap bevat. |
### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Stelt het externe werkmappad voor als externe gegevensbron, anders null.

**Retour:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Stelt de gegevensbron van de grafiek voor.

**Retour:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Haalt het type van de ingesloten werkmap op. Retourneert [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) als DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) is. Alleen-lezen [WorkbookType](../../com.aspose.slides/workbooktype).

**Retour:**
int
### getRange() {#getRange--}
```
public final String getRange()
```

Haalt het gegevensbereik van de grafiek op.

--------------------

> ```
> Presentation pres = new Presentation();
>   try {
>       IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 0, 0, 100, 100);
>       String result = ((ChartData)chart.getChartData()).getRange();
>   finally {
>       if (pres != null) pres.dispose();
>   }
> ```

**Retour:**
java.lang.String - Formule voor celgegevensbereik. Bijv: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Stelt het gegevensbereik van de grafiek in. Series en categorieën worden bijgewerkt op basis van het nieuwe gegevensbereik. Als het aantal series in het gegevensbereik groter is dan het aantal series in de grafiekgegevens, dan worden extra series met hetzelfde type als de laatste serie in de huidige collectie aan het einde van de collectie toegevoegd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| formula | java.lang.String | De formule voor het celgegevensbereik. Bijv: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Stelt externe werkmap in als gegevensbron voor de grafiek. Grafiekgegevens worden bijgewerkt vanuit de doelwerkmap.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| workbookPath | java.lang.String | Pad naar de doelwerkmap |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Stelt externe werkmap in als gegevensbron voor de grafiek.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| workbookPath | java.lang.String | Pad naar de doelwerkmap |
| updateChartData | boolean | Als de waarde false is, wordt alleen het pad naar de werkmap bijgewerkt. Grafiekgegevens worden niet geladen en bijgewerkt vanuit de doelwerkmap. Kan worden gebruikt wanneer de doelwerkmap niet bestaat of niet beschikbaar is. Als de waarde true is, worden de grafiekgegevens bijgewerkt vanuit de doelwerkmap. |
### refreshData() {#refreshData--}
```
public final void refreshData()
```

Verversen de grafiekgegevens door ze opnieuw te laden vanuit de bronwerkmap.

--------------------

> ```
> Presentation presentation = new Presentation("presentationWithChart.pptx");
>  try {
>      IChart chart = (IChart)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      chart.getChartData().refreshData();
>  } finally {
>      presentation.dispose();
>  }
> ```

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Wissel de gegevens over de as. Gegevens die op de X-as worden gevisualiseerd, worden verplaatst naar de Y-as en omgekeerd.