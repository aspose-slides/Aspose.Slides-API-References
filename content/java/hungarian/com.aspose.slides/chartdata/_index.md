---
title: ChartData
second_title: Aspose.Slides Java API referencia
description: A diagram ábrázolásához használt adatokat reprezentálja.
type: docs
url: /hu/com.aspose.slides/chartdata/
---
**Öröklés:**
java.lang.Object, com.aspose.slides.DomObject

**Minden megvalósított interfész:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

A diagram ábrázolásához használt adatokat képviseli.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | A cellagyárat adja vissza, amely a diagram sorozataihoz vagy kategóriáihoz használt cellákat hozza létre. |
| [getSeries()](#getSeries--) | A sorozatokat adja vissza. |
| [getSeriesGroups()](#getSeriesGroups--) | A sorozatcsoportokat adja vissza. |
| [getCategories()](#getCategories--) | Az elsődleges kategóriákat adja vissza (vagy mind az elsődleges, mind a másodlagos kategóriákat, ha a \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Ha hamis, akkor a \#getSecondaryCategories.getSecondaryCategories tulajdonság null értéket ad vissza, és a \#getCategories.getCategories tulajdonság adatait használják mind az elsődleges, mind a másodlagos sorozatokhoz. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Ha hamis, akkor a \#getSecondaryCategories.getSecondaryCategories tulajdonság null értéket ad vissza, és a \#getCategories.getCategories tulajdonság adatait használják mind az elsődleges, mind a másodlagos sorozatokhoz. |
| [getSecondaryCategories()](#getSecondaryCategories--) | A másodlagos kategóriákat adja vissza, ha a \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság true. |
| [readWorkbookStream()](#readWorkbookStream--) | Az internálisan tárolt Excel munkafüzetet egy memóriában lévő adatfolyamba írja. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Az internálisan tartalmazott Excel munkafüzetet felhasználó által megadott értékkel inicializálja. |
| [getDataSourceType()](#getDataSourceType--) | Külső munkafüzet útvonalát jelöli, ha külső adatforrás, egyébként null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | A diagram adatforrását jelöli. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | A beágyazott munkafüzet típusát adja vissza. |
| [getRange()](#getRange--) | A diagram adatválasztékát adja vissza. |
| [setRange(String formula)](#setRange-java.lang.String-) | A diagram adatválasztékát állítja be. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Külső munkafüzetet állít be a diagram adatforrásaként. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Külső munkafüzetet állít be a diagram adatforrásaként. |
| [switchRowColumn()](#switchRowColumn--) | Az adatokat az tengelyek között cseréli. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

A cellagyárat adja vissza, amely a diagram sorozataihoz vagy kategóriáihoz használt cellákat hozza létre. Csak olvasható [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Visszatérési érték:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

A sorozatokat adja vissza. Csak olvasható [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Visszatérési érték:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

A sorozatcsoportokat adja vissza. Csak olvasható [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek kombinálható típusúak. A kombinálható sorozattípusok csoportjait a CombinableSeriesTypesGroup felsoroló típus definiálja és írja le. Emellett minden sorozatcsoport olyan sorozatokat tartalmaz, amelyeket vagy az elsődleges, vagy a másodlagos tengelyen ábrázolnak (nem mindkét eset egyszerre egy csoportban). Így a sorozatcsoportosítás elve a fenti típuscsoportok és az elsődleges/másodlagos ábrázolási típus szerinti csoportosítás. 2) A sorozatcsoport néhány sorozattulajdonságot tartalmaz, amely közös minden csoportbeli sorozatra („sorozatcsoport tulajdonságok”). A „Series group properties” a ChartSeriesGroup osztályban olvasható/írható. Minden „series group property” rendelkezhet csak olvasható projekcióval a ChartSeries osztályban.

**Visszatérési érték:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Az elsődleges kategóriákat adja vissza (vagy mind az elsődleges, mind a másodlagos kategóriákat, ha a \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság false). Csak olvasható [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Ha a \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság false, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad vissza, és a \#getCategories.getCategories tulajdonság adatait használják mind az elsődleges, mind a másodlagos sorozatokhoz. Ha a \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság true, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság adatait a másodlagos sorozatokhoz, a \#getCategories.getCategories tulajdonság adatait pedig az elsődleges sorozatokhoz használják.

**Visszatérési érték:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Ha hamis, akkor a \#getSecondaryCategories.getSecondaryCategories tulajdonság null értéket ad vissza, és a \#getCategories.getCategories tulajdonság adatait használják mind az elsődleges, mind a másodlagos sorozatokhoz. Ha igaz, akkor a \#getSecondaryCategories.getSecondaryCategories tulajdonság adatait a másodlagos sorozatokhoz, a \#getCategories.getCategories tulajdonság adatait pedig az elsődleges sorozatokhoz használják. Olvasható/írható boolean.

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


**Visszatérési érték:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Ha hamis, akkor a \#getSecondaryCategories.getSecondaryCategories tulajdonság null értéket ad vissza, és a \#getCategories.getCategories tulajdonság adatait használják mind az elsődleges, mind a másodlagos sorozatokhoz. Ha igaz, akkor a \#getSecondaryCategories.getSecondaryCategories tulajdonság adatait a másodlagos sorozatokhoz, a \#getCategories.getCategories tulajdonság adatait pedig az elsődleges sorozatokhoz használják. Olvasható/írható boolean.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

A másodlagos kategóriákat adja vissza, ha a \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság true. Csak olvasható [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Ha a \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság false, akkor ez a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad vissza, és a \#getCategories.getCategories tulajdonság adatait használják mind az elsődleges, mind a másodlagos sorozatokhoz. Ha a \#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság true, akkor ennek a \#getSecondaryCategories.getSecondaryCategories tulajdonságnak az adatait a másodlagos sorozatokhoz, a \#getCategories.getCategories tulajdonság adatait pedig az elsődleges sorozatokhoz használják.

**Visszatérési érték:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Az internálisan tartalmazott Excel munkafüzetet egy memóriában lévő adatfolyamba írja.

**Visszatérési érték:**
byte[] - Visszaad egy byte tömb példányt, amely az internálisan tartalmazott Excel munkafüzet másolatát tartalmazza.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Az internálisan tartalmazott Excel munkafüzetet felhasználó által megadott értékkel inicializálja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ms | byte[] | A felhasználó által megadott adatfolyam, amely az egész Excel munkafüzetet tartalmazza. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Külső munkafüzet útvonalát jelöli, ha külső adatforrás, egyébként null.

**Visszatérési érték:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

A diagram adatforrását jelöli.

**Visszatérési érték:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

A beágyazott munkafüzet típusát adja vissza. [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) értéket ad, ha a DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Csak olvasható [WorkbookType](../../com.aspose.slides/workbooktype).

**Visszatérési érték:**
int

### getRange() {#getRange--}
```
public final String getRange()
```

A diagram adatválasztékát adja vissza.

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

**Visszatérési érték:**
java.lang.String - A cellák adatválaszték formula. Például: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

A diagram adatválasztékát állítja be. A sorozatok és kategóriák az új adatválaszték alapján frissülnek. Ha az adatválasztékban lévő sorozatok száma nagyobb, mint a diagram adatainak sorozatszáma, akkor további sorozatok kerülnek hozzáadásra a gyűjtemény végéhez, ugyanazzal a típussal, mint az aktuális gyűjtemény utolsó sorozata.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formula | java.lang.String | A cellák adatválaszték formula. Például: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Külső munkafüzetet állít be a diagram adatforrásaként. A diagram adatai a célmunkafüzettől frissülnek.

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
| workbookPath | java.lang.String | A célmunkafüzet elérési útja |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Külső munkafüzetet állít be a diagram adatforrásaként.

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
| workbookPath | java.lang.String | A célmunkafüzet elérési útja |
| updateChartData | boolean | Ha az érték false, csak a munkafüzet útvonala frissül. A diagram adatai nem töltődnek be, és nem frissülnek a célmunkafüzettől. Akkor használható, ha a célmunkafüzet nem létezik vagy nem érhető el. Ha az érték true, a diagram adatai a célmunkafüzettől frissülnek. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Az adatokat az tengelyek között cseréli. A X tengelyen ábrázolt adatok a Y tengelyre, és fordítva kerülnek.