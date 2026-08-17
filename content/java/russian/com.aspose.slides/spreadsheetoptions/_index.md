---
title: SpreadsheetOptions
second_title: Справочник API Aspose.Slides для Java
description: Представляет параметры, которые могут использоваться для указания дополнительного поведения электронных таблиц.
type: docs
url: /ru/com.aspose.slides/spreadsheetoptions/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Представляет параметры, которые могут использоваться для указания дополнительного поведения электронных таблиц.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Инициализирует новый экземпляр [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) класса. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Получает или задает предпочтительную информацию о культуре для вычисления некоторых функций, предназначенных для использования с языками, использующими набор символов двойного байта (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Получает или задает предпочтительную информацию о культуре для вычисления некоторых функций, предназначенных для использования с языками, использующими набор символов двойного байта (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | Если источник данных для диаграммы является внешней книгой и недоступен, он будет восстановлен из кеша диаграммы. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | Если источник данных для диаграммы является внешней книгой и недоступен, он будет восстановлен из кеша диаграммы. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

Инициализирует новый экземпляр [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) класса.

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

Получает или задает предпочтительную информацию о культуре для вычисления некоторых функций, предназначенных для использования с языками, использующими набор символов двойного байта (DBCS).

**Возвращаемое значение:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

Получает или задает предпочтительную информацию о культуре для вычисления некоторых функций, предназначенных для использования с языками, использующими набор символов двойного байта (DBCS).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

Если источник данных для диаграммы является внешней книгой и недоступен, он будет восстановлен из кеша диаграммы.

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
public final void setRecoverWorkbookFromChartCache(boolean value)
```

Если источник данных для диаграммы является внешней книгой и недоступен, он будет восстановлен из кеша диаграммы.

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