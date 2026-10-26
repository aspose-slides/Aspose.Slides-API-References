---
title: LegendEntryCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API
description: แสดงคอลเลกชันของ legend.
type: docs
url: /th/com.aspose.slides/legendentrycollection/
---
**การสืบทอด:**
java.lang.Object

**ทั้งหมดที่ทำตามอินเทอร์เฟซ:**
[com.aspose.slides.ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)
```
public class LegendEntryCollection implements ILegendEntryCollection
```

แสดงคอลเลกชันของ legend.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับคุณสมบัติของรายการ legend ที่สอดคล้องกับ Chart.ChartData.Series[0].DataPoints[index] ในกรณีที่ประเภทแผนภูมิอยู่ในรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; หรือสอดคล้องกับ Chart.ChartData.Series[index] สำหรับประเภทแผนภูมิอื่น |
| [getCount()](#getCount--) | รับจำนวนรายการ legend |

### get_Item(int index) {#get-Item-int-}
```
public final ILegendEntryProperties get_Item(int index)
```

รับคุณสมบัติของรายการ legend ที่สอดคล้องกับ Chart.ChartData.Series[0].DataPoints[index] ในกรณีที่ประเภทแผนภูมิอยู่ในรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; หรือสอดคล้องกับ Chart.ChartData.Series[index] สำหรับประเภทแผนภูมิอื่น

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getCount() {#getCount--}
```
public final int getCount()
```

รับจำนวนรายการ legend. อ่านได้อย่างเดียว int.

**คืนค่า:**
int