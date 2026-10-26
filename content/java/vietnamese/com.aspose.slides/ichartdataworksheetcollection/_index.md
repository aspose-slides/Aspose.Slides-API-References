---
title: IChartDataWorksheetCollection
second_title: Tham chiếu API Aspose.Slides cho Java
description: Đại diện cho tập hợp các worksheet của workbook dữ liệu biểu đồ.
type: docs
url: /vi/com.aspose.slides/ichartdataworksheetcollection/
---
**Tất cả các giao diện được triển khai:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

Đại diện cho tập hợp các worksheet của workbook dữ liệu biểu đồ.

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
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Trả về worksheet theo chỉ mục. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```

Trả về worksheet theo chỉ mục.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| index | int | Chỉ mục của worksheet trong collection. |

**Giá trị trả về:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - Một thể hiện của IChartDataWorksheet.