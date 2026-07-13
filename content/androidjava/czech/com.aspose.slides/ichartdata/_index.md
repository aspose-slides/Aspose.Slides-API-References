---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Představuje data používaná pro vykreslování grafu.
type: docs
url: /cs/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Představuje data používaná pro vykreslování grafu.
## Metody

| Method | Description |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Získá továrnu na buňky pro vytvoření buněk používaných pro sérii grafu nebo kategorie. |
| [getSeries()](#getSeries--) | Získá sérii. |
| [getSeriesGroups()](#getSeriesGroups--) | Získá skupiny sérií. |
| [getCategories()](#getCategories--) | Získá primární kategorie (nebo jak primární, tak sekundární kategorie, pokud je vlastnost (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Pokud je false, pak vlastnost (\#getSecondaryCategories.getSecondaryCategories) vrátí null a data ve vlastnosti (\#getCategories.getCategories) jsou použita jak pro primární, tak pro sekundární série. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Pokud je false, pak vlastnost (\#getSecondaryCategories.getSecondaryCategories) vrátí null a data ve vlastnosti (\#getCategories.getCategories) jsou použita jak pro primární, tak pro sekundární série. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Získá sekundární kategorie, pokud je vlastnost (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true. |
| [readWorkbookStream()](#readWorkbookStream--) | Zapíše interně obsažený Excel sešit do paměťového proudu. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Inicializuje interně obsažený Excel sešit uživatelem zadanou hodnotou. |
| [setRange(String formula)](#setRange-java.lang.String-) | Nastaví rozsah dat grafu. |
| [getRange()](#getRange--) | Získá rozsah dat grafu. |
| [getDataSourceType()](#getDataSourceType--) | Představuje zdroj dat grafu |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Představuje cestu k externímu sešitu, pokud je zdroj dat externí, jinak null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Získá typ vloženého sešitu. |
| [switchRowColumn()](#switchRowColumn--) | Prohodí data podél osy. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Nastaví externí sešit jako zdroj dat pro graf. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Nastaví externí sešit jako zdroj dat pro graf. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```


Získá továrnu na buňky pro vytvoření buněk používaných pro sérii grafu nebo kategorie. Pouze pro čtení [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Vrací:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```


Získá sérii. Pouze pro čtení [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Vrací:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```


Získá skupiny sérií. Pouze pro čtení [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

1) Každá skupina sérií obsahuje série s kombinovatelnými typy. Skupiny kombinovatelných typů sérií jsou definovány a popsané pomocí výčtu CombinableSeriesTypesGroup. Dále každá skupina sérií obsahuje série, které jsou vykresleny buď na primární ose, nebo na sekundární ose (nikoli oba případy ve stejné skupině). Princip seskupování sérií tedy spočívá ve seskupování podle výše zmíněných typových skupin a podle typu vykreslování – primární/sekundární. 2) Skupina sérií obsahuje některé vlastnosti sérií, které jsou společné pro každou sérii ve skupině („vlastnosti skupiny sérií“). „Vlastnosti skupiny sérií“ ve třídě ChartSeriesGroup jsou čtení/zápis. Každá z „vlastností skupiny sérií“ může mít pouze pro čtení projekci ve třídě ChartSeries.

**Vrací:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```


Získá primární kategorie (nebo jak primární, tak sekundární kategorie, pokud je vlastnost (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false). Pouze pro čtení [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // související kategorie jsou series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // související kategorie jsou series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Pokud je vlastnost (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false, pak vlastnost (\#getSecondaryCategories.getSecondaryCategories) vrátí null a data v této vlastnosti (\#getCategories.getCategories) jsou použita jak pro primární, tak pro sekundární série. Pokud je tato vlastnost true, pak data ve vlastnosti (\#getSecondaryCategories.getSecondaryCategories) jsou použita pro sekundární série a data v této vlastnosti (\#getCategories.getCategories) jsou použita pro primární série.

**Vrací:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```


Pokud je false, pak vlastnost (\#getSecondaryCategories.getSecondaryCategories) vrátí null a data ve vlastnosti (\#getCategories.getCategories) jsou použita jak pro primární, tak pro sekundární série. Pokud je true, pak data ve vlastnosti (\#getSecondaryCategories.getSecondaryCategories) jsou použita pro sekundární série a data ve vlastnosti (\#getCategories.getCategories) jsou použita pro primární série. Čtení/zápis boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // související kategorie jsou series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // související kategorie jsou series.getChart().getChartData().getCategories()
>  }
> ```

**Vrací:**
boolean
### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public abstract void setUseSecondaryCategories(boolean value)
```


Pokud je false, pak vlastnost (\#getSecondaryCategories.getSecondaryCategories) vrátí null a data ve vlastnosti (\#getCategories.getCategories) jsou použita jak pro primární, tak pro sekundární série. Pokud je true, pak data ve vlastnosti (\#getSecondaryCategories.getSecondaryCategories) jsou použita pro sekundární série a data ve vlastnosti (\#getCategories.getCategories) jsou použita pro primární série. Čtení/zápis boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // související kategorie jsou series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // související kategorie jsou series.getChart().getChartData().getCategories()
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public abstract IChartCategoryCollection getSecondaryCategories()
```


Získá sekundární kategorie, pokud je vlastnost (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) true. Pouze pro čtení [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // související kategorie jsou series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // související kategorie jsou series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Pokud je vlastnost (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) false, pak tato vlastnost (\#getSecondaryCategories.getSecondaryCategories) vrátí null a data ve vlastnosti (\#getCategories.getCategories) jsou použita jak pro primární, tak pro sekundární série. Pokud je tato vlastnost true, pak data v této vlastnosti (\#getSecondaryCategories.getSecondaryCategories) jsou použita pro sekundární série a data v této vlastnosti (\#getCategories.getCategories) jsou použita pro primární série.

**Vrací:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```


Zapíše interně obsažený Excel sešit do paměťového proudu.

**Vrací:**
byte[] - Vrací pole bytů obsahující kopii interně obsaženého Excel sešitu.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```


Inicializuje interně obsažený Excel sešit uživatelem zadanou hodnotou.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| ms | byte[] | Uživatelem poskytnutý proud obsahující celý Excel sešit. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```


Nastaví rozsah dat grafu. Série a kategorie budou aktualizovány na základě nového rozsahu dat. Pokud je počet sérií v rozsahu dat větší než počet sérií v datech grafu, budou na konec kolekce přidány další série se stejným typem jako poslední série v aktuální kolekci.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| formula | java.lang.String | Vzorec rozsahu buněk. Např.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```


Získá rozsah dat grafu.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Vrací:**
java.lang.String - Vzorec rozsahu buněk. Např.: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Představuje zdroj dat grafu

**Vrací:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```


Představuje cestu k externímu sešitu, pokud je zdroj dat externí, jinak null

**Vrací:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```


Získá typ vloženého sešitu. Vrací [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined), pokud DataSourceType (\#getDataSourceType.getDataSourceType) je [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Pouze pro čtení [WorkbookType](../../com.aspose.slides/workbooktype).

**Vrací:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```


Prohodí data podél osy. Data zobrazovaná na ose X se přesunou na osu Y a naopak.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
```


Nastaví externí sešit jako zdroj dat pro graf. Data grafu budou aktualizována z cílového sešitu.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| workbookPath | java.lang.String | Cesta k cílovému sešitu |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```


Nastaví externí sešit jako zdroj dat pro graf.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| workbookPath | java.lang.String | Cesta k cílovému sešitu |
| updateChartData | boolean | Pokud je hodnota false, bude aktualizována pouze cesta k sešitu. Data grafu nebudou načtena a aktualizována z cílového sešitu. Lze použít, pokud cílový sešit neexistuje nebo není dostupný. Pokud je hodnota true, data grafu budou aktualizována z cílového sešitu. |