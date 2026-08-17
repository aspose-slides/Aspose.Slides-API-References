---
title: ChartData
second_title: Aspose.Slides für Java API-Referenz
description: Stellt Daten bereit, die für die Diagrammerstellung verwendet werden.
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

Stellt Daten bereit, die für die Diagramm-Darstellung verwendet werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Ruft die Zellenfabrik ab, um Zellen zu erstellen, die für Diagrammserien oder -kategorien verwendet werden. |
| [getSeries()](#getSeries--) | Ruft die Serien ab. |
| [getSeriesGroups()](#getSeriesGroups--) | Ruft die Gruppen von Serien ab. |
| [getCategories()](#getCategories--) | Ruft die primären Kategorien ab (oder sowohl primäre als auch sekundäre Kategorien, wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) false ist). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Falls false, gibt die Eigenschaft \#getSecondaryCategories.getSecondaryCategories null zurück und die Daten in der Eigenschaft \#getCategories.getCategories werden sowohl für primäre als auch für sekundäre Serien verwendet. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Falls false, gibt die Eigenschaft \#getSecondaryCategories.getSecondaryCategories null zurück und die Daten in der Eigenschaft \#getCategories.getCategories werden sowohl für primäre als auch für sekundäre Serien verwendet. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Ruft die sekundären Kategorien ab, wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) true ist. |
| [readWorkbookStream()](#readWorkbookStream--) | Schreibt die intern enthaltene Excel-Arbeitsmappe in einen In-Memory-Stream. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialisiert die intern enthaltene Excel-Arbeitsmappe mit dem vom Benutzer angegebenen Wert. |
| [getDataSourceType()](#getDataSourceType--) | Stellt den Pfad zu einer externen Arbeitsmappe dar, falls externe Datenquelle, andernfalls null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Stellt die Datenquelle des Diagramms dar. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Ruft den Typ der eingebetteten Arbeitsmappe ab. |
| [getRange()](#getRange--) | Ruft den Diagrammdatenbereich ab. |
| [setRange(String formula)](#setRange-java.lang.String-) | Setzt den Diagrammdatenbereich. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Setzt die externe Arbeitsmappe als Datenquelle für das Diagramm. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Setzt die externe Arbeitsmappe als Datenquelle für das Diagramm. |
| [switchRowColumn()](#switchRowColumn--) | Vertauscht die Daten über die Achse. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Ruft die Zellenfabrik ab, um Zellen zu erstellen, die für Diagrammserien oder -kategorien verwendet werden. Nur lesend [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Rückgabe:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Ruft die Serien ab. Nur lesend [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Rückgabe:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Ruft die Gruppen von Serien ab. Nur lesend [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Jede Gruppe von Serien enthält Serien mit kombinierbaren Typen. Gruppen von kombinierbaren Serientypen werden durch das Enumerationsfeld CombinableSeriesTypesGroup definiert und beschrieben. Außerdem enthält jede Gruppe von Serien Serien, die entweder auf primären Achsen oder auf sekundären Achsen (nicht in beiden Fällen in einer Gruppe) dargestellt werden. Das Prinzip der Seriendefinition ist also eine Gruppierung nach den oben genannten Typgruppen und nach dem primären/sekundären Darstellungstyp. 2) Eine Gruppe von Serien enthält einige Serieneigenschaften, die für jede Serie in der Gruppe gemeinsam sind („Seriengruppeneigenschaften“). „Seriengruppeneigenschaften“ in der Klasse ChartSeriesGroup sind les-/schreibfähig. Jede „Seriengruppeneigenschaft“ kann eine nur lesende Projektion in der Klasse ChartSeries haben.

**Rückgabe:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Ruft die primären Kategorien ab (oder sowohl primäre als auch sekundäre Kategorien, wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) false ist). Nur lesend [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) false ist, gibt die Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in der Eigenschaft \#getCategories.getCategories werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) true ist, werden die Daten in der Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) für sekundäre Serien und die Daten in der Eigenschaft \#getCategories.getCategories für primäre Serien verwendet.

**Rückgabe:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Wenn false, gibt die Eigenschaft \#getSecondaryCategories.getSecondaryCategories null zurück und die Daten in der Eigenschaft \#getCategories.getCategories werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn true, werden die Daten in der Eigenschaft \#getSecondaryCategories.getSecondaryCategories für sekundäre Serien und die Daten in der Eigenschaft \#getCategories.getCategories für primäre Serien verwendet. Lese-/Schreib-boolean.

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

**Rückgabe:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Wenn false, gibt die Eigenschaft \#getSecondaryCategories.getSecondaryCategories null zurück und die Daten in der Eigenschaft \#getCategories.getCategories werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn true, werden die Daten in der Eigenschaft \#getSecondaryCategories.getSecondaryCategories für sekundäre Serien und die Daten in der Eigenschaft \#getCategories.getCategories für primäre Serien verwendet. Lese-/Schreib-boolean.

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

Ruft die sekundären Kategorien ab, wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) true ist. Nur lesend [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) false ist, gibt die Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) null zurück und die Daten in der Eigenschaft \#getCategories.getCategories werden sowohl für primäre als auch für sekundäre Serien verwendet. Wenn die Eigenschaft \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) true ist, werden die Daten in der Eigenschaft (\#getSecondaryCategories.getSecondaryCategories) für sekundäre Serien und die Daten in der Eigenschaft \#getCategories.getCategories für primäre Serien verwendet.

**Rückgabe:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Schreibt die intern enthaltene Excel-Arbeitsmappe in einen In-Memory-Stream.

**Rückgabe:**
byte[] - Gibt eine Instanz eines Byte-Arrays zurück, die eine Kopie der intern enthaltenen Excel-Arbeitsmappe enthält.

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

Stellt den Pfad zu einer externen Arbeitsmappe dar, falls externe Datenquelle, andernfalls null.

**Rückgabe:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Stellt die Datenquelle des Diagramms dar.

**Rückgabe:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Ruft den Typ der eingebetteten Arbeitsmappe ab. Gibt [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) zurück, wenn DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) ist. Nur lesend [WorkbookType](../../com.aspose.slides/workbooktype).

**Rückgabe:**
int

### getRange() {#getRange--}
```
public final String getRange()
```

Ruft den Diagrammdatenbereich ab.

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

**Rückgabe:**
java.lang.String - Formel für den Zellen-Datenbereich. Z. B.: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Setzt den Diagrammdatenbereich. Serien und Kategorien werden basierend auf dem neuen Datenbereich aktualisiert. Wenn die Anzahl der Serien im Datenbereich größer ist als die Anzahl der Serien in den Diagrammdaten, werden zusätzliche Serien mit dem gleichen Typ wie die letzte Serie in der aktuellen Sammlung am Ende der Sammlung hinzugefügt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formula | java.lang.String | Die Formel für den Zellen-Datenbereich. Z. B.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Setzt die externe Arbeitsmappe als Datenquelle für das Diagramm. Diagrammdaten werden aus der Zielarbeitsmappe aktualisiert.

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

Setzt die externe Arbeitsmappe als Datenquelle für das Diagramm.

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
| updateChartData | boolean | Wenn der Wert false ist, wird nur der Pfad zur Arbeitsmappe aktualisiert. Diagrammdaten werden nicht aus der Zielarbeitsmappe geladen und aktualisiert. Kann verwendet werden, wenn die Zielarbeitsmappe nicht existiert oder nicht verfügbar ist. Wenn der Wert true ist, werden die Diagrammdaten aus der Zielarbeitsmappe aktualisiert. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Vertauscht die Daten über die Achse. Daten, die auf der X-Achse dargestellt werden, werden auf die Y-Achse verschoben und umgekehrt.