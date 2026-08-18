---
title: SpreadsheetOptions
second_title: Aspose.Slides a Java API hivatkozás
description: Olyan beállításokat jelöl, amelyekkel további táblázatkezelő viselkedést lehet meghatározni.
type: docs
url: /hu/com.aspose.slides/spreadsheetoptions/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Olyan beállításokat képvisel, amelyekkel további táblázatkezelő viselkedést lehet meghatározni.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Új példányt inicializál a [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) osztályból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Lekéri vagy beállítja a kedvenc kultúra információkat olyan függvények számításához, amelyeket a kettős bájtos karakterkészletet (DBCS) használó nyelvekhez szánnak. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Lekéri vagy beállítja a kedvenc kultúra információkat olyan függvények számításához, amelyeket a kettős bájtos karakterkészletet (DBCS) használó nyelvekhez szánnak. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Ha a diagram adatforrása egy külső munkafüzet, és az nem érhető el, akkor a diagram gyorsítótárából kerül helyreállításra. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Ha a diagram adatforrása egy külső munkafüzet, és az nem érhető el, akkor a diagram gyorsítótárából kerül helyreállításra. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```


Új példányt inicializál a [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) osztályból.

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```


Lekéri vagy beállítja a kedvenc kultúra információkat olyan függvények számításához, amelyeket a kettős bájtos karakterkészletet (DBCS) használó nyelvekhez szánnak.

**Visszatérési érték:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```


Lekéri vagy beállítja a kedvenc kultúra információkat olyan függvények számításához, amelyeket a kettős bájtos karakterkészletet (DBCS) használó nyelvekhez szánnak.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```


Ha a diagram adatforrása egy külső munkafüzet, és az nem érhető el, akkor a diagram gyorsítótárából kerül helyreállításra.

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
public final void setRecoverWorkbookFromChartCache(boolean value)
```


Ha a diagram adatforrása egy külső munkafüzet, és az nem érhető el, akkor a diagram gyorsítótárából kerül helyreállításra.

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