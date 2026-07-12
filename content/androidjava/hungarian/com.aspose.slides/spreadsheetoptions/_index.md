---
title: SpreadsheetOptions
second_title: Aspose.Slides Androidhoz a Java API-referencia alapján
description: Olyan beállítási lehetőségeket képvisel, amelyek használhatók további táblázatok viselkedésének meghatározására.
type: docs
url: /hu/com.aspose.slides/spreadsheetoptions/
---
**Öröklődés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Képviseli azokat a beállítási lehetőségeket, amelyek használhatók további táblázatok viselkedésének meghatározására.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Inicializál egy új példányt a [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) osztályból. |
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Lekéri vagy beállítja a preferált kultúrainformációt olyan függvények kiszámításához, amelyek a kettő bájtos karakterkészletet (DBCS) használó nyelvekhez vannak tervezve. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Lekéri vagy beállítja a preferált kultúrainformációt olyan függvények kiszámításához, amelyek a kettő bájtos karakterkészletet (DBCS) használó nyelvekhez vannak tervezve. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Ha a diagram adatforrása egy külső munkafüzet, és nem érhető el, akkor a diagram gyorsítótárából állítják helyre. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Ha a diagram adatforrása egy külső munkafüzet, és nem érhető el, akkor a diagram gyorsítótárából állítják helyre. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

Inicializál egy új példányt a [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) osztályból.

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

Lekéri vagy beállítja a preferált kultúrainformációt olyan függvények kiszámításához, amelyek a kettő bájtos karakterkészletet (DBCS) használó nyelvekhez vannak tervezve.

**Visszatérési érték:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

Lekéri vagy beállítja a preferált kultúrainformációt olyan függvények kiszámításához, amelyek a kettő bájtos karakterkészletet (DBCS) használó nyelvekhez vannak tervezve.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

Ha a diagram adatforrása egy külső munkafüzet, és nem érhető el, akkor a diagram gyorsítótárából állítják helyre.

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

Ha a diagram adatforrása egy külső munkafüzet, és nem érhető el, akkor a diagram gyorsítótárából állítják helyre.

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