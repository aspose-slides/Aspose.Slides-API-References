---
title: ChartData
second_title: Aspose.Slides für Android über Java API-Referenz
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

Stellt Daten bereit, die für die Diagrammerstellung verwendet werden.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Ruft die Zellenfabrik ab, um Zellen für Diagrammreihen oder Kategorien zu erstellen. |
| [getSeries()](#getSeries--) | Ruft die Reihen ab. |
| [getSeriesGroups()](#getSeriesGroups--) | Ruft die Gruppen von Reihen ab. |
| [getCategories()](#getCategories--) | Ruft die primären Kategorien ab (oder sowohl primäre als auch sekundäre Kategorien, wenn die Eigenschaft #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) false ist). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Wenn false, gibt die Eigenschaft #getSecondaryCategories.getSecondaryCategories null zurück und die Daten in der Eigenschaft #getCategories.getCategories werden sowohl für primäre als auch für sekundäre Reihen verwendet. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Wenn false, gibt die Eigenschaft #getSecondaryCategories.getSecondaryCategories null zurück und die Daten in der Eigenschaft #getCategories.getCategories werden sowohl für primäre als auch für sekundäre Reihen verwendet. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Ruft die sekundären Kategorien ab, wenn die Eigenschaft #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) true ist. |
| [readWorkbookStream()](#readWorkbookStream--) | Schreibt die intern enthaltene Excel-Arbeitsmappe in einen Speicherstrom. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Initialisiert die intern enthaltene Excel-Arbeitsmappe mit dem vom Benutzer angegebenen Wert. |
| [getDataSourceType()](#getDataSourceType--) | Stellt den Pfad zur externen Arbeitsmappe dar, falls externe Datenquelle, sonst null. |
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

Ruft die Zellenfabrik ab, um Zellen für Diagrammreihen oder Kategorien zu erstellen. Nur lesbar [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Rückgabe:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Ruft die Reihen ab. Nur lesbar [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Rückgabe:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Ruft die Gruppen von Reihen ab. Nur lesbar [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Jede Gruppe von Reihen enthält Reihen mit kombinierbaren Typen. Gruppen kombinierbarer Reihentypen werden mit dem Enum CombinableSeriesTypesGroup definiert und beschrieben. Außerdem enthält jede Gruppe von Reihen Reihen, die entweder auf den primären Achsen oder auf den sekundären Achsen geplottet werden (nicht beide Fälle in einer Gruppe). Das Prinzip der Gruppierung von Reihen ist also eine Gruppierung nach den oben genannten Typgruppen und nach dem primären/sekundären Plot-Typ. 2) Eine Gruppe von Reihen enthält einige Reihen-Eigenschaften, die für jede Reihe in der Gruppe gemeinsam sind („Series-Group-Properties“). „Series-Group-Properties“ in der Klasse ChartSeriesGroup ist Lese/Schreiber. Jede dieser „Series-Group-Properties“ kann eine nur lesbare Projektion in der Klasse ChartSeries haben.

**Rückgabe:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Ruft die primären Kategorien ab (oder sowohl primäre als auch sekundäre Kategorien, wenn die Eigenschaft #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) false ist). Nur lesbar [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // verknüpfte Kategorien sind series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // verknüpfte Kategorien sind series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Wenn #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) false ist, gibt die Eigenschaft #getSecondaryCategories.getSecondaryCategories null zurück und die Daten in der Eigenschaft #getCategories.getCategories werden sowohl für primäre als auch für sekundäre Reihen verwendet. Wenn die Eigenschaft true ist, werden die Daten in der Eigenschaft #getSecondaryCategories.getSecondaryCategories für sekundäre Reihen und die Daten in der Eigenschaft #getCategories.getCategories für primäre Reihen verwendet.

**Rückgabe:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Wenn false, gibt die Eigenschaft #getSecondaryCategories.getSecondaryCategories null zurück und die Daten in der Eigenschaft #getCategories.getCategories werden sowohl für primäre als auch für sekundäre Reihen verwendet. Wenn true, werden die Daten in der Eigenschaft #getSecondaryCategories.getSecondaryCategories für sekundäre Reihen und die Daten in der Eigenschaft #getCategories.getCategories für primäre Reihen verwendet. Lese/Schreib boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // verknüpfte Kategorien sind series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // verknüpfte Kategorien sind series.getChart().getChartData().getCategories()
>  }
> ```

**Rückgabe:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Wenn false, gibt die Eigenschaft #getSecondaryCategories.getSecondaryCategories null zurück und die Daten in der Eigenschaft #getCategories.getCategories werden sowohl für primäre als auch für sekundäre Reihen verwendet. Wenn true, werden die Daten in der Eigenschaft #getSecondaryCategories.getSecondaryCategories für sekundäre Reihen und die Daten in der Eigenschaft #getCategories.getCategories für primäre Reihen verwendet. Lese/Schreib boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // verknüpfte Kategorien sind series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // verknüpfte Kategorien sind series.getChart().getChartData().getCategories()
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

Ruft die sekundären Kategorien ab, wenn die Eigenschaft #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) true ist. Nur lesbar [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // verknüpfte Kategorien sind series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // verknüpfte Kategorien sind series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Wenn #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) false ist, gibt die Eigenschaft #getSecondaryCategories.getSecondaryCategories null zurück und die Daten in der Eigenschaft #getCategories.getCategories werden sowohl für primäre als auch für sekundäre Reihen verwendet. Wenn die Eigenschaft true ist, werden die Daten in der Eigenschaft #getSecondaryCategories.getSecondaryCategories für sekundäre Reihen und die Daten in der Eigenschaft #getCategories.getCategories für primäre Reihen verwendet.

**Rückgabe:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Schreibt die intern enthaltene Excel-Arbeitsmappe in einen Speicherstrom.

**Rückgabe:**
byte[] - Gibt eine Instanz eines Byte-Arrays zurück, das eine Kopie der intern enthaltenen Excel-Arbeitsmappe enthält.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Initialisiert die intern enthaltene Excel-Arbeitsmappe mit dem vom Benutzer angegebenen Wert.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ms | byte[] | Der vom Benutzer bereitgestellte Strom, der die gesamte Excel-Arbeitsmappe enthält. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Stellt den Pfad zur externen Arbeitsmappe dar, falls externe Datenquelle, sonst null.

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

Ruft den Typ der eingebetteten Arbeitsmappe ab. Gibt [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) zurück, wenn DataSourceType (#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook) ist. Nur lesbar [WorkbookType](../../com.aspose.slides/workbooktype).

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
java.lang.String - Zellen-Datenbereichs-Formel. Bsp.: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Setzt den Diagrammdatenbereich. Reihen und Kategorien werden basierend auf dem neuen Datenbereich aktualisiert. Wenn die Anzahl der Reihen im Datenbereich größer ist als die Anzahl der Reihen im Diagramm, werden zusätzliche Reihen mit dem gleichen Typ wie die letzte Reihe in der aktuellen Sammlung am Ende der Sammlung hinzugefügt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| formula | java.lang.String | Die Zellen-Datenbereichs-Formel. Bsp.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Setzt die externe Arbeitsmappe als Datenquelle für das Diagramm. Diagrammdaten werden aus der Ziel-Arbeitsmappe aktualisiert.

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
| workbookPath | java.lang.String | Pfad zur Ziel-Arbeitsmappe |

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
| workbookPath | java.lang.String | Pfad zur Ziel-Arbeitsmappe |
| updateChartData | boolean | Wenn der Wert false ist, wird nur der Pfad zur Arbeitsmappe aktualisiert. Diagrammdaten werden nicht aus der Ziel-Arbeitsmappe geladen und aktualisiert. Kann verwendet werden, wenn die Ziel-Arbeitsmappe nicht existiert oder nicht verfügbar ist. Wenn der Wert true ist, werden die Diagrammdaten aus der Ziel-Arbeitsmappe aktualisiert. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Vertauscht die Daten über die Achse. Daten, die auf der X-Achse dargestellt werden, werden zur Y-Achse verschoben und umgekehrt.