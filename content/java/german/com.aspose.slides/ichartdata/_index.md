---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Stellt Daten dar, die für die Diagrammerstellung verwendet werden.
type: docs
url: /de/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Stellt Daten dar, die für die Diagrammerstellung verwendet werden.

## Methoden

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Gibt die Zellenfabrik zurück, um Zellen zu erstellen, die für Diagrammreihen oder -kategorien verwendet werden. |
| [getSeries()](#getSeries--) | Gibt die Reihen zurück. |
| [getSeriesGroups()](#getSeriesGroups--) | Gibt die Gruppen von Reihen zurück. |
| [getCategories()](#getCategories--) | Gibt die primären Kategorien zurück (oder sowohl primäre als auch sekundäre Kategorien, wenn die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false ist). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Wenn false, gibt die Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in der Eigenschaft (\#getCategories.getCategories) werden sowohl für primäre als auch für sekundäre Reihen verwendet. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Wenn false, gibt die Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in der Eigenschaft (\#getCategories.getCategories) werden sowohl für primäre als auch für sekundäre Reihen verwendet. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Gibt die sekundären Kategorien zurück, wenn die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true ist. |
| [readWorkbookStream()](#readWorkbookStream--) | Schreibt die intern enthaltene Excel-Arbeitsmappe in einen Speicherstrom. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialisiert die intern enthaltene Excel-Arbeitsmappe mit dem vom Benutzer angegebenen Wert. |
| [setRange(String formula)](#setRange-java.lang.String-) | Legt den Datenbereich des Diagramms fest. |
| [getRange()](#getRange--) | Gibt den Datenbereich des Diagramms zurück. |
| [getDataSourceType()](#getDataSourceType--) | Stellt die Datenquelle des Diagramms dar |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Stellt den Pfad zu einer externen Arbeitsmappe dar, wenn die Datenquelle extern ist, andernfalls null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Gibt den Typ der eingebetteten Arbeitsmappe zurück. |
| [switchRowColumn()](#switchRowColumn--) | Vertauscht die Daten über die Achse. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Legt eine externe Arbeitsmappe als Datenquelle für das Diagramm fest. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Legt eine externe Arbeitsmappe als Datenquelle für das Diagramm fest. |
| [refreshData()](#refreshData--) | Aktualisiert die Diagrammdaten, indem sie aus der Quellarbeitsmappe neu geladen werden. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Gibt die Zellenfabrik zurück, um Zellen zu erstellen, die für Diagrammreihen oder -kategorien verwendet werden. Nur lesbar [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Rückgabe:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Gibt die Reihen zurück. Nur lesbar [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Rückgabe:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Gibt die Gruppen von Reihen zurück. Nur lesbar [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Jede Gruppe von Reihen enthält Reihen mit kombinierbaren Typen. Gruppen von kombinierbaren Reihen-Typen werden durch das Enum **CombinableSeriesTypesGroup** definiert und beschrieben. Außerdem enthält jede Gruppe von Reihen Reihen, die entweder auf den primären Achsen oder auf den sekundären Achsen geplottet werden (nicht beide Fälle in einer Gruppe). Das Prinzip der Reihen-Gruppierung ist also eine Gruppierung nach den oben genannten Typ-Gruppen und nach dem primären/sekundären Plot-Typ. 2) Eine Gruppe von Reihen enthält einige Reihen-Eigenschaften, die für jede Reihe in der Gruppe gemeinsam sind („series group properties“). „Series group properties“ in der Klasse **ChartSeriesGroup** sind les-/schreibbar. Jede der „series group properties“ kann eine nur lesbare Projektion in der Klasse **ChartSeries** haben.

**Rückgabe:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Gibt die primären Kategorien zurück (oder sowohl primäre als auch sekundäre Kategorien, wenn die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false ist). Nur lesbar [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // Zugehörige Kategorien sind series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // Zugehörige Kategorien sind series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Wenn die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false ist, gibt die Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in dieser Eigenschaft (\#getCategories.getCategories) werden sowohl für primäre als auch für sekundäre Reihen verwendet. Ist die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true, werden die Daten in der Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) für sekundäre Reihen und die Daten in dieser Eigenschaft (\#getCategories.getCategories) für primäre Reihen verwendet.

**Rückgabe:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Wenn false, gibt die Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in der Eigenschaft (\#getCategories.getCategories) werden sowohl für primäre als auch für sekundäre Reihen verwendet. Wenn true, werden die Daten in der Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) für sekundäre Reihen und die Daten in der Eigenschaft (\#getCategories.getCategories) für primäre Reihen verwendet. Lese/Schreibe-Boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // Zugehörige Kategorien sind series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // Zugehörige Kategorien sind series.getChart().getChartData().getCategories()
>  }
> ```

**Rückgabe:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

Wenn false, gibt die Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in der Eigenschaft (\#getCategories.getCategories) werden sowohl für primäre als auch für sekundäre Reihen verwendet. Wenn true, werden die Daten in der Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) für sekundäre Reihen und die Daten in der Eigenschaft (\#getCategories.getCategories) für primäre Reihen verwendet. Lese/Schreibe-Boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // Zugehörige Kategorien sind series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // Zugehörige Kategorien sind series.getChart().getChartData().getCategories()
>  }
> ```

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

Gibt die sekundären Kategorien zurück, wenn die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true ist. Nur lesbar [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // Zugehörige Kategorien sind series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // Zugehörige Kategorien sind series.getChart().getChartData().getCategories()
>  }
> ```

Wenn die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false ist, gibt diese Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in der Eigenschaft (\#getCategories.getCategories) werden sowohl für primäre als auch für sekundäre Reihen verwendet. Ist die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true, werden die Daten in dieser Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) für sekundäre Reihen und die Daten in der Eigenschaft (\#getCategories.getCategories) für primäre Reihen verwendet.

**Rückgabe:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Schreibt die intern enthaltene Excel-Arbeitsmappe in einen Speicherstrom.

**Rückgabe:**
byte[] - Gibt ein Byte-Array zurück, das eine Kopie der intern enthaltenen Excel-Arbeitsmappe enthält.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Initialisiert die intern enthaltene Excel-Arbeitsmappe mit dem vom Benutzer angegebenen Wert.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | Der vom Benutzer bereitgestellte Stream, der die gesamte Excel-Arbeitsmappe enthält. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Legt den Datenbereich des Diagramms fest. Reihen und Kategorien werden basierend auf dem neuen Datenbereich aktualisiert. Wenn die Anzahl der Reihen im Datenbereich größer ist als die Anzahl der Reihen in den Diagrammdaten, werden zusätzliche Reihen mit demselben Typ wie die letzte Reihe in der aktuellen Sammlung am Ende der Sammlung hinzugefügt.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | Die Zellen-Datenbereichs-Formel. Z. B.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

Gibt den Datenbereich des Diagramms zurück.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```


**Rückgabe:**
java.lang.String - Zellen-Datenbereichs-Formel. Z. B.: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Stellt die Datenquelle des Diagramms dar

**Rückgabe:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Stellt den Pfad zu einer externen Arbeitsmappe dar, wenn die Datenquelle extern ist, andernfalls null

**Rückgabe:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Gibt den Typ der eingebetteten Arbeitsmappe zurück. Gibt [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) zurück, wenn DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) ist. Nur lesbar [WorkbookType](../../com.aspose.slides/workbooktype).

**Rückgabe:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Vertauscht die Daten über die Achse. Daten, die auf der X-Achse diagrammiert werden, werden zur Y-Achse verschoben und umgekehrt.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Legt eine externe Arbeitsmappe als Datenquelle für das Diagramm fest. Diagrammdaten werden aus der Zielarbeitsmappe aktualisiert.

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

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Pfad zur Zielarbeitsmappe |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Legt eine externe Arbeitsmappe als Datenquelle für das Diagramm fest.

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

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | Pfad zur Zielarbeitsmappe |
| updateChartData | boolean | Wenn der Wert false ist, wird nur der Pfad zur Arbeitsmappe aktualisiert. Diagrammdaten werden nicht geladen und nicht aus der Zielarbeitsmappe aktualisiert. Kann verwendet werden, wenn die Zielarbeitsmappe nicht existiert oder nicht verfügbar ist. Wenn der Wert true ist, werden Diagrammdaten aus der Zielarbeitsmappe aktualisiert. |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```

Aktualisiert die Diagrammdaten, indem sie aus der Quellarbeitsmappe neu geladen werden.

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