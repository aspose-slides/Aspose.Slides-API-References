---
title: ILegendEntryCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวแทนของคอลเลกชันของ legend.
type: docs
url: /th/com.aspose.slides/ilegendentrycollection/
---```
public interface ILegendEntryCollection
```

เป็นตัวแทนของคอลเลกชันของ legend.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับคุณสมบัติของรายการ legend ที่สอดคล้องกับ Chart.ChartData.Series[0].DataPoints[index] ในกรณีที่ชนิดแผนภูมิเป็นหนึ่งในรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; หรือสอดคล้องกับ Chart.ChartData.Series[index] สำหรับชนิดแผนภูมิอื่นๆ |
| [getCount()](#getCount--) | รับจำนวนขององค์ประกอบที่อยู่ในคอลเลกชันจริงๆ |

### get_Item(int index) {#get-Item-int-}
```
public abstract ILegendEntryProperties get_Item(int index)
```

รับคุณสมบัติของรายการ legend ที่สอดคล้องกับ Chart.ChartData.Series[0].DataPoints[index] ในกรณีที่ชนิดแผนภูมิเป็นหนึ่งในรายการต่อไปนี้: ChartType.BarOfPie, ChartType.ExplodedPie, ChartType.ExplodedPie3D, ChartType.Pie, ChartType.Pie3D, ChartType.PieOfPie; หรือสอดคล้องกับ Chart.ChartData.Series[index] สำหรับชนิดแผนภูมิอื่นๆ

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่คืน:**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)

### getCount() {#getCount--}
```
public abstract int getCount()
```

รับจำนวนขององค์ประกอบที่อยู่ในคอลเลกชันจริงๆ. อ่านอย่างเดียว int.

**ค่าที่คืน:**
int