---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Java API Reference
description: Представляет параметры, которые могут использоваться для указания дополнительного поведения электронных таблиц.
type: docs
url: /ru/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Представляет параметры, которые могут использоваться для указания дополнительного поведения электронных таблиц.
## Методы

| Метод | Описание |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Получает или задает предпочтительную информацию о культуре для вычисления некоторых функций, предназначенных для использования с языками, использующими набор двойных байтов (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Получает или задает предпочтительную информацию о культуре для вычисления некоторых функций, предназначенных для использования с языками, использующими набор двойных байтов (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Если источник данных для диаграммы является внешней книгой и недоступен, он будет восстановлен из кэша диаграммы. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Если источник данных для диаграммы является внешней книгой и недоступен, он будет восстановлен из кэша диаграммы. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


Получает или задает предпочтительную информацию о культуре для вычисления некоторых функций, предназначенных для использования с языками, использующими набор двойных байтов (DBCS).

**Возвращаемое значение:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


Получает или задает предпочтительную информацию о культуре для вычисления некоторых функций, предназначенных для использования с языками, использующими набор двойных байтов (DBCS).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


Если источник данных для диаграммы является внешней книгой и недоступен, он будет восстановлен из кэша диаграммы.

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


Если источник данных для диаграммы является внешней книгой и недоступен, он будет восстановлен из кэша диаграммы.

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