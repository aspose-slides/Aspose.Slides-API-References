---
title: ISpreadsheetOptions
second_title: Aspose.Slides for Java API Reference
description: Represents options which can be used to specify additional spreadsheets behavior.
type: docs
url: /zh-hant/com.aspose.slides/ispreadsheetoptions/
---```
public interface ISpreadsheetOptions
```

Represents options which can be used to specify additional spreadsheets behavior.
## 方法

| 方法 | 說明 |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | 取得或設定用於計算某些針對使用雙位元組字元集 (DBCS) 語言的函式的首選文化資訊。 |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | 取得或設定用於計算某些針對使用雙位元組字元集 (DBCS) 語言的函式的首選文化資訊。 |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | 如果圖表的資料來源是外部工作簿且不可用，將從圖表快取中復原。 |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | 如果圖表的資料來源是外部工作簿且不可用，將從圖表快取中復原。 |
### getPreferredCulture() {#getPreferredCulture--}
```
public abstract Locale getPreferredCulture()
```


取得或設定用於計算某些針對使用雙位元組字元集 (DBCS) 語言的函式的首選文化資訊。

**返回：**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public abstract void setPreferredCulture(Locale value)
```


取得或設定用於計算某些針對使用雙位元組字元集 (DBCS) 語言的函式的首選文化資訊。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public abstract boolean getRecoverWorkbookFromChartCache()
```


如果圖表的資料來源是外部工作簿且不可用，將從圖表快取中復原。

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


**返回：**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public abstract void setRecoverWorkbookFromChartCache(boolean value)
```


如果圖表的資料來源是外部工作簿且不可用，將從圖表快取中復原。

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
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | boolean |  |