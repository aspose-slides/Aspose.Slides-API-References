---
title: SpreadsheetOptions
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje možnosti, které lze použít k určení dalšího chování tabulek.
type: docs
url: /cs/com.aspose.slides/spreadsheetoptions/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Představuje možnosti, které lze použít k určení dalšího chování tabulek.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Inicializuje novou instanci [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) třídy. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Získává nebo nastavuje informace o preferované kultuře pro výpočet některých funkcí určených pro jazyky používající dvojbytový znakový soubor (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Získává nebo nastavuje informace o preferované kultuře pro výpočet některých funkcí určených pro jazyky používající dvojbytový znakový soubor (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Pokud je zdroj dat pro graf externí sešit a není k dispozici, bude obnoven z vyrovnávací paměti grafu. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Pokud je zdroj dat pro graf externí sešit a není k dispozici, bude obnoven z vyrovnávací paměti grafu. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```


Inicializuje novou instanci [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) třídy.

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```


Získává nebo nastavuje informace o preferované kultuře pro výpočet některých funkcí určených pro jazyky používající dvojbytový znakový soubor (DBCS).

**Vrací:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```


Získává nebo nastavuje informace o preferované kultuře pro výpočet některých funkcí určených pro jazyky používající dvojbytový znakový soubor (DBCS).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```


Pokud je zdroj dat pro graf externí sešit a není k dispozici, bude obnoven z vyrovnávací paměti grafu.

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
public final void setRecoverWorkbookFromChartCache(boolean value)
```


Pokud je zdroj dat pro graf externí sešit a není k dispozici, bude obnoven z vyrovnávací paměti grafu.

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