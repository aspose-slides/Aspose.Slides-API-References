---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Java API Reference
description: Represents options which can be used to specify additional spreadsheets behavior.
type: docs
url: /hu/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Azokat a beállításokat képviseli, amelyek további táblázatkezelő viselkedés meghatározására használhatók.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Lekérdezi vagy beállítja a kedvelt kultúra információkat olyan függvények számításához, amelyek a kétszakaszos karakterkészletet (DBCS) használó nyelvekhez vannak tervezve. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Lekérdezi vagy beállítja a kedvelt kultúra információkat olyan függvények számításához, amelyek a kétszakaszos karakterkészletet (DBCS) használó nyelvekhez vannak tervezve. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Ha a diagram adatforrása egy külső munkafüzet, és nem érhető el, akkor a diagram gyorsítótárából állítja helyre. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Ha a diagram adatforrása egy külső munkafüzet, és nem érhető el, akkor a diagram gyorsítótárából állítja helyre. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


Lekérdezi vagy beállítja a kedvelt kultúra információkat olyan függvények számításához, amelyek a kétszakaszos karakterkészletet (DBCS) használó nyelvekhez vannak tervezve.

**Visszatérési érték:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


Lekérdezi vagy beállítja a kedvelt kultúra információkat olyan függvények számításához, amelyek a kétszakaszos karakterkészletet (DBCS) használó nyelvekhez vannak tervezve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


Ha a diagram adatforrása egy külső munkafüzet, és nem érhető el, akkor a diagram gyorsítótárából állítja helyre.

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

**Visszatérési érték:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


Ha a diagram adatforrása egy külső munkafüzet, és nem érhető el, akkor a diagram gyorsítótárából állítja helyre.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |