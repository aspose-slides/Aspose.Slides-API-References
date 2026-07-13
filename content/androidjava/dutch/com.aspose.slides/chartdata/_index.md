---
title: ChartData
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt de gegevens voor die worden gebruikt bij het plotten van een diagram.
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

Stelt de gegevens voor die worden gebruikt bij het plotten van een diagram.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Haalt de cellenfabriek op om cellen te maken die worden gebruikt voor diagramreeksen of -categorieën. |
| [getSeries()](#getSeries--) | Haalt de reeksen op. |
| [getSeriesGroups()](#getSeriesGroups--) | Haalt de groepen van reeksen op. |
| [getCategories()](#getCategories--) | Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) eigenschap false is). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Als false, dan retourneert #getSecondaryCategories.getSecondaryCategories null en worden de gegevens in #getCategories.getCategories zowel voor primaire als secundaire reeksen gebruikt. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Als false, dan retourneert #getSecondaryCategories.getSecondaryCategories null en worden de gegevens in #getCategories.getCategories zowel voor primaire als secundaire reeksen gebruikt. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Haalt de secundaire categorieën op als de eigenschap #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) true is. |
| [readWorkbookStream()](#readWorkbookStream--) | Schrijft de intern ingesloten Excel-werkmap naar een in-memory stream. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialiseert de intern ingesloten Excel-werkmap met een door de gebruiker opgegeven waarde. |
| [getDataSourceType()](#getDataSourceType--) | Stelt het pad naar een extern werkboek voor als externe gegevensbron, anders null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Stelt de gegevensbron van het diagram voor. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Haalt het type van het ingesloten werkboek op. |
| [getRange()](#getRange--) | Haalt diagramgegevensbereik op. |
| [setRange(String formula)](#setRange-java.lang.String-) | Stelt diagramgegevensbereik in. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Stelt een extern werkboek in als gegevensbron voor het diagram. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Stelt een extern werkboek in als gegevensbron voor het diagram. |
| [switchRowColumn()](#switchRowColumn--) | Wissel de gegevens over de as. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Haalt de cellenfabriek op om cellen te maken die worden gebruikt voor diagramreeksen of -categorieën. Alleen-lezen [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Retourneert:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Haalt de reeksen op. Alleen-lezen [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Retourneert:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Haalt de groepen van reeksen op. Alleen-lezen [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Elke groep van reeksen bevat reeksen met combineerbare typen. Groepen van combineerbare reekstypen zijn gedefinieerd en beschreven met de enum CombinableSeriesTypesGroup. Ook bevat elke groep van reeksen reeksen die worden geplot op de primaire of secundaire assen (niet beide omstandigheden in één groep). Dus is het principe van reeksgroepering een groepering op typegroepen zoals hierboven genoemd en op primaire/secundaire plottype. 2) Een groep van reeksen bevat enkele reekseigenschappen die gemeenschappelijk zijn voor elke reeks in de groep (“reeks groepeigenschappen”). “Reeks groepeigenschappen” in de klasse ChartSeriesGroup is lees/schrijf. Elke “reeks groepeigenschappen” kan een alleen-lezen projectie hebben in de klasse ChartSeries.

**Retourneert:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als de eigenschap #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) false is). Alleen-lezen [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Als #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) eigenschap false is, dan retourneert de eigenschap (#getSecondaryCategories.getSecondaryCategories) null en worden de gegevens in deze #getCategories.getCategories eigenschap zowel voor primaire als secundaire reeksen gebruikt. Als de eigenschap true is, worden de gegevens in de eigenschap (#getSecondaryCategories.getSecondaryCategories) gebruikt voor secundaire reeksen en de gegevens in deze #getCategories.getCategories eigenschap voor primaire reeksen.

**Retourneert:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Als false, dan retourneert #getSecondaryCategories.getSecondaryCategories null en worden de gegevens in #getCategories.getCategories zowel voor primaire als secundaire reeksen gebruikt. Als true, dan worden de gegevens in #getSecondaryCategories.getSecondaryCategories gebruikt voor secundaire reeksen en de gegevens in #getCategories.getCategories voor primaire reeksen. Lees/schrijf boolean.

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

**Retourneert:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Als false, dan retourneert #getSecondaryCategories.getSecondaryCategories null en worden de gegevens in #getCategories.getCategories zowel voor primaire als secundaire reeksen gebruikt. Als true, dan worden de gegevens in #getSecondaryCategories.getSecondaryCategories gebruikt voor secundaire reeksen en de gegevens in #getCategories.getCategories voor primaire reeksen. Lees/schrijf boolean.

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

Haalt de secundaire categorieën op als de eigenschap #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) true is. Alleen-lezen [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Als #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) eigenschap false is, dan retourneert deze eigenschap (#getSecondaryCategories.getSecondaryCategories) null en worden de gegevens in #getCategories.getCategories zowel voor primaire als secundaire reeksen gebruikt. Als de eigenschap true is, worden de gegevens in deze #getSecondaryCategories.getSecondaryCategories eigenschap gebruikt voor secundaire reeksen en de gegevens in #getCategories.getCategories eigenschap voor primaire reeksen.

**Retourneert:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Schrijft de intern ingesloten Excel-werkmap naar een in-memory stream.

**Retourneert:**
byte[] - Retourneert een instantie van een byte-array die een kopie van de intern ingesloten Excel-werkmap bevat.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Initialiseert de intern ingesloten Excel-werkmap met een door de gebruiker opgegeven waarde.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ms | byte[] | De door de gebruiker geleverde stream die de volledige Excel-werkmap bevat. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Stelt het pad naar een extern werkboek voor als externe gegevensbron, anders null.

**Retourneert:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Stelt de gegevensbron van het diagram voor.

**Retourneert:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Haalt het type van het ingesloten werkboek op. Retourneert [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) als DataSourceType (#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) is. Alleen-lezen [WorkbookType](../../com.aspose.slides/workbooktype).

**Retourneert:**
int

### getRange() {#getRange--}
```
public final String getRange()
```

Haalt diagramgegevensbereik op.

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

**Retourneert:**
java.lang.String - Formule voor celgegevensbereik. Bijv: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Stelt het diagramgegevensbereik in. Reeksen en categorieën worden bijgewerkt op basis van het nieuwe gegevensbereik. Als het aantal reeksen in het gegevensbereik groter is dan het aantal reeksen in de diagramgegevens, dan worden extra reeksen met hetzelfde type als de laatste reeks in de huidige collectie aan het einde van de collectie toegevoegd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| formula | java.lang.String | De formule voor het celgegevensbereik. Bijv: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Stelt een extern werkboek in als gegevensbron voor het diagram. Diagramgegevens worden bijgewerkt vanuit het doelwerkboek.

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
| workbookPath | java.lang.String | Pad naar het doelwerkboek |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Stelt een extern werkboek in als gegevensbron voor het diagram.

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
| workbookPath | java.lang.String | Pad naar het doelwerkboek |
| updateChartData | boolean | Als de waarde false is, wordt alleen het pad naar het werkboek bijgewerkt. Diagramgegevens worden niet geladen en bijgewerkt vanuit het doelwerkboek. Kan worden gebruikt wanneer het doelwerkboek niet bestaat of niet beschikbaar is. Als de waarde true is, worden diagramgegevens bijgewerkt vanuit het doelwerkboek. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Wissel de gegevens over de as. Gegevens die op de X-as worden weergegeven, worden verplaatst naar de Y-as en omgekeerd.