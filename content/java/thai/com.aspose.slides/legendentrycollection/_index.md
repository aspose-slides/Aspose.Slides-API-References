---
title: LegendEntryCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงคอลเลกชัน legends.
type: docs
url: /th/com.aspose.slides/legendentrycollection/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

แสดงคอลเลกชัน legends.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับคุณสมบัติของรายการ legend ที่สอดคล้องกับ Chart.ChartData.Series[0].DataPoints[index] ในกรณีที่ประเภทแผนภูมิอยู่ในรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; หรือสอดคล้องกับ Chart.ChartData.Series[index] สำหรับประเภทแผนภูมิอื่น ๆ. |
| [getCount()](#getCount--) | รับจำนวนรายการ legend. |
### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

รับคุณสมบัติของรายการ legend ที่สอดคล้องกับ Chart.ChartData.Series[0].DataPoints[index] ในกรณีที่ประเภทแผนภูมิอยู่ในรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; หรือสอดคล้องกับ Chart.ChartData.Series[index] สำหรับประเภทแผนภูมิอื่น ๆ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)
### getCount() {#getCount--}
```
public final int getCount()
```

รับจำนวนรายการ legend. int แบบอ่านอย่างเดียว.

**ผลลัพธ์:**
int