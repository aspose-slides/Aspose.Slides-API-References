---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Az ábra ábrázolásához használt adatokat képviseli.
type: docs
url: /hu/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Az ábra ábrázolásához használt adatokat képviseli.
## Módszerek

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | A cellagyárat adja vissza, amely a diagram sorozatokhoz vagy kategóriákhoz használt cellákat hozza létre. |
| [getSeries()](#getSeries--) | A sorozatokat adja vissza. |
| [getSeriesGroups()](#getSeriesGroups--) | A sorozatcsoportokat adja vissza. |
| [getCategories()](#getCategories--) | Az elsődleges kategóriákat adja vissza (vagy mind az elsődleges, mind a másodlagos kategóriákat, ha a (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság hamis). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Ha hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad vissza, és a (\#getCategories.getCategories) tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Ha hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad vissza, és a (\#getCategories.getCategories) tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. |
| [getSecondaryCategories()](#getSecondaryCategories--) | A másodlagos kategóriákat adja vissza, ha a (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság igaz. |
| [readWorkbookStream()](#readWorkbookStream--) | A belső Excel munkafüzetet egy memóriabeli streambe írja. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | A belső Excel munkafüzetet a felhasználó által megadott értékkel inicializálja. |
| [setRange(String formula)](#setRange-java.lang.String-) | Beállítja a diagram adat intervallumát. |
| [getRange()](#getRange--) | A diagram adat intervallumát adja vissza. |
| [getDataSourceType()](#getDataSourceType--) | A diagram adatforrását képviseli. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Külső munkafüzet útvonalát jelöli, ha az adatforrás külső, egyébként null. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | A beágyazott munkafüzet típusát adja vissza. |
| [switchRowColumn()](#switchRowColumn--) | Az adatokat felcseréli a tengelyek között. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Külső munkafüzetet állít be adatforrásként a diagramhoz. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Külső munkafüzetet állít be adatforrásként a diagramhoz. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```

A cellagyárat adja vissza, amely a diagram sorozatokhoz vagy kategóriákhoz használt cellákat hozza létre. Csak olvasható [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Visszatér:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```

A sorozatokat adja vissza. Csak olvasható [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Visszatér:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```

A sorozatcsoportokat adja vissza. Csak olvasható [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Minden sorozatcsoport olyan sorozatokat tartalmaz, amelyek kombinálható típusúak. A kombinálható sorozattípusok csoportjait a CombinableSeriesTypesGroup enum definiálja és írja le. Emellett minden sorozatcsoport olyan sorozatot tartalmaz, amely vagy elsődleges, vagy másodlagos tengelyen ábrázolt (nem mindkét eset egyszerre egy csoportban). Így a sorozatcsoportosítás elve a fent említett típuscsoportok és az elsődleges/másodlagos ábrázolási típus szerinti csoportosítás.
2) A sorozatcsoport néhány sorozati tulajdonságot tartalmaz, amely közös minden sorozatra a csoportban („series group properties”). A ChartSeriesGroup osztályban a „series group properties” olvasható/írható. Minden „series group property” rendelkezhet csak olvasható leképezéssel a ChartSeries osztályban.

**Visszatér:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```

Az elsődleges kategóriákat adja vissza (vagy mind az elsődleges, mind a másodlagos kategóriákat, ha a (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság hamis). Csak olvasható [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Ha a (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad vissza, és a (\#getCategories.getCategories) tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha a (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság igaz, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság adatai a másodlagos sorozatokhoz, a (\#getCategories.getCategories) tulajdonság adatai pedig az elsődleges sorozatokhoz használatosak.

**Visszatér:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```

Ha hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad vissza, és a (\#getCategories.getCategories) tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha igaz, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság adatai a másodlagos sorozatokhoz, a (\#getCategories.getCategories) tulajdonság adatai pedig az elsődleges sorozatokhoz használatosak. Olvasható/írható boolean.

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

Ha hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad vissza, és a (\#getCategories.getCategories) tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha igaz, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság adatai a másodlagos sorozatokhoz, a (\#getCategories.getCategories) tulajdonság adatai pedig az elsődleges sorozatokhoz használatosak. Olvasható/írható boolean.

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```

A másodlagos kategóriákat adja vissza, ha a (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság igaz. Csak olvasható [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Ha a (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság hamis, akkor ez a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad vissza, és a (\#getCategories.getCategories) tulajdonság adatai mind az elsődleges, mind a másodlagos sorozatokhoz használatosak. Ha a (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság igaz, akkor ebben a (\#getSecondaryCategories.getSecondaryCategories) tulajdonságban lévő adat a másodlagos sorozatokhoz, a (\#getCategories.getCategories) tulajdonságban lévő adat pedig az elsődleges sorozatokhoz használatos.

**Visszatér:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```

A belső Excel munkafüzetet egy memóriabeli streambe írja.

**Visszatér:**
byte[] - Visszaad egy bájt tömböt, amely a belső Excel munkafüzet másolatát tartalmazza.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```

A belső Excel munkafüzetet a felhasználó által megadott értékkel inicializálja.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| ms | byte[] | A felhasználó által biztosított stream, amely tartalmazza a teljes Excel munkafüzetet. |
### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```

Beállítja a diagram adat intervallumát. A sorozatok és kategóriák az új adatintervallum alapján frissülnek. Ha az adatintervallumban lévő sorozatok száma nagyobb, mint a diagram adat sorozatok száma, akkor további sorozatok kerülnek hozzáadásra a gyűjtemény végéhez, a legutolsó sorozat típusával megegyező típusban.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| formula | java.lang.String | A cellák adatintervallum képlete. Pl.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |
### getRange() {#getRange--}
```
public abstract String getRange()
```

A diagram adat intervallumát adja vissza.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Visszatér:**
java.lang.String - Cellák adatintervallum képlete. Pl.: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```

A diagram adatforrását képviseli.

**Visszatér:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```

Külső munkafüzet útvonalát jelöli, ha az adatforrás külső, egyébként null.

**Visszatér:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```

A beágyazott munkafüzet típusát adja vissza. [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined)-t ad vissza, ha a DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Csak olvasható [WorkbookType](../../com.aspose.slides/workbooktype).

**Visszatér:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```

Az adatokat felcseréli a tengelyek között. Az X tengelyen ábrázolt adatok a Y tengelyre, és fordítva kerülnek áthelyezésre.
### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
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
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | A cél munkafüzet elérési útja |
### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Külső munkafüzetet állít be adatforrásként a diagramhoz.

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
| Parameter | Type | Description |
| --- | --- | --- |
| workbookPath | java.lang.String | A cél munkafüzet elérési útja |
| updateChartData | boolean | Ha az érték hamis, csak a munkafüzet útvonala frissül. A diagram adat nem töltődik be és nem frissül a cél munkafüzetről. Használható, ha a cél munkafüzet nem létezik vagy nem érhető el. Ha az érték igaz, a diagram adat frissül a cél munkafüzetről. |