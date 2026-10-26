---
title: IChartDataWorksheetCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แทนชุดการเก็บรวบรวมของแผ่นงานของเวิร์กบุ๊กข้อมูลแผนภูมิ.
type: docs
url: /th/com.aspose.slides/ichartdataworksheetcollection/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

แทนชุดการเก็บรวบรวมของแผ่นงานของเวิร์กบุ๊กข้อมูลแผนภูมิ.

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
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | คืนแผ่นงานตามดัชนี. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```


คืนแผ่นงานตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแผ่นงานในคอลเลกชัน. |

**คืนค่า:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - อินสแตนซ์ของ IChartDataWorksheet.