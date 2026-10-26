---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides for Android via Java API 参考文档
description: 表示图表数据工作簿的工作表集合。
type: docs
url: /zh/com.aspose.slides/ichartdataworksheetcollection/
---
**所有实现的接口：**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

表示图表数据工作簿的工作表集合。

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
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returns the worksheet by index. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)

根据索引返回工作表。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 集合中工作表的索引。 |

**返回值:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - IChartDataWorksheet 的实例。