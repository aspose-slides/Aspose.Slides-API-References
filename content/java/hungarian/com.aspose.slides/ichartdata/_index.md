---
title: IChartData
second_title: Aspose.Slides for Java API Referenciája
description: Diagramábrázoláshoz használt adatokat képviseli.
type: docs
url: /hu/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Diagramábrázoláshoz használt adatokat képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | A cellagyár lekérése a diagram sorozatokhoz vagy kategóriákhoz használt cellák létrehozásához. |
| [getSeries()](#getSeries--) | A sorozatok lekérése. |
| [getSeriesGroups()](#getSeriesGroups--) | A sorozatok csoportjainak lekérése. |
| [getCategories()](#getCategories--) | Az elsődleges kategóriák (vagy az elsődleges és másodlagos kategóriák is, ha (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság hamis). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Ha hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad, és a (\#getCategories.getCategories) tulajdonság adatait használják az elsődleges és másodlagos sorozatokhoz egyaránt. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Ha hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad, és a (\#getCategories.getCategories) tulajdonság adatait használják az elsődleges és másodlagos sorozatokhoz egyaránt. |
| [getSecondaryCategories()](#getSecondaryCategories--) | A másodlagos kategóriák lekérése, ha a (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság igaz. |
| [readWorkbookStream()](#readWorkbookStream--) | A belső Excel munkafüzetet egy memóriafolyamba írja. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | A belső Excel munkafüzetet a felhasználó által megadott értékkel inicializálja. |
| [setRange(String formula)](#setRange-java.lang.String-) | Diagramadat-tartomány beállítása. |
| [getRange()](#getRange--) | Diagramadat-tartomány lekérése. |
| [getDataSourceType()](#getDataSourceType--) | A diagram adatforrását képviseli |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Külső munkafüzet útvonalát adja vissza, ha az adatforrás külső, egyébként null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | A beágyazott munkafüzet típusának lekérése. |
| [switchRowColumn()](#switchRowColumn--) | Az adatok áthelyezése a tengelyen. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Külső munkafüzet beállítása adatforrásként a diagramhoz. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Külső munkafüzet beállítása adatforrásként a diagramhoz. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```


A cellagyár lekérése a diagram sorozatokhoz vagy kategóriákhoz használt cellák létrehozásához. Csak olvasható [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Visszatér:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```


A sorozatok lekérése. Csak olvasható [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Visszatér:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```


A sorozatok csoportjainak lekérése. Csak olvasható [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Minden sorozatcsoport kombinálható típusú sorozatokat tartalmaz. A kombinálható sorozattípusokat a CombinableSeriesTypesGroup felsorolt típus definiálja és írja le. Emellett minden sorozatcsoport olyan sorozatokat tartalmaz, amelyeket vagy elsődleges, vagy másodlagos tengelyen ábrázolnak (nem mindkettő egy csoportban). Tehát a sorozatcsoportosítás elve a fent említett típuscsoportok és az elsődleges/másodlagos ábrázolási típus szerinti csoportosítás. 2) A sorozatcsoport néhány sorozattulajdonságot tartalmaz, amelyek közösek a csoport minden sorozatára („sorozatcsoport tulajdonságok”). A ChartSeriesGroup osztályban a „sorozatcsoport tulajdonságok” olvasás/írás módúak. Minden „sorozatcsoport tulajdonságnak” lehet csak olvasható leképezése a ChartSeries osztályban.

**Visszatér:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```


Az elsődleges kategóriák lekérése (vagy az elsődleges és másodlagos kategóriák is, ha (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság hamis). Csak olvasható [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Ha a (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad, és ebben a (\#getCategories.getCategories) tulajdonságban lévő adatot használják mind az elsődleges, mind a másodlagos sorozatokhoz. Ha a tulajdonság igaz, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonságban lévő adatot használják a másodlagos sorozatokhoz, az ebben a (\#getCategories.getCategories) tulajdonságban lévő adatot pedig az elsődleges sorozatokhoz.

**Visszatér:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```


Ha hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad, és a (\#getCategories.getCategories) tulajdonság adatait használják az elsődleges és másodlagos sorozatokhoz egyaránt. Ha igaz, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság adatait használják a másodlagos sorozatokhoz, a (\#getCategories.getCategories) tulajdonság adatait pedig az elsődleges sorozatokhoz. Olvasás/írás boolean.

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


Ha hamis, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad, és a (\#getCategories.getCategories) tulajdonság adatait használják az elsődleges és másodlagos sorozatokhoz egyaránt. Ha igaz, akkor a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság adatait használják a másodlagos sorozatokhoz, a (\#getCategories.getCategories) tulajdonság adatait pedig az elsődleges sorozatokhoz. Olvasás/írás boolean.

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
public abstract IChartCategoryCollection getSecondaryCategories()
```


A másodlagos kategóriák lekérése, ha a (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság igaz. Csak olvasható [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Ha a (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) tulajdonság hamis, akkor ez a (\#getSecondaryCategories.getSecondaryCategories) tulajdonság null értéket ad, és a (\#getCategories.getCategories) tulajdonság adatait használják az elsődleges és másodlagos sorozatokhoz egyaránt. Ha a tulajdonság igaz, akkor ebben a (\#getSecondaryCategories.getSecondaryCategories) tulajdonságban lévő adatot használják a másodlagos sorozatokhoz, a (\#getCategories.getCategories) tulajdonság adatait pedig az elsődleges sorozatokhoz.

**Visszatér:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```


A belső Excel munkafüzetet egy memóriafolyamba írja.

**Visszatér:**
byte[] - Visszaad egy bájt tömböt, amely a belső Excel munkafüzet másolatát tartalmazza.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```


A belső Excel munkafüzetet a felhasználó által megadott értékkel inicializálja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| ms | byte[] | A felhasználó által biztosított adatfolyam, amely a teljes Excel munkafüzetet tartalmazza. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```


Diagramadat-tartomány beállítása. A sorozatok és kategóriák az új adat-tartomány alapján frissülnek. Ha a adat-tartományban lévő sorozatok száma nagyobb, mint a diagram adatban lévő sorozatok száma, akkor további sorozatok kerülnek hozzáadásra a jelenlegi gyűjtemény utolsó sorozatának típusával megegyező típusban a gyűjtemény végére.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| formula | java.lang.String | A cellák adat-tartományának képlete. Pl.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```


Diagramadat-tartomány lekérése.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Visszatér:**
java.lang.String - A cellák adat-tartományának képlete. Pl.: "Sheet1!$A$1:$C$4"
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


Külső munkafüzet útvonalát adja vissza, ha az adatforrás külső, egyébként null

**Visszatér:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```


A beágyazott munkafüzet típusának lekérése. [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) értékkel tér vissza, ha a DataSourceType (\#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Csak olvasható [WorkbookType](../../com.aspose.slides/workbooktype).

**Visszatér:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```


Az adat áthelyezése a tengelyen. Az X tengelyen ábrázolt adat áthelyeződik a Y tengelyre és fordítva.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```


Külső munkafüzet beállítása adatforrásként a diagramhoz. A diagram adatai a célmunkafüzettel frissülnek.

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


Külső munkafüzet beállítása adatforrásként a diagramhoz.

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
| updateChartData | boolean | Ha az érték hamis, csak a munkafüzet útvonala frissül. A diagram adatai nem töltődnek be és nem frissülnek a célmunkafüzettel. Akkor használható, ha a célmunkafüzet nem létezik vagy nem érhető el. Ha az érték igaz, a diagram adatai a célmunkafüzettel frissülnek. |