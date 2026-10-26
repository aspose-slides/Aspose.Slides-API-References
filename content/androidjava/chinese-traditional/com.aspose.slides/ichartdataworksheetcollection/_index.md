---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides 用於 Android 的 Java API 參考
description: 表示圖表資料工作簿的工作表集合。
type: docs
url: /zh-hant/com.aspose.slides/ichartdataworksheetcollection/
---
**所有已實作的介面：**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

表示圖表資料工作簿的工作表集合。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.Pie, 50, 50, 400, 500);
>      IChartDataWorkbook workbook =  chart.getChartData().getChartDataWorkbook();
>      for (IChartDataWorksheet worksheet : workbook.getWorksheets())
>      {
>          String worksheetName = worksheet.getName();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## 方法

| 方法 | 說明 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 根據索引返回工作表。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```


根據索引返回工作表。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| index | int | 工作表在集合中的索引。 |

**返回:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - IChartDataWorksheet 的實例。