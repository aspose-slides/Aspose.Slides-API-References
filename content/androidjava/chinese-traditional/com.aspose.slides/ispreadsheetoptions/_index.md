---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options which can be used to specify additional spreadsheets behavior.
type: docs
url: /zh-hant/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

表示可用於指定其他試算表行為的選項。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | Gets or sets preferred culture information for calculating some functions intended for use with languages that use the double-byte character set (DBCS). |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | Gets or sets preferred culture information for calculating some functions intended for use with languages that use the double-byte character set (DBCS). |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache. |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | If data source for the chart is an external workbook and it's not available, it will be recovered from the chart cache. |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```

取得或設定用於計算某些函式的首選語系資訊，這些函式旨在用於使用雙位元組字元集（DBCS）的語言。

**返回值：**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```

取得或設定用於計算某些函式的首選語系資訊，這些函式旨在用於使用雙位元組字元集（DBCS）的語言。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```

如果圖表的資料來源是外部活頁簿且不可用，將從圖表快取中恢復。

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

**返回值：**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```

如果圖表的資料來源是外部活頁簿且不可用，將從圖表快取中恢復。

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

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| value | boolean |  |