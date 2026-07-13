---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Vertegenwoordigt gegevens die worden gebruikt voor het plotten van een diagram.
type: docs
url: /nl/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Vertegenwoordigt gegevens die worden gebruikt voor het plotten van een diagram.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Haalt de cellen-factory op om cellen te maken die worden gebruikt voor grafiekreeksen of -categorieën. |
| [getSeries()](#getSeries--) | Haalt de reeksen op. |
| [getSeriesGroups()](#getSeriesGroups--) | Haalt de groepen van reeksen op. |
| [getCategories()](#getCategories--) | Haalt de primaire categorieën op (of zowel primaire als secundaire categorieën als (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) eigenschap false is). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Als false, dan retourneert de (\#getSecondaryCategories.getSecondaryCategories) eigenschap null en worden de gegevens in de (\#getCategories.getCategories) eigenschap gebruikt voor zowel primaire als secundaire series. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Als false, dan retourneert de (\#getSecondaryCategories.getSecondaryCategories) eigenschap null en worden de gegevens in de (\#getCategories.getCategories) eigenschap gebruikt voor zowel primaire als secundaire series. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Haalt de secundaire categorieën op als de (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) eigenschap true is. |
| [readWorkbookStream()](#readWorkbookStream--) | Schrijft de intern opgenomen Excel-werkmap naar een in-memory stream. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialiseert de intern opgenomen Excel-werkmap met een door de gebruiker opgegeven waarde. |
| [setRange(String formula)](#setRange-java.lang.String-) | Stel het gegevensbereik van de grafiek in. |
| [getRange()](#getRange--) | Haalt het gegevensbereik van de grafiek op. |
| [getDataSourceType()](#getDataSourceType--) | Vertegenwoordigt de gegevensbron van de grafiek. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Vertegenwoordigt het pad naar de externe werkmap als de gegevensbron extern is, anders null. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Haalt het type van de ingesloten werkmap op. |
| [switchRowColumn()](#switchRowColumn--) | Wissel de gegevens over de as. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Stelt een externe werkmap in als gegevensbron voor de grafiek. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Stelt een externe werkmap in als gegevensbron voor de grafiek. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Haalt de cellen-factory op om cellen te maken die worden gebruikt voor grafiekreeksen of -categorieën. Alleen-lezen [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

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

1) Elke groep van reeksen bevat reeksen met combineerbare typen. Groepen van combineerbare serietypen worden gedefinieerd en beschreven met de CombinableSeriesTypesGroup enum. Ook bevat elke groep van reeksen reeksen die worden weergegeven op de primaire assen of op de secundaire assen (niet beide gevallen in één groep). Dus, het principe van het groeperen van reeksen is een groepering op basis van bovengenoemde typegroepen en op type van weergave op primaire/secundaire assen.

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

Als de (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) eigenschap false is, dan geeft de (\#getSecondaryCategories.getSecondaryCategories) eigenschap null terug en worden de gegevens in deze (\#getCategories.getCategories) eigenschap gebruikt voor zowel primaire als secundaire series. Als de (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) eigenschap true is, dan worden de gegevens in de (\#getSecondaryCategories.getSecondaryCategories) eigenschap gebruikt voor secundaire series en de gegevens in deze (\#getCategories.getCategories) eigenschap voor primaire series.

**Retour:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Als false, dan geeft de (\#getSecondaryCategories.getSecondaryCategories) eigenschap null terug en worden de gegevens in de (\#getCategories.getCategories) eigenschap gebruikt voor zowel primaire als secundaire series. Als true, dan worden de gegevens in de (\#getSecondaryCategories.getSecondaryCategories) eigenschap gebruikt voor secundaire series en de gegevens in de (\#getCategories.getCategories) eigenschap voor primaire series. Lezen/Schrijven boolean.

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

Als false, dan geeft de (\#getSecondaryCategories.getSecondaryCategories) eigenschap null terug en worden de gegevens in de (\#getCategories.getCategories) eigenschap gebruikt voor zowel primaire als secundaire series. Als true, dan worden de gegevens in de (\#getSecondaryCategories.getSecondaryCategories) eigenschap gebruikt voor secundaire series en de gegevens in de (\#getCategories.getCategories) eigenschap voor primaire series. Lezen/Schrijven boolean.

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
public abstract IChartCategoryCollection getSecondaryCategories()
```

Haalt de secundaire categorieën op als de (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) eigenschap true is. Alleen-lezen [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Als de (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) eigenschap false is, dan geeft deze (\#getSecondaryCategories.getSecondaryCategories) eigenschap null terug en worden de gegevens in de (\#getCategories.getCategories) eigenschap gebruikt voor zowel primaire als secundaire series. Als de (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) eigenschap true is, dan worden de gegevens in deze (\#getSecondaryCategories.getSecondaryCategories) eigenschap gebruikt voor secundaire series en de gegevens in deze (\#getCategories.getCategories) eigenschap voor primaire series.

**Retour:**  
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Schrijft de intern opgenomen Excel-werkmap naar een in-memory stream.

**Retour:**  
byte[] - Retourneert een byte-array die een kopie van de intern opgenomen Excel-werkmap bevat.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Initialiseert de intern opgenomen Excel-werkmap met een door de gebruiker opgegeven waarde.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| ms | byte[] | De door de gebruiker geleverde stream die de volledige Excel-werkmap bevat. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Stel het gegevensbereik van de grafiek in. Reeksen en categorieën worden bijgewerkt op basis van het nieuwe gegevensbereik. Als het aantal reeksen in het gegevensbereik groter is dan het aantal reeksen in de grafiekgegevens, dan worden extra reeksen met hetzelfde type als de laatste reeks in de huidige collectie toegevoegd aan het einde van de collectie.

**Parameters:**  
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| formula | java.lang.String | De formule voor het gegevensbereik van de cellen. Bijv: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

Haalt het gegevensbereik van de grafiek op.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```


**Retour:**  
java.lang.String - Formule voor het gegevensbereik van de cellen. Bijv: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Vertegenwoordigt de gegevensbron van de grafiek

**Retour:**  
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Vertegenwoordigt het pad naar de externe werkmap als de gegevensbron extern is, anders null

**Retour:**  
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Haalt het type van de ingesloten werkmap op. Retourneert [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) als DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) is. Alleen-lezen [WorkbookType](../../com.aspose.slides/workbooktype).

**Retour:**  
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Wissel de gegevens over de as. Gegevens die op de X-as worden weergegeven, verplaatsen zich naar de Y-as en omgekeerd.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Stelt een externe werkmap in als gegevensbron voor de grafiek. Grafiekgegevens worden bijgewerkt vanuit de doelwerkmap.

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
| workbookPath | java.lang.String | Pad naar de doelwerkmap |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Stelt een externe werkmap in als gegevensbron voor de grafiek.

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
| workbookPath | java.lang.String | Pad naar de doelwerkmap |
| updateChartData | boolean | Als de waarde false is, wordt alleen het pad naar de werkmap bijgewerkt. Grafiekgegevens worden niet geladen en bijgewerkt vanuit de doelwerkmap. Kan worden gebruikt wanneer de doelwerkmap niet bestaat of niet beschikbaar is. Als de waarde true is, worden de grafiekgegevens bijgewerkt vanuit de doelwerkmap. |