---
title: IChartDataWorksheetCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงถึงคอลเลกชันของแผ่นงานในสมุดงานข้อมูลแผนภูมิ.
type: docs
url: /th/com.aspose.slides/ichartdataworksheetcollection/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
com.aspose.slides.IGenericCollection
```
public interface IChartDataWorksheetCollection extends IGenericCollection<IChartDataWorksheet>
```

แสดงถึงคอลเลกชันของแผ่นงานในสมุดงานข้อมูลแผนภูมิ.

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
| [get_Item(int index)](#get-Item-int-) | คืนค่าแผ่นงานตามดัชนี. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IChartDataWorksheet get_Item(int index)
```


คืนค่าแผ่นงานตามดัชนี.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int | ดัชนีของแผ่นงานในคอลเลกชัน. |

**ค่าที่ส่งกลับ:**
[IChartDataWorksheet](../../com.aspose.slides/ichartdataworksheet) - อินสแตนซ์ของ IChartDataWorksheet.