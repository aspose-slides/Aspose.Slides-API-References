---
title: IChartData
second_title: Aspose.Slides for Android via Java API Reference
description: Represents data used for a chart plotting.
type: docs
url: /pl/com.aspose.slides/ichartdata/
---```
public interface IChartData
```

Reprezentuje dane używane do tworzenia wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Pobiera fabrykę komórek do tworzenia komórek używanych w seriach wykresu lub kategoriach. |
| [getSeries()](#getSeries--) | Pobiera serie. |
| [getSeriesGroups()](#getSeriesGroups--) | Pobiera grupy serii. |
| [getCategories()](#getCategories--) | Pobiera główne kategorie (lub zarówno główne, jak i drugorzędne kategorie, jeśli właściwość (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) jest false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Jeśli false, to właściwość (\#getSecondaryCategories.getSecondaryCategories) zwraca null i dane w właściwości (\#getCategories.getCategories) są używane zarówno dla serii głównych, jak i drugorzędnych. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Jeśli false, to właściwość (\#getSecondaryCategories.getSecondaryCategories) zwraca null i dane w właściwości (\#getCategories.getCategories) są używane zarówno dla serii głównych, jak i drugorzędnych. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Pobiera drugorzędne kategorie, jeśli właściwość (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) jest true. |
| [readWorkbookStream()](#readWorkbookStream--) | Zapisuje wewnętrznie zawarty skoroszyt Excel do strumienia w pamięci. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Inicjalizuje wewnętrznie zawarty skoroszyt Excel wartością podaną przez użytkownika. |
| [setRange(String formula)](#setRange-java.lang.String-) | Ustawia zakres danych wykresu. |
| [getRange()](#getRange--) | Pobiera zakres danych wykresu. |
| [getDataSourceType()](#getDataSourceType--) | Reprezentuje źródło danych wykresu |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Reprezentuje ścieżkę do zewnętrznego skoroszytu, jeśli źródło danych jest zewnętrzne, w przeciwnym razie null |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Pobiera typ osadzonego skoroszytu. |
| [switchRowColumn()](#switchRowColumn--) | Zamienia dane wzdłuż osi. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public abstract IChartDataWorkbook getChartDataWorkbook()
```


Pobiera fabrykę komórek do tworzenia komórek używanych w seriach wykresu lub kategoriach. Tylko do odczytu [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Zwraca:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public abstract IChartSeriesCollection getSeries()
```


Pobiera serie. Tylko do odczytu [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Zwraca:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public abstract IChartSeriesGroupCollection getSeriesGroups()
```


Pobiera grupy serii. Tylko do odczytu [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Każda grupa serii zawiera serie o typach możliwych do kombinacji. Grupy kombinowalnych typów serii są definiowane i opisywane przy użyciu wyliczenia CombinableSeriesTypesGroup. Ponadto każda grupa serii zawiera serie, które są rysowane albo na osi głównej, albo na osi drugorzędnej (nie w obu przypadkach w jednej grupie). Zatem zasada grupowania serii polega na grupowaniu według grup typów wymienionych powyżej oraz według typu rysowania głównego/drugorzędnego. 2) Grupa serii zawiera niektóre właściwości serii wspólne dla każdej serii w grupie („właściwości grupy serii”). „Właściwości grupy serii” w klasie ChartSeriesGroup są odczyt/zapis. Każda z „właściwości grupy serii” może mieć projekcję tylko do odczytu w klasie ChartSeries.

**Zwraca:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public abstract IChartCategoryCollection getCategories()
```


Pobiera główne kategorie (lub zarówno główne, jak i drugorzędne kategorie, jeśli właściwość (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) jest false). Tylko do odczytu [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Jeśli właściwość (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) jest false, to właściwość (\#getSecondaryCategories.getSecondaryCategories) zwraca null i dane w tej właściwości (\#getCategories.getCategories) są używane zarówno dla serii głównych, jak i drugorzędnych. Jeśli właściwość (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) jest true, to dane w właściwości (\#getSecondaryCategories.getSecondaryCategories) są używane dla serii drugorzędnych, a dane w tej właściwości (\#getCategories.getCategories) są używane dla serii głównych.

**Zwraca:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public abstract boolean getUseSecondaryCategories()
```


Jeśli false, to właściwość (\#getSecondaryCategories.getSecondaryCategories) zwraca null i dane w właściwości (\#getCategories.getCategories) są używane zarówno dla serii głównych, jak i drugorzędnych. Jeśli true, to dane w właściwości (\#getSecondaryCategories.getSecondaryCategories) są używane dla serii drugorzędnych, a dane w właściwości (\#getCategories.getCategories) są używane dla serii głównych. Odczyt/zapis boolean.

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
public abstract void setUseSecondaryCategories(boolean value)
```


Jeśli false, to właściwość (\#getSecondaryCategories.getSecondaryCategories) zwraca null i dane w właściwości (\#getCategories.getCategories) są używane zarówno dla serii głównych, jak i drugorzędnych. Jeśli true, to dane w właściwości (\#getSecondaryCategories.getSecondaryCategories) są używane dla serii drugorzędnych, a dane w właściwości (\#getCategories.getCategories) są używane dla serii głównych. Odczyt/zapis boolean.

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
public abstract IChartCategoryCollection getSecondaryCategories()
```


Pobiera drugorzędne kategorie, jeśli właściwość (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) jest true. Tylko do odczytu [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Jeśli właściwość (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) jest false, to ta właściwość (\#getSecondaryCategories.getSecondaryCategories) zwraca null i dane w właściwości (\#getCategories.getCategories) są używane zarówno dla serii głównych, jak i drugorzędnych. Jeśli właściwość (\#getUseSecondaryCategories.getUseSecondaryCategories/\#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean)) jest true, to dane w tej właściwości (\#getSecondaryCategories.getSecondaryCategories) są używane dla serii drugorzędnych, a dane w tej właściwości (\#getCategories.getCategories) są używane dla serii głównych.

**Zwraca:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### readWorkbookStream() {#readWorkbookStream--}
```
public abstract byte[] readWorkbookStream()
```


Zapisuje wewnętrznie zawarty skoroszyt Excel do strumienia w pamięci.

**Zwraca:**
byte[] - Zwraca tablicę bajtów zawierającą kopię wewnętrznie zawartego skoroszytu Excel.
### writeWorkbookStream(byte[] ms) {#writeWorkbookStream-byte---}
```
public abstract void writeWorkbookStream(byte[] ms)
```


Inicjalizuje wewnętrznie zawarty skoroszyt Excel wartością podaną przez użytkownika.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| ms | byte[] | Strumień dostarczony przez użytkownika zawierający cały skoroszyt Excel. |

### setRange(String formula) {#setRange-java.lang.String-}
```
public abstract void setRange(String formula)
```


Ustawia zakres danych wykresu. Serie i kategorie zostaną zaktualizowane na podstawie nowego zakresu danych. Jeśli liczba serii w zakresie danych jest większa niż liczba serii w danych wykresu, zostaną dodane dodatkowe serie tego samego typu co ostatnia seria w bieżącej kolekcji, na koniec kolekcji.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| formula | java.lang.String | Formuła zakresu danych komórek. Np.: "Sheet1!$A$1:$C$4", "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### getRange() {#getRange--}
```
public abstract String getRange()
```


Pobiera zakres danych wykresu.

--------------------

> ```
> Presentation pres = new Presentation();
>  {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.PercentsStackedBar, 100, 100, 500, 400);
>      String result = ((ChartData)chart.getChartData()).getRange();
>  }
> ```

**Zwraca:**
java.lang.String - Formuła zakresu danych komórek. Np.: "Sheet1!$A$1:$C$4"
### getDataSourceType() {#getDataSourceType--}
```
public abstract int getDataSourceType()
```


Reprezentuje źródło danych wykresu

**Zwraca:**
int
### getExternalWorkbookPath() {#getExternalWorkbookPath--}
```
public abstract String getExternalWorkbookPath()
```


Reprezentuje ścieżkę do zewnętrznego skoroszytu, jeśli źródło danych jest zewnętrzne, w przeciwnym razie null

**Zwraca:**
java.lang.String
### getEmbeddedWorkbookType() {#getEmbeddedWorkbookType--}
```
public abstract int getEmbeddedWorkbookType()
```


Pobiera typ osadzonego skoroszytu. Zwraca [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) jeśli DataSourceType (\#getDataSourceType.getDataSourceType) jest [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Tylko do odczytu [WorkbookType](../../com.aspose.slides/workbooktype).

**Zwraca:**
int
### switchRowColumn() {#switchRowColumn--}
```
public abstract void switchRowColumn()
```


Zamienia dane wzdłuż osi. Dane wykreślone na osi X zostaną przeniesione na oś Y i odwrotnie.

### setExternalWorkbook(String workbookPath) {#setExternalWorkbook-java.lang.String-}
```
public abstract void setExternalWorkbook(String workbookPath)
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
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| workbookPath | java.lang.String | Ścieżka do docelowego skoroszytu |

### setExternalWorkbook(String workbookPath, boolean updateChartData) {#setExternalWorkbook-java.lang.String-boolean-}
```
public abstract void setExternalWorkbook(String workbookPath, boolean updateChartData)
```


Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu.

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
| Parametr | Typ | Opis |
| --- | --- | --- |
| workbookPath | java.lang.String | Ścieżka do docelowego skoroszytu |
| updateChartData | boolean | Jeśli wartość jest false, zostanie zaktualizowana tylko ścieżka do skoroszytu. Dane wykresu nie zostaną wczytane i zaktualizowane z docelowego skoroszytu. Może być użyte, gdy docelowy skoroszyt nie istnieje lub nie jest dostępny. Jeśli wartość jest true, dane wykresu zostaną zaktualizowane z docelowego skoroszytu. |