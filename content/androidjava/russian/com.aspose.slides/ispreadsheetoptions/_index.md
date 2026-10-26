---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options which can be used to specify additional spreadsheets behavior.
type: docs
url: /ru/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Представляет параметры, которые могут использоваться для указания дополнительного поведения электронных таблиц.
## Методы

| Метод | Описание |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Получает или задает информацию о предпочтительной культуре для вычисления некоторых функций, предназначенных для использования с языками, использующими двубайтный набор символов (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Получает или задает информацию о предпочтительной культуре для вычисления некоторых функций, предназначенных для использования с языками, использующими двубайтный набор символов (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Если источник данных для диаграммы является внешней рабочей книгой и она недоступна, она будет восстановлена из кэша диаграмм. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Если источник данных для диаграммы является внешней рабочей книгой и она недоступна, она будет восстановлена из кэша диаграмм. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


Получает или задает информацию о предпочтительной культуре для вычисления некоторых функций, предназначенных для использования с языками, использующими двубайтный набор символов (DBCS).

**Возвращаемое значение:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


Получает или задает информацию о предпочтительной культуре для вычисления некоторых функций, предназначенных для использования с языками, использующими двубайтный набор символов (DBCS).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


Если источник данных для диаграммы является внешней рабочей книгой и она недоступна, она будет восстановлена из кэша диаграмм.

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

**Возвращаемое значение:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


Если источник данных для диаграммы является внешней рабочей книгой и она недоступна, она будет восстановлена из кэша диаграмм.

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

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |