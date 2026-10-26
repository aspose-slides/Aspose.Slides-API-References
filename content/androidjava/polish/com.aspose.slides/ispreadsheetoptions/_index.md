---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options which can be used to specify additional spreadsheets behavior.
type: docs
url: /pl/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Reprezentuje opcje, które mogą być użyte do określenia dodatkowego zachowania arkuszy kalkulacyjnych.
## Metody

| Metoda | Opis |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Gets or sets preferred culture information for calculating some functions intended for use with languages that use the double-byte character set (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Gets or sets preferred culture information for calculating some functions intended for use with languages that use the double-byte character set (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


Pobiera lub ustawia informacje o preferowanej kulturze używanej do obliczania niektórych funkcji przeznaczonych dla języków korzystających z dwubajtowego zestawu znaków (DBCS).

**Zwraca:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


Pobiera lub ustawia informacje o preferowanej kulturze używanej do obliczania niektórych funkcji przeznaczonych dla języków korzystających z dwubajtowego zestawu znaków (DBCS).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


Jeśli źródło danych wykresu jest zewnętrzną skoroszytem i nie jest dostępne, zostanie ono odzyskane z pamięci podręcznej wykresu.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Zwraca:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


Jeśli źródło danych wykresu jest zewnętrzną skoroszytem i nie jest dostępne, zostanie ono odzyskane z pamięci podręcznej wykresu.

--------------------

> ```
> Example:
>   
>   SpreadsheetOptions spreadOptions = new SpreadsheetOptions();
>   spreadOptions.setRecoverWorkbookFromChartCache(true);
> 
>   LoadOptions loadOptions = new LoadOptions();
>   loadOptions.setSpreadsheetOptions(spreadOptions);
> 
>   Presentation pres = new Presentation("Presentation.pptx", loadOptions);
>   try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartDataWorkbook recoveredWorkbook = chart.getChartData().getChartDataWorkbook();
>   } finally {
>      if (pres != null) pres.dispose();
>   }
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |