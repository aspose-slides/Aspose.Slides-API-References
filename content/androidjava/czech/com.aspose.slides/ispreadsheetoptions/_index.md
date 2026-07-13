---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Představuje možnosti, které lze použít k určení dalšího chování tabulek.
type: docs
url: /cs/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Představuje možnosti, které lze použít k určení dalšího chování tabulek.
## Metody

| Metoda | Popis |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Získá nebo nastaví preferované informace o kultuře pro výpočet některých funkcí určených pro jazyky používající dvojbytovou znakovou sadu (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Získá nebo nastaví preferované informace o kultuře pro výpočet některých funkcí určených pro jazyky používající dvojbytovou znakovou sadu (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Pokud je zdroj dat pro graf externí sešit a není k dispozici, bude obnoven z mezipaměti grafu. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Pokud je zdroj dat pro graf externí sešit a není k dispozici, bude obnoven z mezipaměti grafu. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


Získá nebo nastaví preferované informace o kultuře pro výpočet některých funkcí určených pro jazyky používající dvojbytovou znakovou sadu (DBCS).

**Vrací:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


Získá nebo nastaví preferované informace o kultuře pro výpočet některých funkcí určených pro jazyky používající dvojbytovou znakovou sadu (DBCS).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


Pokud je zdroj dat pro graf externí sešit a není k dispozici, bude obnoven z mezipaměti grafu.

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

**Vrací:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


Pokud je zdroj dat pro graf externí sešit a není k dispozici, bude obnoven z mezipaměti grafu.

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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |