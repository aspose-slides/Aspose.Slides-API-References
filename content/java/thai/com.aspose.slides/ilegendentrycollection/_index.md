---
title: ILegendEntryCollection
second_title: Aspose.Slides for Java API Reference
description: Represents legends collection.
type: docs
url: /th/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

เป็นคอลเลกชันของ legend.

## เมธอด

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงคุณสมบัติของรายการ legend ที่สอดคล้องกับ Chart.ChartData.Series[0].DataPoints[index] ในกรณีที่ประเภทแผนภูมิเป็นหนึ่งจากรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; หรือสอดคล้องกับ Chart.ChartData.Series[index] สำหรับประเภทแผนภูมิอื่น ๆ. |
| [getCount()](#getCount--) | ดึงจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน. |

### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

ดึงคุณสมบัติของรายการ legend ที่สอดคล้องกับ Chart.ChartData.Series[0].DataPoints[index] ในกรณีที่ประเภทแผนภูมิเป็นหนึ่งจากรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; หรือสอดคล้องกับ Chart.ChartData.Series[index] สำหรับประเภทแผนภูมิอื่น ๆ.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งคืน:**  
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getCount() {#getCount--}
```
public abstract int getCount()
```

ดึงจำนวนขององค์ประกอบที่มีอยู่จริงในคอลเลกชัน. อ่านอย่างเดียว int.

**ค่าที่ส่งคืน:**  
int