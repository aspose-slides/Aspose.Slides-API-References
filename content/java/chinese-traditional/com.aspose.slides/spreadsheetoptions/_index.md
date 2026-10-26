---
title: SpreadsheetOptions
second_title: Aspose.Slides for Java API 參考
description: 代表可用於指定額外試算表行為的選項。
type: docs
url: /zh-hant/com.aspose.slides/spreadsheetoptions/
---
**繼承：**
java.lang.Object

**所有已實作的介面：**
[com.aspose.slides.ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)
```
public class SpreadsheetOptions implements ISpreadsheetOptions
```

代表可用於指定額外試算表行為的選項。

## 建構函式

| Constructor | Description |
| --- | --- |
| [SpreadsheetOptions()](#SpreadsheetOptions--) | 初始化 [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) 類別的新實例。 |

## 方法

| Method | Description |
| --- | --- |
| [getPreferredCulture()](#getPreferredCulture--) | 取得或設定首選語系資訊，以計算針對使用雙位元組字元集 (DBCS) 語言的某些函式。 |
| [setPreferredCulture(Locale value)](#setPreferredCulture-java.util.Locale-) | 取得或設定首選語系資訊，以計算針對使用雙位元組字元集 (DBCS) 語言的某些函式。 |
| [getRecoverWorkbookFromChartCache()](#getRecoverWorkbookFromChartCache--) | 如果圖表的資料來源是外部活頁簿且無法取得，將從圖表快取中復原。 |
| [setRecoverWorkbookFromChartCache(boolean value)](#setRecoverWorkbookFromChartCache-boolean-) | 如果圖表的資料來源是外部活頁簿且無法取得，將從圖表快取中復原。 |

### SpreadsheetOptions() {#SpreadsheetOptions--}
```
public SpreadsheetOptions()
```

初始化 [SpreadsheetOptions](../../com.aspose.slides/spreadsheetoptions) 類別的新實例。

### getPreferredCulture() {#getPreferredCulture--}
```
public final Locale getPreferredCulture()
```

取得或設定首選語系資訊，以計算針對使用雙位元組字元集 (DBCS) 語言的某些函式。

**回傳值：**
java.util.Locale
### setPreferredCulture(Locale value) {#setPreferredCulture-java.util.Locale-}
```
public final void setPreferredCulture(Locale value)
```

取得或設定首選語系資訊，以計算針對使用雙位元組字元集 (DBCS) 語言的某些函式。

**參數：**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Locale |  |

### getRecoverWorkbookFromChartCache() {#getRecoverWorkbookFromChartCache--}
```
public final boolean getRecoverWorkbookFromChartCache()
```

如果圖表的資料來源是外部活頁簿且無法取得，將從圖表快取中復原。

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

**回傳值：**
boolean
### setRecoverWorkbookFromChartCache(boolean value) {#setRecoverWorkbookFromChartCache-boolean-}
```
public final void setRecoverWorkbookFromChartCache(boolean value)
```

如果圖表的資料來源是外部活頁簿且無法取得，將從圖表快取中復原。

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
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |