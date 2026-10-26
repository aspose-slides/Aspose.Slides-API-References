---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje opcje, które można wykorzystać do określenia dodatkowego zachowania arkuszy kalkulacyjnych.
type: docs
url: /pl/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Reprezentuje opcje, które można wykorzystać do określenia dodatkowego zachowania arkuszy kalkulacyjnych.
## Metody

| Metoda | Opis |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Pobiera lub ustawia preferowane informacje o kulturze używane przy obliczaniu niektórych funkcji przeznaczonych dla języków używających zestawu znaków podwójnego bajtu (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Pobiera lub ustawia preferowane informacje o kulturze używane przy obliczaniu niektórych funkcji przeznaczonych dla języków używających zestawu znaków podwójnego bajtu (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Jeśli źródło danych wykresu jest zewnętrznym skoroszytem i nie jest dostępne, zostanie odzyskane z pamięci podręcznej wykresu. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Jeśli źródło danych wykresu jest zewnętrznym skoroszytem i nie jest dostępne, zostanie odzyskane z pamięci podręcznej wykresu. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```

Pobiera lub ustawia preferowane informacje o kulturze używane przy obliczaniu niektórych funkcji przeznaczonych dla języków używających zestawu znaków podwójnego bajtu (DBCS).

**Zwraca:**  
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```

Pobiera lub ustawia preferowane informacje o kulturze używane przy obliczaniu niektórych funkcji przeznaczonych dla języków używających zestawu znaków podwójnego bajtu (DBCS).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.util.Locale |  |
### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```

Jeśli źródło danych wykresu jest zewnętrznym skoroszytem i nie jest dostępne, zostanie odzyskane z pamięci podręcznej wykresu.

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

Jeśli źródło danych wykresu jest zewnętrznym skoroszytem i nie jest dostępne, zostanie odzyskane z pamięci podręcznej wykresu.

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