---
title: IChartData
second_title: Aspose.Slides für Android via Java API-Referenz
description: Stellt Daten dar, die für das Plotten eines Diagramms verwendet werden.
type: docs
url: /de/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Stellt Daten dar, die für das Plotten eines Diagramms verwendet werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Liefert die Zellenfabrik zum Erzeugen von Zellen, die für Diagrammserien oder -kategorien verwendet werden. |
| [getSeries()](#getSeries--) | Liefert die Serien. |
| [getSeriesGroups()](#getSeriesGroups--) | Liefert die Gruppen von Serien. |
| [getCategories()](#getCategories--) | Liefert die primären Kategorien (oder sowohl primäre als auch sekundäre Kategorien, wenn die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false ist). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Wenn false, gibt die Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in der Eigenschaft (\#getCategories.getCategories) werden sowohl für primäre als auch für sekundäre Serien verwendet. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Wenn false, gibt die Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in der Eigenschaft (\#getCategories.getCategories) werden sowohl für primäre als auch für sekundäre Serien verwendet. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Liefert die sekundären Kategorien, wenn die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true ist. |
| [readWorkbookStream()](#readWorkbookStream--) | Schreibt die intern enthaltene Excel-Arbeitsmappe in einen In-Memory-Stream. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialisiert die intern enthaltene Excel-Arbeitsmappe mit dem vom Benutzer angegebenen Wert. |
| [setRange(String formula)](#setRange-java.lang.String-) | Setzt den Datenbereich des Diagramms. |
| [getRange()](#getRange--) | Liefert den Datenbereich des Diagramms. |
| [getDataSourceType()](#getDataSourceType--) | Stellt die Datenquelle des Diagramms dar |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Stellt den Pfad zur externen Arbeitsmappe dar, wenn die Datenquelle extern ist, sonst null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Liefert den Typ der eingebetteten Arbeitsmappe. |
| [switchRowColumn()](#switchRowColumn--) | Vertauscht die Daten über die Achse. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Setzt eine externe Arbeitsmappe als Datenquelle für das Diagramm. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Setzt eine externe Arbeitsmappe als Datenquelle für das Diagramm. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Liefert die Zellenfabrik zum Erzeugen von Zellen, die für Diagrammserien oder -kategorien verwendet werden. Nur lesbar [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Rückgabewert:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Liefert die Serien. Nur lesbar [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Rückgabewert:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Liefert die Gruppen von Serien. Nur lesbar [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Jede Gruppe von Serien enthält Serien mit kombinierbaren Typen. Gruppen von kombinierbaren Serientypen werden mit dem Enum CombinableSeriesTypesGroup definiert und beschrieben. Außerdem enthält jede Gruppe von Serien Serien, die entweder auf den primären Achsen oder auf den sekundären Achsen geplottet werden (nicht beide Fälle in einer Gruppe). Das Prinzip der Seriengruppierung ist also eine Gruppierung nach den oben genannten Typgruppen und nach dem primären/sekundären Plottyp. 2) Eine Gruppe von Serien enthält einige Serieneigenschaften, die für jede Serie in der Gruppe gemeinsam sind ("Series group properties"). "Series group properties" in der Klasse ChartSeriesGroup sind les-/schreibbar. Jede "Series group properties" kann in der Klasse ChartSeries eine schreibgeschützte Projektion haben.

**Rückgabewert:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Liefert die primären Kategorien (oder sowohl primäre als auch sekundäre Kategorien, wenn die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false ist). Nur lesbar [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Wenn die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false ist, gibt die Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in dieser Eigenschaft (\#getCategories.getCategories) werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true ist, werden die Daten in der Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) für sekundäre Serien und die Daten in dieser Eigenschaft (\#getCategories.getCategories) für primäre Serien verwendet.

**Rückgabewert:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Wenn false, gibt die Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in der Eigenschaft (\#getCategories.getCategories) werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn true, werden die Daten in der Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) für sekundäre Serien und die Daten in der Eigenschaft (\#getCategories.getCategories) für primäre Serien verwendet. Lese-/Schreib-Boolescher Wert.

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
public abstract void setUseSecondaryCategories(boolean value)
```

Wenn false, gibt die Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in der Eigenschaft (\#getCategories.getCategories) werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn true, werden die Daten in der Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) für sekundäre Serien und die Daten in der Eigenschaft (\#getCategories.getCategories) für primäre Serien verwendet. Lese-/Schreib-Boolescher Wert.

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
public abstract IChartCategoryCollection getSecondaryCategories()
```

Liefert die sekundären Kategorien, wenn die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true ist. Nur lesbar [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Wenn die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false ist, gibt diese Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in der Eigenschaft (\#getCategories.getCategories) werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn die Eigenschaft (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true ist, werden die Daten in dieser Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) für sekundäre Serien und die Daten in der Eigenschaft (\#getCategories.getCategories) für primäre Serien verwendet.

**Rückgabewert:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Schreibt die intern enthaltene Excel-Arbeitsmappe in einen In-Memory-Stream.

**Rückgabewert:**
byte[] - Gibt ein Byte-Array zurück, das eine Kopie der intern enthaltenen Excel-Arbeitsmappe enthält.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Initialisiert die intern enthaltene Excel-Arbeitsmappe mit dem vom Benutzer angegebenen Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ms | byte[] | Der vom Benutzer bereitgestellte Stream, der die gesamte Excel-Arbeitsmappe enthält. |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Setzt den Datenbereich des Diagramms. Serien und Kategorien werden basierend auf dem neuen Datenbereich aktualisiert. Wenn die Anzahl der Serien im Datenbereich größer ist als die Anzahl der Serien in den Diagrammdaten, werden zusätzliche Serien mit dem gleichen Typ wie die letzte Serie in der aktuellen Sammlung am Ende der Sammlung hinzugefügt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formula | java.lang.String | Die Zellen-Datenbereichsformel. Z. B.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
### getRange() {#getRange--}
```
public abstract String getRange()
```

Liefert den Datenbereich des Diagramms.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```


**Rückgabewert:**
java.lang.String - Zellen-Datenbereichsformel. Z. B.: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

Stellt die Datenquelle des Diagramms dar

**Rückgabewert:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Stellt den Pfad zur externen Arbeitsmappe dar, wenn die Datenquelle extern ist, sonst null

**Rückgabewert:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Liefert den Typ der eingebetteten Arbeitsmappe. Gibt [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) zurück, wenn DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) ist. Nur lesbar [WorkbookType](../../com.aspose.slides/workbooktype).

**Rückgabewert:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Vertauscht die Daten über die Achse. Daten, die auf der X-Achse dargestellt werden, verschieben sich zur Y-Achse und umgekehrt.
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Setzt eine externe Arbeitsmappe als Datenquelle für das Diagramm. Diagrammdaten werden aus der Zielarbeitsmappe aktualisiert.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| workbookPath | java.lang.String | Pfad zur Zielarbeitsmappe |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Setzt eine externe Arbeitsmappe als Datenquelle für das Diagramm.

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| workbookPath | java.lang.String | Pfad zur Zielarbeitsmappe |
| updateChartData | boolean | Wenn der Wert false ist, wird nur der Pfad zur Arbeitsmappe aktualisiert. Diagrammdaten werden nicht aus der Zielarbeitsmappe geladen und aktualisiert. Kann verwendet werden, wenn die Zielarbeitsmappe nicht existiert oder nicht verfügbar ist. Wenn der Wert true ist, werden die Diagrammdaten aus der Zielarbeitsmappe aktualisiert. |