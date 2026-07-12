---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android Java API-referencia
description: A további táblázatok viselkedésének meghatározására használható beállításokat képviseli.
type: docs
url: /hu/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

A további táblázatok viselkedésének meghatározására használható beállításokat képviseli.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | A duplakódos karakterkészletet (DBCS) használó nyelvekhez szánt egyes funkciók számításához szükséges preferált kultúra-információt kapja meg vagy állítja be. |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | A duplakódos karakterkészletet (DBCS) használó nyelvekhez szánt egyes funkciók számításához szükséges preferált kultúra-információt kapja meg vagy állítja be. |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Ha a diagram adatforrása egy külső munkafüzet, és nem elérhető, akkor a diagram gyorsítótárából lesz helyreállítva. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Ha a diagram adatforrása egy külső munkafüzet, és nem elérhető, akkor a diagram gyorsítótárából lesz helyreállítva. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```

A duplakódos karakterkészletet (DBCS) használó nyelvekhez szánt egyes funkciók számításához szükséges preferált kultúra-információt kapja meg vagy állítja be.

**Visszatérési érték:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```

A duplakódos karakterkészletet (DBCS) használó nyelvekhez szánt egyes funkciók számításához szükséges preferált kultúra-információt kapja meg vagy állítja be.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.util.Locale |  |
### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```

Ha a diagram adatforrása egy külső munkafüzet, és nem elérhető, akkor a diagram gyorsítótárából lesz helyreállítva.

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

Ha a diagram adatforrása egy külső munkafüzet, és nem elérhető, akkor a diagram gyorsítótárából lesz helyreállítva.

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