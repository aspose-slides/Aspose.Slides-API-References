---
title: ChartData
second_title: Aspose.Slides Java API referencia
description: A diagram ábrázolásához használt adatokat képviseli.
type: docs
url: /hu/com.aspose.slides/chartdata/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Az összes megvalósított interfész:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Az ábra ábrázolásához használt adatokat képviseli.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | A cellagyárat adja vissza, amely a diagram sorozatokhoz vagy kategóriákhoz használt cellákat hozza létre. |
| [getSeries()](#getSeries--) | A sorozatokat adja vissza. |
| [getSeriesGroups()](#getSeriesGroups--) | A sorozatcsoportokat adja vissza. |
| [getCategories()](#getCategories--) | Az elsődleges kategóriákat adja vissza (vagy az elsődleges és másodlagos kategóriákat is, ha a \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság hamis). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Ha hamis, akkor a \#getSecondaryCategories.getSecondaryCategories tulajdonság null értéket ad vissza, és a \#getCategories.getCategories tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Ha hamis, akkor a \#getSecondaryCategories.getSecondaryCategories tulajdonság null értéket ad vissza, és a \#getCategories.getCategories tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. |
| [getSecondaryCategories()](#getSecondaryCategories--) | A másodlagos kategóriákat adja vissza, ha a \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság igaz. |
| [readWorkbookStream()](#readWorkbookStream--) | Az belső Excel munkafüzetet egy memóriában lévő adatfolyamba írja. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | A belső Excel munkafüzetet a felhasználó által megadott értékkel inicializálja. |
| [getDataSourceType()](#getDataSourceType--) | Külső munkafüzet útvonalat képviseli, ha külső adatforrás, egyébként null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | A diagram adatforrását képviseli. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | A beágyazott munkafüzet típusát adja vissza. |
| [getRange()](#getRange--) | A diagram adat tartományát adja vissza. |
| [setRange(String formula)](#setRange-java.lang.String-) | Beállítja a diagram adat tartományát. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Külső munkafüzetet állít be adatforrásként a diagramhoz. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Külső munkafüzetet állít be adatforrásként a diagramhoz. |
| [refreshData()](#refreshData--) | A diagram adatokat frissíti a forrás munkafüzetből újratöltve. |
| [switchRowColumn()](#switchRowColumn--) | Az adatokat áthelyezi az tengelyek között. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

A cellagyárat adja vissza, amely a diagram sorozatokhoz vagy kategóriákhoz használt cellákat hozza létre. Csak olvasható [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Visszatér:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

A sorozatokat adja vissza. Csak olvasható [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Visszatér:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

A sorozatcsoportokat adja vissza. Csak olvasható [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek kombinálható típusúak. A kombinálható sorozattípus csoportokat a CombinableSeriesTypesGroup enum határozza meg és írja le. Emellett minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek vagy az elsődleges tengelyeken, vagy a másodlagos tengelyeken ábrázolhatók (nem mindkét eset egy csoportban). Így a sorozatcsoportosítás elve a fent említett típuscsoportok szerinti csoportosítás és az elsődleges/másodlagos ábrázolási típus szerint történik. 2) A sorozatcsoport néhány sorozati tulajdonságot tartalmaz, amelyek minden sorozatra jellemzőek a csoportban („sorozatcsoport tulajdonságok”). A ChartSeriesGroup osztályban a „sorozatcsoport tulajdonságok” olvasás/írás módúak. Minden „sorozatcsoport tulajdonságnak” lehet csak olvasható vetülete a ChartSeries osztályban.

**Visszatér:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Az elsődleges kategóriákat adja vissza (vagy az elsődleges és másodlagos kategóriákat is, ha a \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság hamis). Csak olvasható [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // kapcsolódó kategóriák: series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // kapcsolódó kategóriák: series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Ha \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság hamis, akkor ez a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad vissza, és a \#getCategories.getCategories tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha a \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság igaz, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság adatait a másodlagos sorozatokhoz, a \#getCategories.getCategories tulajdonság adatait pedig az elsődleges sorozatokhoz használják.

**Visszatér:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Ha hamis, akkor a \#getSecondaryCategories.getSecondaryCategories tulajdonság null értéket ad vissza, és a \#getCategories.getCategories tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha igaz, akkor a \#getSecondaryCategories.getSecondaryCategories tulajdonság adatait a másodlagos sorozatokhoz, a \#getCategories.getCategories tulajdonság adatait pedig az elsődleges sorozatokhoz használják. Olvasás/írás boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // kapcsolódó kategóriák: series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // kapcsolódó kategóriák: series.getChart().getChartData().getCategories()
>  }
> ```

**Visszatér:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Ha hamis, akkor a \#getSecondaryCategories.getSecondaryCategories tulajdonság null értéket ad vissza, és a \#getCategories.getCategories tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha igaz, akkor a \#getSecondaryCategories.getSecondaryCategories tulajdonság adatait a másodlagos sorozatokhoz, a \#getCategories.getCategories tulajdonság adatait pedig az elsődleges sorozatokhoz használják. Olvasás/írás boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // kapcsolódó kategóriák: series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // kapcsolódó kategóriák: series.getChart().getChartData().getCategories()
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

A másodlagos kategóriákat adja vissza, ha a \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság igaz. Csak olvasható [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // kapcsolódó kategóriák: series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // kapcsolódó kategóriák: series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Ha \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság hamis, akkor ez a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad vissza, és a \#getCategories.getCategories tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság igaz, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság adatait a másodlagos sorozatokhoz, a \#getCategories.getCategories tulajdonság adatait pedig az elsődleges sorozatokhoz használják.

**Visszatér:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Az belső Excel munkafüzetet egy memóriában lévő adatfolyamba írja.

**Visszatér:**
byte[] - Egy byte tömb példányt ad vissza, amely a belsőleg tartalmazott Excel munkafüzet másolatát tartalmazza.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

A belső Excel munkafüzetet a felhasználó által megadott értékkel inicializálja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ms | byte[] | A felhasználó által megadott adatfolyam, amely a teljes Excel munkafüzetet tartalmazza. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Külső munkafüzet útvonalat képviseli, ha külső adatforrás, egyébként null.

**Visszatér:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

A diagram adatforrását képviseli.

**Visszatér:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

A beágyazott munkafüzet típusát adja vissza. [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) értéket ad vissza, ha a DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Csak olvasható [WorkbookType](../../com.aspose.slides/workbooktype).

**Visszatér:**
int

### getRange() {#getRange--}
```
public final String getRange()
```

A diagram adat tartományát adja vissza.

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

**Visszatér:**
java.lang.String - A cellák adat tartományának képlete. Például: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Beállítja a diagram adat tartományát. A sorozatok és kategóriák az új adat tartomány alapján frissülnek. Ha a adat tartományban lévő sorozatok száma nagyobb, mint a diagram adatban lévő sorozatok száma, akkor további sorozatok a jelenlegi gyűjtemény utolsó sorozatának típusával megegyezően kerülnek a gyűjtemény végére.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formula | java.lang.String | A cellák adat tartományának képlete. Például: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Külső munkafüzetet állít be adatforrásként a diagramhoz. A diagram adatai a cél munkafüzetről frissülnek.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| workbookPath | java.lang.String | A cél munkafüzet elérési útja |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Külső munkafüzetet állít be adatforrásként a diagramhoz.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| workbookPath | java.lang.String | A cél munkafüzet elérési útja |
| updateChartData | boolean | Ha az érték hamis, csak a munkafüzet útvonal frissül. A diagram adatai nem töltődnek be és nem frissülnek a cél munkafüzetről. Akkor használható, ha a cél munkafüzet nem létezik vagy nem érhető el. Ha az érték igaz, a diagram adatai a cél munkafüzetről frissülnek. |

### refreshData() {#refreshData--}
```
public final void refreshData()
```

A diagram adatokat frissíti a forrás munkafüzetből újratöltve.

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

Az adatokat áthelyezi az tengelyek között. Az X tengelyen ábrázolt adatok az Y tengelyre kerülnek, és fordítva.