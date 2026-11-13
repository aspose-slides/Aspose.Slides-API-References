---
title: ChartData
second_title: Aspose.Slides dla Java – odniesienie API
description: Reprezentuje dane używane do tworzenia wykresu.
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
| [getChartDataWorkbook()](#getChartDataWorkbook--) | Uzyskuje fabrykę komórek do tworzenia komórek używanych w seriach wykresu lub kategoriach. |
| [getSeries()](#getSeries--) | Uzyskuje serie. |
| [getSeriesGroups()](#getSeriesGroups--) | Uzyskuje grupy serii. |
| [getCategories()](#getCategories--) | Uzyskuje podstawowe kategorie (lub zarówno podstawowe, jak i dodatkowe kategorie, jeśli #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest false). |
| [getUseSecondaryCategories()](#getUseSecondaryCategories--) | Jeśli false, to właściwość #getSecondaryCategories.getSecondaryCategories zwraca null i dane w właściwości #getCategories.getCategories są używane zarówno dla serii podstawowych, jak i dodatkowych. |
| [setUseSecondaryCategories(boolean value)](#setUseSecondaryCategories-boolean-) | Jeśli false, to właściwość #getSecondaryCategories.getSecondaryCategories zwraca null i dane w właściwości #getCategories.getCategories są używane zarówno dla serii podstawowych, jak i dodatkowych. |
| [getSecondaryCategories()](#getSecondaryCategories--) | Uzyskuje dodatkowe kategorie, jeśli #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest true. |
| [readWorkbookStream()](#readWorkbookStream--) | Zapisuje wewnętrznie zawarty skoroszyt Excel do strumienia w pamięci. |
| [writeWorkbookStream(byte[] ms)](#writeWorkbookStream-byte---) | Inicjalizuje wewnętrznie zawarty skoroszyt Excel wartością podaną przez użytkownika. |
| [getDataSourceType()](#getDataSourceType--) | Reprezentuje ścieżkę do zewnętrznego skoroszytu, jeśli źródło danych jest zewnętrzne, w przeciwnym razie null. |
| [getExternalWorkbookPath()](#getExternalWorkbookPath--) | Reprezentuje źródło danych wykresu. |
| [getEmbeddedWorkbookType()](#getEmbeddedWorkbookType--) | Uzyskuje typ osadzonego skoroszytu. |
| [getRange()](#getRange--) | Uzyskuje zakres danych wykresu. |
| [setRange(String formula)](#setRange-java.lang.String-) | Ustawia zakres danych wykresu. |
| [setExternalWorkbook(String workbookPath)](#setExternalWorkbook-java.lang.String-) | Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. |
| [setExternalWorkbook(String workbookPath, boolean updateChartData)](#setExternalWorkbook-java.lang.String-boolean-) | Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. |
| [refreshData()](#refreshData--) | Odświeża dane wykresu, ponownie wczytując je ze źródłowego skoroszytu. |
| [switchRowColumn()](#switchRowColumn--) | Zamienia dane na osi. |
### getChartDataWorkbook() {#getChartDataWorkbook--}
```
public final IChartDataWorkbook getChartDataWorkbook()
```

Uzyskuje fabrykę komórek do tworzenia komórek używanych w seriach wykresu lub kategoriach. Tylko do odczytu [IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook).

**Zwraca:**
[IChartDataWorkbook](../../com.aspose.slides/ichartdataworkbook)
### getSeries() {#getSeries--}
```
public final IChartSeriesCollection getSeries()
```

Uzyskuje serie. Tylko do odczytu [IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection).

**Zwraca:**
[IChartSeriesCollection](../../com.aspose.slides/ichartseriescollection)
### getSeriesGroups() {#getSeriesGroups--}
```
public final IChartSeriesGroupCollection getSeriesGroups()
```

Uzyskuje grupy serii. Tylko do odczytu [IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection).

--------------------

1) Każda grupa serii zawiera serie o kombinowalnych typach. Grupy kombinowalnych typów serii są definiowane i opisane za pomocą wyliczenia CombinableSeriesTypesGroup. Ponadto każda grupa serii zawiera serie, które są rysowane na osi podstawowej lub na osi dodatkowej (nie w obu przypadkach w jednej grupie). Zatem zasada grupowania serii polega na grupowaniu według wymienionych wyżej grup typów oraz według typu rysowania (podstawowy/dodatkowy). 2) Grupa serii zawiera pewne właściwości serii, które są wspólne dla każdej serii w grupie („właściwości grupy serii”). „Właściwości grupy serii” w klasie ChartSeriesGroup są odczyt/zapis. Każda z „właściwości grupy serii” może mieć projekcję tylko do odczytu w klasie ChartSeries.

**Zwraca:**
[IChartSeriesGroupCollection](../../com.aspose.slides/ichartseriesgroupcollection)
### getCategories() {#getCategories--}
```
public final IChartCategoryCollection getCategories()
```

Uzyskuje podstawowe kategorie (lub zarówno podstawowe, jak i dodatkowe kategorie, jeśli #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest false). Tylko do odczytu [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Jeśli #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest false, to (#getSecondaryCategories.getSecondaryCategories) zwraca null i dane w #getCategories.getCategories są używane zarówno dla serii podstawowych, jak i dodatkowych. Jeśli #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest true, to dane w (#getSecondaryCategories.getSecondaryCategories) są używane dla serii dodatkowych, a dane w #getCategories.getCategories są używane dla serii podstawowych.

**Zwraca:**
[IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection)
### getUseSecondaryCategories() {#getUseSecondaryCategories--}
```
public final boolean getUseSecondaryCategories()
```

Jeśli false, to #getSecondaryCategories.getSecondaryCategories zwraca null i dane w #getCategories.getCategories są używane zarówno dla serii podstawowych, jak i dodatkowych. Jeśli true, to dane w #getSecondaryCategories.getSecondaryCategories są używane dla serii dodatkowych, a dane w #getCategories.getCategories są używane dla serii podstawowych. Odczyt/zapis boolean.

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

Jeśli false, to #getSecondaryCategories.getSecondaryCategories zwraca null i dane w #getCategories.getCategories są używane zarówno dla serii podstawowych, jak i dodatkowych. Jeśli true, to dane w #getSecondaryCategories.getSecondaryCategories są używane dla serii dodatkowych, a dane w #getCategories.getCategories są używane dla serii podstawowych. Odczyt/zapis boolean.

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

Uzyskuje dodatkowe kategorie, jeśli #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest true. Tylko do odczytu [IChartCategoryCollection](../../com.aspose.slides/ichartcategorycollection).

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

Jeśli #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest false, to (#getSecondaryCategories.getSecondaryCategories) zwraca null i dane w #getCategories.getCategories są używane zarówno dla serii podstawowych, jak i dodatkowych. Jeśli #getUseSecondaryCategories.getUseSecondaryCategories/#setUseSecondaryCategories(boolean).setUseSecondaryCategories(boolean) jest true, to dane w (#getSecondaryCategories.getSecondaryCategories) są używane dla serii dodatkowych, a dane w #getCategories.getCategories są używane dla serii podstawowych.

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

Uzyskuje typ osadzonego skoroszytu. Zwraca [WorkbookType.NotDefined](../../com.aspose.slides/workbooktype\#NotDefined) jeśli DataSourceType (#getDataSourceType.getDataSourceType) jest [ChartDataSourceType.ExternalWorkbook](../../com.aspose.slides/chartdatasourcetype\#ExternalWorkbook). Tylko do odczytu [WorkbookType](../../com.aspose.slides/workbooktype).

**Zwraca:**
int
### getRange() {#getRange--}
```
public final String getRange()
```

Uzyskuje zakres danych wykresu.

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

Ustawia zakres danych wykresu. Serie i kategorie zostaną zaktualizowane na podstawie nowego zakresu danych. Jeśli liczba serii w zakresie danych jest większa niż liczba serii w danych wykresu, dodatkowe serie z tym samym typem co ostatnia seria w bieżącej kolekcji zostaną dodane na koniec kolekcji.

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
| updateChartData | boolean | Jeśli wartość jest false, zostanie zaktualizowana tylko ścieżka do skoroszytu. Dane wykresu nie zostaną załadowane i zaktualizowane z docelowego skoroszytu. Może być użyte, gdy docelowy skoroszyt nie istnieje lub nie jest dostępny. Jeśli wartość jest true, dane wykresu zostaną zaktualizowane z docelowego skoroszytu. |

### refreshData() {#refreshData--}
```
public final void refreshData()
```

Odświeża dane wykresu, ponownie wczytując je ze źródłowego skoroszytu.

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

Zamienia dane na osi. Dane rysowane na osi X zostaną przeniesione na oś Y i odwrotnie.