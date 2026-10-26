---
title: SpreadsheetOptions
second_title: Aspose.Slides dla Androida za pośrednictwem referencji API Java
description: Reprezentuje opcje, które mogą być użyte do określenia dodatkowego zachowania arkuszy kalkulacyjnych.
type: docs
url: /pl/com.aspose.slides/spreadsheetoptions/
---
**Dziedziczenie:**
java.lang.Object

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Reprezentuje opcje, które można wykorzystać do określenia dodatkowego zachowania arkuszy kalkulacyjnych.
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Inicjalizuje nową instancję klasy [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions). |
## Metody

| Metoda | Opis |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Pobiera lub ustawia preferowane informacje o kulturze używane do obliczania niektórych funkcji przeznaczonych dla języków używających dwubajtowego zestawu znaków (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Pobiera lub ustawia preferowane informacje o kulturze używane do obliczania niektórych funkcji przeznaczonych dla języków używających dwubajtowego zestawu znaków (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Jeżeli źródło danych dla wykresu jest zewnętrznym skoroszytem i nie jest dostępne, zostanie odzyskane z pamięci podręcznej wykresu. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Jeżeli źródło danych dla wykresu jest zewnętrznym skoroszytem i nie jest dostępne, zostanie odzyskane z pamięci podręcznej wykresu. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```


Inicjalizuje nową instancję klasy [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions).

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```


Pobiera lub ustawia preferowane informacje o kulturze używane do obliczania niektórych funkcji przeznaczonych dla języków używających dwubajtowego zestawu znaków (DBCS).

**Zwraca:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```


Pobiera lub ustawia preferowane informacje o kulturze używane do obliczania niektórych funkcji przeznaczonych dla języków używających dwubajtowego zestawu znaków (DBCS).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```


Jeżeli źródło danych dla wykresu jest zewnętrznym skoroszytem i nie jest dostępne, zostanie odzyskane z pamięci podręcznej wykresu.

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
public final void setRecoverWorkbookFromChartCache(boolean value)
```


Jeżeli źródło danych dla wykresu jest zewnętrznym skoroszytem i nie jest dostępne, zostanie odzyskane z pamięci podręcznej wykresu.

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