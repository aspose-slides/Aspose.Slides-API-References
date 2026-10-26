---
title: ChartData
second_title: Aspose.Slides dla Java – Dokumentacja API
description: Reprezentuje dane używane do rysowania wykresu.
type: docs
url: /pl/com.aspose.slides/chartdata/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IChartData](../../com.aspose.slides/ichartdata)
```
public class ChartData extends DomObject<Chart> implements IChartData
```

Reprezentuje dane używane do rysowania wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Pobiera fabrykę komórek do tworzenia komórek używanych w seriach wykresu lub kategoriach. |
| [getSeries()](#getSeries--) | Pobiera serie. |
| [getSeriesGroups()](#getSeriesGroups--) | Pobiera grupy serii. |
| [getCategories()](#getCategories--) | Pobiera kategorie podstawowe (lub zarówno podstawowe, jak i dodatkowe kategorie, jeśli właściwość #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Jeśli false, to właściwość #getSecondaryCategories.getSecondaryCategories zwraca null i dane w właściwości #getCategories.getCategories są używane zarówno dla serii podstawowych, jak i dodatkowych. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Jeśli false, to właściwość #getSecondaryCategories.getSecondaryCategories zwraca null i dane w właściwości #getCategories.getCategories są używane zarówno dla serii podstawowych, jak i dodatkowych. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Pobiera dodatkowe kategorie, jeśli właściwość #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest true. |
| [readWorkbookStream()](#readWorkbookStream--) | Zapisuje wewnętrznie zawarty skoroszyt Excel do strumienia w pamięci. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Inicjalizuje wewnętrznie zawarty skoroszyt Excel wartością podaną przez użytkownika. |
| [getDataSourceType()](#getDataSourceType--) | Reprezentuje ścieżkę do zewnętrznego skoroszytu, jeśli źródło danych jest zewnętrzne, w przeciwnym razie null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Reprezentuje źródło danych wykresu. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Pobiera typ osadzonego skoroszytu. |
| [getRange()](#getRange--) | Pobiera zakres danych wykresu. |
| [setRange(String formula)](#setRange-java.lang.String-) | Ustawia zakres danych wykresu. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. |
| [switchRowColumn()](#switchRowColumn--) | Zamienia dane wzdłuż osi. |

### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Pobiera fabrykę komórek do tworzenia komórek używanych w seriach wykresu lub kategoriach. tylko do odczytu [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Zwraca:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)

### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Pobiera serie. tylko do odczytu [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Zwraca:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)

### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Pobiera grupy serii. tylko do odczytu [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Każda grupa serii zawiera serie z łącznymi typami. Grupy łącznych typów serii są definiowane i opisane w wyliczeniu CombinableSeriesTypesGroup. Ponadto każda grupa serii zawiera serie, które są wykreślane albo na osi podstawowej, albo na osi dodatkowej (nie oba przypadki w jednej grupie). Zatem zasada grupowania serii to grupowanie według wymienionych wyżej grup typów oraz według typu rysowania (podstawowy/dodatkowy). 2) Grupa serii zawiera niektóre właściwości serii, które są wspólne dla każdej serii w grupie („właściwości grupy serii”). „Właściwości grupy serii” w klasie ChartSeriesGroup są odczyt/zapis. Każda z „właściwości grupy serii” może mieć projekcję tylko do odczytu w klasie ChartSeries.

**Zwraca:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)

### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Pobiera kategorie podstawowe (lub zarówno podstawowe, jak i dodatkowe kategorie, jeśli właściwość #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest false). tylko do odczytu [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // powiązane kategorie to series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // powiązane kategorie to series.getChart().getChartData().getCategories()
>  }
> ```

--------------------

Jeśli właściwość #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest false, to właściwość (#getSecondaryCategories.getSecondaryCategories) zwraca null i dane w właściwości #getCategories.getCategories są używane zarówno dla serii podstawowych, jak i dodatkowych. Jeśli właściwość #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest true, to dane w właściwości (#getSecondaryCategories.getSecondaryCategories) są używane dla serii dodatkowych, a dane w tej właściwości #getCategories.getCategories są używane dla serii podstawowych.

**Zwraca:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Jeśli false, to właściwość #getSecondaryCategories.getSecondaryCategories zwraca null i dane w właściwości #getCategories.getCategories są używane zarówno dla serii podstawowych, jak i dodatkowych. Jeśli true, to dane w właściwości #getSecondaryCategories.getSecondaryCategories są używane dla serii dodatkowych, a dane w właściwości #getCategories.getCategories są używane dla serii podstawowych. odczyt/zapis boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // powiązane kategorie to series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // powiązane kategorie to series.getChart().getChartData().getCategories()
>  }
> ```

**Zwraca:**
boolean

### setUseSecondaryCategories(boolean value) {#setUseSecondaryCategories-boolean-}
```
public final void setUseSecondaryCategories(boolean value)
```

Jeśli false, to właściwość #getSecondaryCategories.getSecondaryCategories zwraca null i dane w właściwości #getCategories.getCategories są używane zarówno dla serii podstawowych, jak i dodatkowych. Jeśli true, to dane w właściwości #getSecondaryCategories.getSecondaryCategories są używane dla serii dodatkowych, a dane w właściwości #getCategories.getCategories są używane dla serii podstawowych. odczyt/zapis boolean.

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // powiązane kategorie to series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // powiązane kategorie to series.getChart().getChartData().getCategories()
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getSecondaryCategories() {#getSecondaryCategories--}
```
public final IChartCategoryCollection getSecondaryCategories()
```

Pobiera dodatkowe kategorie, jeśli właściwość #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest true. tylko do odczytu [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

--------------------

> ```
> Example. What categories are related to series - ChartData.getCategories() or ChartData.getSecondaryCategories()?
>  
>  if (series.getPlotOnSecondAxis() && series.getChart().getChartData().getUseSecondaryCategories())
>  {
>      // powiązane kategorie to series.getChart().getChartData().getSecondaryCategories()
>  }
>  else
>  {
>      // powiązane kategorie to series.getChart().getChartData().getCategories()
>  }
> ```

Jeśli właściwość #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest false, to właściwość (#getSecondaryCategories.getSecondaryCategories) zwraca null i dane w właściwości #getCategories.getCategories są używane zarówno dla serii podstawowych, jak i dodatkowych. Jeśli właściwość #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest true, to dane w tej właściwości #getSecondaryCategories.getSecondaryCategories są używane dla serii dodatkowych, a dane w właściwości #getCategories.getCategories są używane dla serii podstawowych.

**Zwraca:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)

### readWorkbookStream() {#readWorkbookStream--}
```
public final byte[] readWorkbookStream()
```

Zapisuje wewnętrznie zawarty skoroszyt Excel do strumienia w pamięci.

**Zwraca:**
byte[] - Zwraca instancję tablicy bajtów zawierającej kopię wewnętrznie zawartego skoroszytu Excel.

### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public final void writeWorkbookStream(byte[] ms)
```

Inicjalizuje wewnętrznie zawarty skoroszyt Excel wartością podaną przez użytkownika.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| ms | byte[] | Strumień dostarczony przez użytkownika zawierający cały skoroszyt Excel. |

### getDataSourceType() {#getDataSourceType--}
```
public final int getDataSourceType()
```

Reprezentuje ścieżkę do zewnętrznego skoroszytu, jeśli źródło danych jest zewnętrzne, w przeciwnym razie null.

**Zwraca:**
int

### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public final String getExternalWorkbookPath()
```

Reprezentuje źródło danych wykresu.

**Zwraca:**
java.lang.String

### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public final int getEmbeddedWorkbookType()
```

Pobiera typ osadzonego skoroszytu. Zwraca [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) jeśli DataSourceType (#getDataSourceType.getDataSourceType) jest [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). tylko do odczytu [WorkbookType](../../com.aspose.slides/workbooktype).

**Zwraca:**
int

### getRange() {#getRange--}
```
public final String getRange()
```

Pobiera zakres danych wykresu.

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

**Zwraca:**
java.lang.String - Formuła zakresu danych komórek. Np.: "Sheet1!$A$1:$C$4"

### setRange(String formula) {#setRange-java.lang.String-}
```
public final void setRange(String formula)
```

Ustawia zakres danych wykresu. Serie i kategorie zostaną zaktualizowane na podstawie nowego zakresu danych. Jeśli liczba serii w zakresie danych jest większa niż liczba serii w danych wykresu, zostaną dodane dodatkowe serie o tym samym typie co ostatnia seria w bieżącej kolekcji, umieszczone na końcu kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| formula | java.lang.String | Formuła zakresu danych komórek. Np.: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public final void setExternalWorkbook(String workbookPath)
```

Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. Dane wykresu zostaną zaktualizowane z docelowego skoroszytu.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| workbookPath | java.lang.String | Ścieżka do docelowego skoroszytu |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public final void setExternalWorkbook(String workbookPath, boolean updateChartData)
```

Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| workbookPath | java.lang.String | Ścieżka do docelowego skoroszytu |
| updateChartData | boolean | Jeśli wartość jest false, tylko ścieżka do skoroszytu zostanie zaktualizowana. Dane wykresu nie zostaną załadowane i zaktualizowane z docelowego skoroszytu. Może być użyte, gdy docelowy skoroszyt nie istnieje lub nie jest dostępny. Jeśli wartość jest true, dane wykresu zostaną zaktualizowane z docelowego skoroszytu. |

### switchRowColumn() {#switchRowColumn--}
```
public final void switchRowColumn()
```

Zamienia dane wzdłuż osi. Dane wykreślone na osi X zostaną przeniesione na oś Y i odwrotnie.