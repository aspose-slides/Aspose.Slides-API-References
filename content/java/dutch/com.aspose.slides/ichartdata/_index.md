---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Stelt gegevens voor die worden gebruikt voor het plotten van een diagram.
type: docs
url: /nl/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Stelt gegevens voor die worden gebruikt voor het plotten van een diagram.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Haalt de cellenfabriek op om cellen te maken die worden gebruikt voor diagramreeksen of categorieën. |
| [getSeries()](#getSeries--) | Haalt de reeksen op. |
| [getSeriesGroups()](#getSeriesGroups--) | Haalt de groepen van reeksen op. |
| [getCategories()](#getCategories--) | Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als de eigenschap (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false is). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Als false, dan retourneert de eigenschap (\#getSecondaryCategories.getSecondaryCategories) null en worden de gegevens in de eigenschap (\#getCategories.getCategories) zowel voor primaire als secundaire reeksen gebruikt. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Als false, dan retourneert de eigenschap (\#getSecondaryCategories.getSecondaryCategories) null en worden de gegevens in de eigenschap (\#getCategories.getCategories) zowel voor primaire als secundaire reeksen gebruikt. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Haalt de secundaire categorieën op als de eigenschap (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true is. |
| [readWorkbookStream()](#readWorkbookStream--) | Schrijft de intern opgenomen Excel-werkmap naar een in-memory stream. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialiseert de intern opgenomen Excel-werkmap met een door de gebruiker opgegeven waarde. |
| [setRange(String formula)](#setRange-java.lang.String-) | Stelt het gegevensbereik van het diagram in. |
| [getRange()](#getRange--) | Haalt het gegevensbereik van het diagram op. |
| [getDataSourceType()](#getDataSourceType--) | Stelt de gegevensbron van het diagram voor |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Stelt het pad naar een extern werkmap voor als de gegevensbron extern is, anders null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Haalt het type van de ingebedde werkmap op. |
| [switchRowColumn()](#switchRowColumn--) | Wisselt de gegevens over de as. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Stelt extern werkmap in als gegevensbron voor het diagram. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Stelt extern werkmap in als gegevensbron voor het diagram. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Haalt de cellenfabriek op om cellen te maken die worden gebruikt voor diagramreeksen of categorieën. Alleen-lezen [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Retour:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Haalt de reeksen op. Alleen-lezen [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Retour:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Haalt de groepen van reeksen op. Alleen-lezen [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

1) Elke groep van reeksen bevat reeksen met combineerbare types. Groepen van combineerbare serietypes worden gedefinieerd en beschreven met de enum CombinableSeriesTypesGroup. Ook bevat elke groep van reeksen reeksen die worden geplot op de primaire assen of op de secundaire assen (niet beide gevallen in één groep). Dus het principe van groepsvorming van reeksen is een groepering op basis van de hierboven genoemde typegroepen en op primaire/secundaire plottype. 2) Een groep van reeksen bevat enkele seriekeigenschappen die gemeenschappelijk zijn voor elke reeks in de groep ("series group properties"). "Series group properties" in de klasse ChartSeriesGroup is lezen/schrijven. Elk van de "series group properties" kan een alleen-lezen projectie hebben in de klasse ChartSeries.

**Retour:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als de eigenschap (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false is). Alleen-lezen [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Als (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false is, dan retourneert de eigenschap (\#getSecondaryCategories.getSecondaryCategories) null en worden de gegevens in deze (\#getCategories.getCategories) eigenschap zowel voor primaire als secundaire reeksen gebruikt. Als (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true is, dan worden de gegevens in de eigenschap (\#getSecondaryCategories.getSecondaryCategories) gebruikt voor secundaire reeksen en de gegevens in deze (\#getCategories.getCategories) eigenschap voor primaire reeksen.

**Retour:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Als false dan retourneert de eigenschap (\#getSecondaryCategories.getSecondaryCategories) null en worden de gegevens in de eigenschap (\#getCategories.getCategories) zowel voor primaire als secundaire reeksen gebruikt. Als true dan worden de gegevens in de eigenschap (\#getSecondaryCategories.getSecondaryCategories) gebruikt voor secundaire reeksen en de gegevens in de eigenschap (\#getCategories.getCategories) voor primaire reeksen. Lezen/schrijven boolean.

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

Als false dan retourneert de eigenschap (\#getSecondaryCategories.getSecondaryCategories) null en worden de gegevens in de eigenschap (\#getCategories.getCategories) zowel voor primaire als secundaire reeksen gebruikt. Als true dan worden de gegevens in de eigenschap (\#getSecondaryCategories.getSecondaryCategories) gebruikt voor secundaire reeksen en de gegevens in de eigenschap (\#getCategories.getCategories) voor primaire reeksen. Lezen/schrijven boolean.

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
| waarde | boolean |  |

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

Als (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false is, dan retourneert deze (\#getSecondaryCategories.getSecondaryCategories) eigenschap null en worden de gegevens in de eigenschap (\#getCategories.getCategories) zowel voor primaire als secundaire reeksen gebruikt. Als (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true is, dan worden de gegevens in deze (\#getSecondaryCategories.getSecondaryCategories) eigenschap gebruikt voor secundaire reeksen en de gegevens in de eigenschap (\#getCategories.getCategories) voor primaire reeksen.

**Retour:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Schrijft de intern opgenomen Excel-werkmap naar een in-memory stream.

**Retour:**
byte[] - Retourneert een byte-array die een kopie bevat van de intern opgenomen Excel-werkmap.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Initialiseert de intern opgenomen Excel-werkmap met een door de gebruiker opgegeven waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ms | byte[] | De door de gebruiker aangeleverde stream die de volledige Excel-werkmap bevat. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Stelt het gegevensbereik van het diagram in. Reeksen en categorieën worden bijgewerkt op basis van het nieuwe gegevensbereik. Als het aantal reeksen in het gegevensbereik groter is dan het aantal reeksen in de diagramgegevens, dan worden extra reeksen met hetzelfde type als de laatste reeks in de huidige collectie aan het einde van de collectie toegevoegd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| formula | java.lang.String | De formule voor het cellen-gegevensbereik. Bijv: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

Haalt het gegevensbereik van het diagram op.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Retour:**
java.lang.String - Formule voor het cellen-gegevensbereik. Bijv: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Stelt de gegevensbron van het diagram voor

**Retour:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Stelt het pad naar een extern werkmap voor als de gegevensbron extern is, anders null

**Retour:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Haalt het type van de ingebedde werkmap op. Retourneert [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) als DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) is. Alleen-lezen [WorkbookType](../../com.aspose.slides/workbooktype).

**Retour:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Wisselt de gegevens over de as. Gegevens die op de X-as worden weergegeven, verplaatsen naar de Y-as en omgekeerd.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Stelt extern werkmap in als gegevensbron voor het diagram. Diagramgegevens worden bijgewerkt vanuit het doelwerkmap.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| workbookPath | java.lang.String | Pad naar het doelwerkmap |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Stelt extern werkmap in als gegevensbron voor het diagram.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| workbookPath | java.lang.String | Pad naar het doelwerkmap |
| updateChartData | boolean | Als de waarde false is, wordt alleen het pad naar het werkmap bijgewerkt. Diagramgegevens worden niet geladen en bijgewerkt vanuit het doelwerkmap. Kan worden gebruikt wanneer het doelwerkmap niet bestaat of niet beschikbaar is. Als de waarde true is, worden diagramgegevens bijgewerkt vanuit het doelwerkmap. |