---
title: SpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options which can be used to specify additional spreadsheets behavior.
type: docs
weight: 526
url: /androidjava/com.aspose.slides/spreadsheetoptions/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

Represents options which can be used to specify additional spreadsheets behavior.
## Constructors

| Constructor | Description |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | Initializes a new instance of the [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Gets or sets preferred culture information for calculating some functions intended for use with languages that use the double-byte character set (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Gets or sets preferred culture information for calculating some functions intended for use with languages that use the double-byte character set (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache. |
### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```


Initializes a new instance of the [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) class.

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```


Gets or sets preferred culture information for calculating some functions intended for use with languages that use the double-byte character set (DBCS).

**Returns:**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```


Gets or sets preferred culture information for calculating some functions intended for use with languages that use the double-byte character set (DBCS).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```


If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache.

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

**Returns:**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public final void setRecoverWorkbookFromChartCache(boolean value)
```


If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

