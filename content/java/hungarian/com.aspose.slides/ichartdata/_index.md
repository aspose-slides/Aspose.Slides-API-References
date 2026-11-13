---
title: IChartData
second_title: Aspose.Slides for Java API Reference
description: Az ábrakészítéshez használt adatokat képviseli.
type: docs
url: /hu/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Az ábrakészítéshez használt adatokat képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Megkapja a cellagyárat a diagram sorozatokhoz vagy kategóriákhoz használt cellák létrehozásához. |
| [getSeries()](#getSeries--) | Megkapja a sorozatokat. |
| [getSeriesGroups()](#getSeriesGroups--) | Megkapja a sorozatok csoportjait. |
| [getCategories()](#getCategories--) | Megkapja az elsődleges kategóriákat (vagy az elsődleges és a másodlagos kategóriákat is, ha (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság hamis). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Ha hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad, és a (\#getCategories.getCategories) tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Ha hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad, és a (\#getCategories.getCategories) tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Megkapja a másodlagos kategóriákat, ha (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság igaz. |
| [readWorkbookStream()](#readWorkbookStream--) | Az internálisan tárolt Excel munkafüzetet egy memóriában lévő folyamba írja. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Az internálisan tárolt Excel munkafüzetet felhasználó által megadott értékkel inicializálja. |
| [setRange(String formula)](#setRange-java.lang.String-) | Beállítja a diagram adat-tartományt. |
| [getRange()](#getRange--) | Megkapja a diagram adat-tartományt. |
| [getDataSourceType()](#getDataSourceType--) | A diagram adatforrását képviseli. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Külső munkafüzet útvonalát jelöli, ha az adatforrás külső, egyébként null. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Megkapja a beágyazott munkafüzet típusát. |
| [switchRowColumn()](#switchRowColumn--) | Az adatot felcseréli az tengelyek között. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Különálló munkafüzetet állít be adatforrásként a diagramhoz. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Különálló munkafüzetet állít be adatforrásként a diagramhoz. |
| [refreshData()](#refreshData--) | A diagram adatot frissíti a forrásmunkafüzet újratöltésével. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

Megkapja a cellagyárat a diagram sorozatokhoz vagy kategóriákhoz használt cellák létrehozásához. Csak olvasható [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Visszatér:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

Megkapja a sorozatokat. Csak olvasható [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Visszatér:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

Megkapja a sorozatok csoportjait. Csak olvasható [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek kombinálható típusúak. A kombinálható sorozattípuscsoportok a CombinableSeriesTypesGroup enumerációval vannak definiálva és leírva. Emellett minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek vagy elsődleges, vagy másodlagos tengelyen vannak ábrázolva (nem mindkét eset egy csoportban). Tehát a sorozatcsoportolás alapelve a fent említett típuscsoportok és az elsődleges/másodlagos ábrázolási típus szerinti csoportosítás. 2) Egy sorozatcsoport tartalmaz néhány sorozattulajdonságot, amely közös az adott csoport minden sorozata számára ("sorozatcsoport-tulajdonságok"). A "Series group properties" a ChartSeriesGroup osztályban olvasás/írás. Minden "sorozatcsoport-tulajdonságnak" lehet egy csak olvasható vetülete a ChartSeries osztályban.

**Visszatér:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Megkapja az elsődleges kategóriákat (vagy az elsődleges és a másodlagos kategóriákat is, ha (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság hamis). Csak olvasható [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // a kapcsolódó kategóriák a series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // a kapcsolódó kategóriák a series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Ha (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad, és a (\#getCategories.getCategories) tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság igaz, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság adatai a másodlagos sorozatokhoz, a (\#getCategories.getCategories) tulajdonság adatai pedig az elsődleges sorozatokhoz használatosak.

**Visszatér:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Ha hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad, és a (\#getCategories.getCategories) tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha igaz, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság adatai a másodlagos sorozatokhoz, a (\#getCategories.getCategories) tulajdonság adatai pedig az elsődleges sorozatokhoz használatosak. Olvasás/írás boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // a kapcsolódó kategóriák a series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // a kapcsolódó kategóriák a series.getChart().getChartData().getCategories()
>  }
> ```

**Visszatér:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```

Ha hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad, és a (\#getCategories.getCategories) tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha igaz, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság adatai a másodlagos sorozatokhoz, a (\#getCategories.getCategories) tulajdonság adatai pedig az elsődleges sorozatokhoz használatosak. Olvasás/írás boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // a kapcsolódó kategóriák series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // a kapcsolódó kategóriák series.getChart().getChartData().getCategories()
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

Megkapja a másodlagos kategóriákat, ha (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság igaz. Csak olvasható [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // a kapcsolódó kategóriák a series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // a kapcsolódó kategóriák a series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Ha (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság hamis, akkor ez a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad, és a (\#getCategories.getCategories) tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság igaz, akkor ez a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság adatai a másodlagos sorozatokhoz, a (\#getCategories.getCategories) tulajdonság adatai pedig az elsődleges sorozatokhoz használatosak.

**Visszatér:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

Az internálisan tárolt Excel munkafüzetet egy memóriában lévő folyamba írja.

**Visszatér:**
byte[] - Egy bájt tömböt ad vissza, amely az internálisan tárolt Excel munkafüzet másolatát tartalmazza.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

Az internálisan tárolt Excel munkafüzetet felhasználó által megadott értékkel inicializálja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ms | byte[] | A felhasználó által biztosított folyam, amely a teljes Excel munkafüzetet tartalmazza. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Beállítja a diagram adat-tartományt. A sorozatok és kategóriák az új adat-tartomány alapján frissülnek. Ha az adat-tartományban lévő sorozatok száma nagyobb, mint a diagram adat-tartományban lévő sorozatok száma, akkor további sorozatok lesznek hozzáadva a gyűjtemény végéhez, azonos típussal, mint az aktuális gyűjtemény utolsó sorozata.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formula | java.lang.String | A cellák adat-tartomány képlete. Pl.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```

Megkapja a diagram adat-tartományt.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Visszatér:**
java.lang.String - A cellák adat-tartomány képlete. Pl.: "Sheet1!$A$1:$C$4"

### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

A diagram adatforrását képviseli

**Visszatér:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Külső munkafüzet útvonalát jelöli, ha az adatforrás külső, egyébként null

**Visszatér:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

Megkapja a beágyazott munkafüzet típusát. [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) értéket ad vissza, ha a DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Csak olvasható [WorkbookType](../../com.aspose.slides/workbooktype).

**Visszatér:**
int

### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Az adatot felcseréli az tengelyek között. A X tengelyen ábrázolt adat áthelyeződik a Y tengelyre és fordítva.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```

Különálló munkafüzetet állít be adatforrásként a diagramhoz. A diagram adatai a célmunkafüzetből lesznek frissítve.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| workbookPath | java.lang.String | A célmunkafüzet elérési útja |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Különálló munkafüzetet állít be adatforrásként a diagramhoz.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| workbookPath | java.lang.String | A célmunkafüzet elérési útja |
| updateChartData | boolean | Ha az érték hamis, csak a munkafüzet elérési útja frissül. A diagram adatai nem kerülnek betöltésre és frissülésre a célmunkafüzetről. Akkor használható, ha a célmunkafüzet nem létezik vagy nem érhető el. Ha az érték igaz, a diagram adatai frissülnek a célmunkafüzetről. |

### refreshData() {#refreshData--}
```
public abstract void refreshData()
```

A diagram adatot frissíti a forrásmunkafüzet újratöltésével.

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