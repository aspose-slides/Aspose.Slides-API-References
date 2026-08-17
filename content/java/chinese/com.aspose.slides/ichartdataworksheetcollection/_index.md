---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides for Java API 参考
description: 表示图表数据工作簿的工作表集合。
type: docs
url: /zh/com.aspose.slides/ichartdataworksheetcollection/
---
**所有实现的接口:**
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
## 方法

| 方法 | 描述 |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | 返回指定索引的工作表。 |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

返回指定索引的工作表。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | int | 集合中工作表的索引。 |

**返回:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - IChartDataWorksheet 的实例。