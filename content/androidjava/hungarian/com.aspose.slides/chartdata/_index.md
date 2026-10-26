---
title: ChartData
second_title: Aspose.Slides Androidhoz Java API hivatkozással
description: A diagram ábrázolásához használt adatokat képviseli.
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

Az ábra kirajzolásához használt adatokat képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Lekéri a cellagyárat a diagram sorozatokhoz vagy kategóriákhoz használt cellák létrehozásához. |
| [getSeries()](#getSeries--) | Lekéri a sorozatokat. |
| [getSeriesGroups()](#getSeriesGroups--) | Lekéri a sorozatcsoportokat. |
| [getCategories()](#getCategories--) | Lekéri az elsődleges kategóriákat (vagy mind az elsődleges, mind a másodlagos kategóriákat, ha #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság hamis). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Ha hamis, akkor a #getSecondaryCategories.getSecondaryCategories tulajdonság null értéket ad vissza, és a #getCategories.getCategories tulajdonság adata mind az elsődleges, mind a másodlagos sorozatokhoz használatos. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Ha hamis, akkor a #getSecondaryCategories.getSecondaryCategories tulajdonság null értéket ad vissza, és a #getCategories.getCategories tulajdonság adata mind az elsődleges, mind a másodlagos sorozatokhoz használatos. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Lekéri a másodlagos kategóriákat, ha a #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság igaz. |
| [readWorkbookStream()](#readWorkbookStream--) | Az belsőleg tárolt Excel munkafüzetet egy memóriában lévő folyamba írja. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Inicializálja a belsőleg tárolt Excel munkafüzetet a felhasználó által megadott értékkel. |
| [getDataSourceType()](#getDataSourceType--) | Külső munkafüzet útvonalát képviseli, ha külső adatforrás, egyébként null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | A diagram adatforrását képviseli. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Lekéri a beágyazott munkafüzet típusát. |
| [getRange()](#getRange--) | Lekéri a diagram adat tartományát. |
| [setRange(String formula)](#setRange-java.lang.String-) | Beállítja a diagram adat tartományát. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Külső munkafüzetet állít be a diagram adatforrásaként. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Külső munkafüzetet állít be a diagram adatforrásaként. |
| [switchRowColumn()](#switchRowColumn--) | Megcseréli az adatokat a tengelyek között. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Lekéri a cellagyárat a diagram sorozatokhoz vagy kategóriákhoz használt cellák létrehozásához. Csak olvasható [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Visszatérési érték:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Lekéri a sorozatokat. Csak olvasható [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Visszatérési érték:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Lekéri a sorozatcsoportokat. Csak olvasható [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek kombinálható típusúak. A kombinálható sorozattípusok csoportjait a CombinableSeriesTypesGroup felsoroló határozza meg és írja le. Emellett minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek vagy az elsődleges tengelyen, vagy a másodlagos tengelyen kerülnek ábrázolásra (nem mindkét eset egyszerre egy csoportban). Így a sorozatcsoportosítás alapelve a fent említett típuscsoportok szerinti csoportosítás és az elsődleges/másodlagos ábrázolási típus szerinti csoportosítás.  
2) Egy sorozatcsoport tartalmaz néhány sorozatra jellemző tulajdonságot, amely közös minden csoportbeli sorozatra („sorozatcsoport tulajdonságok”). A „Series group properties” a ChartSeriesGroup osztályban olvasható/írható. Minden „series group property”-nek lehet egy csak olvasható változata a ChartSeries osztályban.

**Visszatérési érték:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Lekéri az elsődleges kategóriákat (vagy mind az elsődleges, mind a másodlagos kategóriákat, ha a #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság hamis). Csak olvasható [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Ha a #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság hamis, akkor a (#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad vissza, és a #getCategories.getCategories tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha a #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság igaz, akkor a (#getSecondaryCategories.getSecondaryCategories) tulajdonság adatai a másodlagos sorozatokhoz, a #getCategories.getCategories tulajdonság adatai pedig az elsődleges sorozatokhoz használatosak.

**Visszatérési érték:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Ha hamis, akkor a #getSecondaryCategories.getSecondaryCategories tulajdonság null értéket ad vissza, és a #getCategories.getCategories tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha igaz, akkor a #getSecondaryCategories.getSecondaryCategories tulajdonság adatai a másodlagos sorozatokhoz, a #getCategories.getCategories tulajdonság adatai pedig az elsődleges sorozatokhoz használatosak. Olvasható/írható logikai érték.

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

Ha hamis, akkor a #getSecondaryCategories.getSecondaryCategories tulajdonság null értéket ad vissza, és a #getCategories.getCategories tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha igaz, akkor a #getSecondaryCategories.getSecondaryCategories tulajdonság adatai a másodlagos sorozatokhoz, a #getCategories.getCategories tulajdonság adatai pedig az elsődleges sorozatokhoz használatosak. Olvasható/írható logikai érték.

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

Lekéri a másodlagos kategóriákat, ha a #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság igaz. Csak olvasható [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Ha a #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság hamis, akkor ez a (#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad vissza, és a #getCategories.getCategories tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha a #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) tulajdonság igaz, akkor ennek a #getSecondaryCategories.getSecondaryCategories tulajdonságnak az adatai a másodlagos sorozatokhoz, a #getCategories.getCategories tulajdonság adatai pedig az elsődleges sorozatokhoz használatosak.

**Visszatérési érték:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Az belsőleg tárolt Excel munkafüzetet egy memóriában lévő folyamba írja.

**Visszatérési érték:**
byte[] - Visszaad egy bájt tömb példányt, amely a belsőleg tárolt Excel munkafüzet másolatát tartalmazza.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Inicializálja a belsőleg tárolt Excel munkafüzetet a felhasználó által megadott értékkel.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ms | byte[] | A felhasználó által biztosított folyam, amely az egész Excel munkafüzetet tartalmazza. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Külső munkafüzet útvonalát jelöli, ha külső adatforrás, ellenkező esetben null.

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

Lekéri a beágyazott munkafüzet típusát. [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) értéket ad vissza, ha a DataSourceType (#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Csak olvasható [WorkbookType](../../com.aspose.slides/workbooktype).

**Visszatérési érték:**
int
### getRange() {#getRange--}
```
public final String getRange()
```

Lekéri a diagram adat tartományát.

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
java.lang.String - A cellák adat tartomány képlete. Például: "Sheet1!$A$1:$C$4"
### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Beállítja a diagram adat tartományát. A sorozatok és kategóriák az új adat tartomány alapján frissülnek. Ha a adat tartományban lévő sorozatok száma nagyobb, mint a diagram adatában lévő sorozatok száma, akkor további sorozatok, melyek típusa megegyezik a jelenlegi kollekció utolsó sorozatával, a kollekció végéhez lesznek hozzáadva.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formula | java.lang.String | A cellák adat tartomány képlete. Például: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Külső munkafüzetet állít be a diagram adatforrásaként. A diagram adatai a cél munkafüzetből lesznek frissítve.

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
| workbookPath | java.lang.String | Az cél munkafüzet elérési útja |

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
| workbookPath | java.lang.String | Az cél munkafüzet elérési útja |
| updateChartData | boolean | Ha az érték hamis, csak a munkafüzet útvonal lesz frissítve. A diagram adatai nem lesznek betöltve és frissítve a cél munkafüzetről. Használható, ha a cél munkafüzet nem létezik vagy nem érhető el. Ha az érték igaz, a diagram adatai a cél munkafüzetről lesznek frissítve. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Megcseréli az adatokat a tengelyeken. Az X tengelyen ábrázolt adatok a Y tengelyre, és fordítva, kerülnek áthelyezésre.