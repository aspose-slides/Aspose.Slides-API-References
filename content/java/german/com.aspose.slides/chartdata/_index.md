---
title: ChartData
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Daten dar, die für die Diagrammzeichnung verwendet werden.
type: docs
url: /de/com.aspose.slides/chartdata/
---
**Vererbung:**
java.lang.Object, com.aspose.slides.DomObject

**Alle implementierten Schnittstellen:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Stellt Daten dar, die für die Diagrammzeichnung verwendet werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Ruft die Zellenfabrik ab, um Zellen zu erstellen, die für Diagrammserien oder -kategorien verwendet werden. |
| [getSeries()](#getSeries--) | Ruft die Serien ab. |
| [getSeriesGroups()](#getSeriesGroups--) | Ruft die Gruppen von Serien ab. |
| [getCategories()](#getCategories--) | Ruft die primären Kategorien ab (oder sowohl primäre als auch sekundäre Kategorien, wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) false ist). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Wenn false, dann gibt die Eigenschaft \#getSecondaryCategories.getSecondaryCategories null zurück und die Daten in der Eigenschaft \#getCategories.getCategories werden sowohl für primäre als auch für sekundäre Serien verwendet. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Wenn false, dann gibt die Eigenschaft \#getSecondaryCategories.getSecondaryCategories null zurück und die Daten in der Eigenschaft \#getCategories.getCategories werden sowohl für primäre als auch für sekundäre Serien verwendet. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Ruft die sekundären Kategorien ab, wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) true ist. |
| [readWorkbookStream()](#readWorkbookStream--) | Schreibt die intern enthaltene Excel-Arbeitsmappe in einen In-Memory-Stream. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialisiert die intern enthaltene Excel-Arbeitsmappe mit dem vom Benutzer angegebenen Wert. |
| [getDataSourceType()](#getDataSourceType--) | Gibt den Pfad zu einer externen Arbeitsmappe an, wenn eine externe Datenquelle verwendet wird, sonst null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Stellt die Datenquelle des Diagramms dar. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Ruft den Typ der eingebetteten Arbeitsmappe ab. |
| [getRange()](#getRange--) | Ruft den Datenbereich des Diagramms ab. |
| [setRange(String formula)](#setRange-java.lang.String-) | Setzt den Datenbereich des Diagramms. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Legt eine externe Arbeitsmappe als Datenquelle für das Diagramm fest. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Legt eine externe Arbeitsmappe als Datenquelle für das Diagramm fest. |
| [refreshData()](#refreshData--) | Aktualisiert die Diagrammdaten, indem sie aus der Quellarbeitsmappe neu geladen werden. |
| [switchRowColumn()](#switchRowColumn--) | Vertauscht die Daten über die Achse. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Ruft die Zellenfabrik ab, um Zellen zu erstellen, die für Diagrammserien oder -kategorien verwendet werden. Nur lesbar [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Rückgabewert:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Ruft die Serien ab. Nur lesbar [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Rückgabewert:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Ruft die Gruppen von Serien ab. Nur lesbar [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Jede Seriengruppe enthält Serien mit kombinierbaren Typen. Gruppen von kombinierbaren Serientypen sind im Enum CombinableSeriesTypesGroup definiert und beschrieben. Außerdem enthält jede Seriengruppe Serien, die entweder auf primären oder auf sekundären Achsen geplottet werden (nicht beide Fälle in einer Gruppe). Das Prinzip der Seriengruppierung ist also eine Gruppierung nach den oben genannten Typgruppen und nach dem primären/sekundären Plottyp. 2) Eine Seriengruppe enthält einige Serieneigenschaften, die für jede Serie in der Gruppe gemeinsam sind („Seriengruppeneigenschaften“). „Seriengruppeneigenschaften“ in der Klasse ChartSeriesGroup sind Lese/Schreib. Jede „Seriengruppeneigenschaft“ kann in der Klasse ChartSeries eine nur lesbare Projektion haben.

**Rückgabewert:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Ruft die primären Kategorien ab (oder sowohl primäre als auch sekundäre Kategorien, wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) false ist). Nur lesbar [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // zugehörige Kategorien sind series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // zugehörige Kategorien sind series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) false ist, dann gibt die Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in dieser Eigenschaft \#getCategories.getCategories werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) true ist, dann werden die Daten in der Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) für sekundäre Serien und die Daten in dieser Eigenschaft \#getCategories.getCategories für primäre Serien verwendet.

**Rückgabewert:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Wenn false, dann gibt die Eigenschaft \#getSecondaryCategories.getSecondaryCategories null zurück und die Daten in der Eigenschaft \#getCategories.getCategories werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn true, dann werden die Daten in der Eigenschaft \#getSecondaryCategories.getSecondaryCategories für sekundäre Serien und die Daten in der Eigenschaft \#getCategories.getCategories für primäre Serien verwendet. Lese/Schreib boolesch.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // zugehörige Kategorien sind series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // zugehörige Kategorien sind series.getChart().getChartData().getCategories()
>  }
> ```

**Rückgabewert:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Wenn false, dann gibt die Eigenschaft \#getSecondaryCategories.getSecondaryCategories null zurück und die Daten in der Eigenschaft \#getCategories.getCategories werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn true, dann werden die Daten in der Eigenschaft \#getSecondaryCategories.getSecondaryCategories für sekundäre Serien und die Daten in der Eigenschaft \#getCategories.getCategories für primäre Serien verwendet. Lese/Schreib boolesch.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // zugehörige Kategorien sind series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // zugehörige Kategorien sind series.getChart().getChartData().getCategories()
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

Ruft die sekundären Kategorien ab, wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) true ist. Nur lesbar [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // zugehörige Kategorien sind series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // zugehörige Kategorien sind series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) false ist, dann gibt diese Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in der Eigenschaft \#getCategories.getCategories werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) true ist, dann werden die Daten in dieser Eigenschaft \#getSecondaryCategories.getSecondaryCategories für sekundäre Serien und die Daten in der Eigenschaft \#getCategories.getCategories für primäre Serien verwendet.

**Rückgabewert:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Schreibt die intern enthaltene Excel-Arbeitsmappe in einen In-Memory-Stream.

**Rückgabewert:**
byte[] - Gibt ein Byte-Array-Exemplar zurück, das eine Kopie der intern enthaltenen Excel-Arbeitsmappe enthält.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Initialisiert die intern enthaltene Excel-Arbeitsmappe mit dem vom Benutzer angegebenen Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ms | byte[] | Der vom Benutzer bereitgestellte Stream, der die gesamte Excel-Arbeitsmappe enthält. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Gibt den Pfad zu einer externen Arbeitsmappe an, wenn eine externe Datenquelle verwendet wird, sonst null.

**Rückgabewert:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Stellt die Datenquelle des Diagramms dar.

**Rückgabewert:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Ruft den Typ der eingebetteten Arbeitsmappe ab. Gibt [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) zurück, wenn DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) ist. Nur lesbar [WorkbookType](../../com.aspose.slides/workbooktype).

**Rückgabewert:**
int
### getRange() {#getRange--}
```
public final String getRange()
```

Ruft den Datenbereich des Diagramms ab.

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

**Rückgabewert:**
java.lang.String - Zellen-Datenbereichsformel. z. B.: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Setzt den Datenbereich des Diagramms. Serien und Kategorien werden basierend auf dem neuen Datenbereich aktualisiert. Wenn die Anzahl der Serien im Datenbereich größer ist als die Anzahl der Serien im Diagrammdaten, werden zusätzliche Serien mit demselben Typ wie die letzte Serie in der aktuellen Sammlung am Ende der Sammlung hinzugefügt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formula | java.lang.String | Die Zellen-Datenbereichsformel. z. B.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
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
>     if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| workbookPath | java.lang.String | Pfad zur Zielarbeitsmappe |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Legt eine externe Arbeitsmappe als Datenquelle für das Diagramm fest.

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

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| workbookPath | java.lang.String | Pfad zur Zielarbeitsmappe |
| updateChartData | boolean | Wenn der Wert false ist, wird nur der Pfad zur Arbeitsmappe aktualisiert. Diagrammdaten werden nicht geladen und nicht aus der Zielarbeitsmappe aktualisiert. Kann verwendet werden, wenn die Zielarbeitsmappe nicht existiert oder nicht verfügbar ist. Wenn der Wert true ist, werden die Diagrammdaten aus der Zielarbeitsmappe aktualisiert. |

### refreshData() {#refreshData--}
```
public final void refreshData()
```

Aktualisiert die Diagrammdaten, indem sie aus der Quellarbeitsmappe neu geladen werden.

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

Vertauscht die Daten über die Achse. Daten, die auf der X-Achse dargestellt werden, wechseln zur Y-Achse und umgekehrt.