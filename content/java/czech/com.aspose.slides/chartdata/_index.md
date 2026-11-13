---
title: ChartData
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Reprezentuje data používaná pro vykreslování grafu.
type: docs
url: /cs/com.aspose.slides/chartdata/
---
**Dědičnost:**
java.lang.Object, com.aspose.slides.DomObject

**Všechny implementované rozhraní:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Reprezentuje data používaná pro vykreslování grafu.

## Metody

| Metoda | Popis |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Získá továrnu na buňky pro vytvoření buněk používaných pro řady grafu nebo kategorie. |
| [getSeries()](#getSeries--) | Získá řady. |
| [getSeriesGroups()](#getSeriesGroups--) | Získá skupiny řad. |
| [getCategories()](#getCategories--) | Získá primární kategorie (nebo jak primární, tak sekundární kategorie, pokud je vlastnost #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) nastavena na false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Pokud je false, pak vlastnost #getSecondaryCategories.getSecondaryCategories vrací null a data ve vlastnosti #getCategories.getCategories se používají jak pro primární, tak pro sekundární řady. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Pokud je false, pak vlastnost #getSecondaryCategories.getSecondaryCategories vrací null a data ve vlastnosti #getCategories.getCategories se používají jak pro primární, tak pro sekundární řady. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Získá sekundární kategorie, pokud je vlastnost #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) nastavena na true. |
| [readWorkbookStream()](#readWorkbookStream--) | Zapíše interně obsažený Excel sešit do paměťového proudu. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Inicializuje interně obsažený Excel sešit uživatelem zadanou hodnotou. |
| [getDataSourceType()](#getDataSourceType--) | Reprezentuje cestu k externímu sešitu, pokud je externí zdroj dat, jinak null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Reprezentuje zdroj dat grafu. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Získá typ vloženého sešitu. |
| [getRange()](#getRange--) | Získá rozsah dat grafu. |
| [setRange(String formula)](#setRange-java.lang.String-) | Nastaví rozsah dat grafu. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Nastaví externí sešit jako zdroj dat pro graf. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Nastaví externí sešit jako zdroj dat pro graf. |
| [refreshData()](#refreshData--) | Obnoví data grafu načtením z výchozího sešitu. |
| [switchRowColumn()](#switchRowColumn--) | Prohodí data přes osu. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Získá továrnu na buňky pro vytvoření buněk používaných pro řady grafu nebo kategorie. Pouze pro čtení [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Vrací:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Získá řady. Pouze pro čtení [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Vrací:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Získá skupiny řad. Pouze pro čtení [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Každá skupina řad obsahuje řady s kombinovatelnými typy. Skupiny kombinovatelných typů řad jsou definovány a popsány pomocí výčtu CombinableSeriesTypesGroup. Každá skupina řad také obsahuje řady, které jsou vykreslovány buď na primárních osách, nebo na sekundárních osách (nikoli v obou případech v jedné skupině). Princip seskupování řad je tedy seskupení podle typových skupin uvedených výše a podle typu vykreslování primární/sekundární.

**Vrací:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Získá primární kategorie (nebo jak primární, tak sekundární kategorie, pokud je vlastnost #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) nastavena na false). Pouze pro čtení [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Pokud je vlastnost #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) nastavena na false, pak vlastnost #getSecondaryCategories.getSecondaryCategories vrací null a data ve vlastnosti #getCategories.getCategories se používají jak pro primární, tak pro sekundární řady. Pokud je tato vlastnost nastavena na true, data ve vlastnosti #getSecondaryCategories.getSecondaryCategories se používají pro sekundární řady a data ve vlastnosti #getCategories.getCategories se používají pro primární řady.

**Vrací:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Pokud je false, pak vlastnost #getSecondaryCategories.getSecondaryCategories vrací null a data ve vlastnosti #getCategories.getCategories se používají jak pro primární, tak pro sekundární řady. Pokud je true, data ve vlastnosti #getSecondaryCategories.getSecondaryCategories se používají pro sekundární řady a data ve vlastnosti #getCategories.getCategories se používají pro primární řady. Čtení/Zápis boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // related categories are series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // related categories are series.getChart().getChartData().getCategories()
>  }
> ```

**Vrací:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Pokud je false, pak vlastnost #getSecondaryCategories.getSecondaryCategories vrací null a data ve vlastnosti #getCategories.getCategories se používají jak pro primární, tak pro sekundární řady. Pokud je true, data ve vlastnosti #getSecondaryCategories.getSecondaryCategories se používají pro sekundární řady a data ve vlastnosti #getCategories.getCategories se používají pro primární řady. Čtení/Zápis boolean.

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
public final IChartCategoryCollection getSecondaryCategories()
```

Získá sekundární kategorie, pokud je vlastnost #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) nastavena na true. Pouze pro čtení [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Pokud je vlastnost #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) nastavena na false, pak tato vlastnost #getSecondaryCategories.getSecondaryCategories vrací null a data ve vlastnosti #getCategories.getCategories se používají jak pro primární, tak pro sekundární řady. Pokud je tato vlastnost nastavena na true, data ve vlastnosti #getSecondaryCategories.getSecondaryCategories se používají pro sekundární řady a data ve vlastnosti #getCategories.getCategories se používají pro primární řady.

**Vrací:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Zapíše interně obsažený Excel sešit do paměťového proudu.

**Vrací:**
byte[] - Vrací instanci pole bajtů obsahující kopii interně obsaženého Excel sešitu.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Inicializuje interně obsažený Excel sešit uživatelem zadanou hodnotou.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| ms | byte[] | Uživatelem poskytnutý proud obsahující celý Excel sešit. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Reprezentuje cestu k externímu sešitu, pokud je externí zdroj dat, jinak null.

**Vrací:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Reprezentuje zdroj dat grafu.

**Vrací:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Získá typ vloženého sešitu. Vrací [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) pokud je DataSourceType (#getDataSourceType.getDataSourceType) [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Pouze pro čtení [WorkbookType](../../com.aspose.slides/workbooktype).

**Vrací:**
int

### getRange() {#getRange--}
```
public final String getRange()
```

Získá rozsah dat grafu.

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

**Vrací:**
java.lang.String - Formule rozsahu buněk. Např.: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Nastaví rozsah dat grafu. Řady a kategorie budou aktualizovány na základě nového rozsahu. Pokud je počet řad v rozsahu větší než počet řad v datech grafu, budou přidány další řady se stejným typem jako poslední řada v aktuální kolekci na konec kolekce.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| formula | java.lang.String | Formule rozsahu buněk. Např.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
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
>     if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| workbookPath | java.lang.String | Cesta k cílovému sešitu |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Nastaví externí sešit jako zdroj dat pro graf.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| workbookPath | java.lang.String | Cesta k cílovému sešitu |
| updateChartData | boolean | Pokud je hodnota false, bude aktualizována pouze cesta k sešitu. Data grafu nebudou načtena a aktualizována z cílového sešitu. Lze použít, když cílový sešit neexistuje nebo není dostupný. Pokud je hodnota true, data grafu budou aktualizována z cílového sešitu. |

### refreshData() {#refreshData--}
```
public final void refreshData()
```

Obnoví data grafu načtením z výchozího sešitu.

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

Prohodí data přes osu. Data vykreslená na ose X se přesunou na osu Y a naopak.