---
title: ChartSeriesGroup
second_title: Aspose.Slides สำหรับ Java การอ้างอิง API
description: เป็นตัวแทนของกลุ่มของ series.
type: docs
url: /th/com.aspose.slides/chartseriesgroup/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ Implement ทั้งหมด:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

เป็นตัวแทนของกลุ่มของ series.

--------------------

1) ดูสรุปและหมายเหตุสำหรับคลาส ChartSeriesGroupCollection และ enum CombinableSeriesTypesGroup. 2) กลุ่มของ series มีบาง property ของ series ที่เป็นค่าร่วมกันสำหรับแต่ละ series ในกลุ่ม ("series group properties"). "Series group properties" ในคลาส ChartSeriesGroup เป็นแบบอ่าน/เขียน. แต่ละ "series group properties" สามารถมีการฉายแบบอ่านอย่างเดียวในคลาส ChartSeries.

## Methods

| Method | คำอธิบาย |
| --- | --- |
| [getType()](#getType--) | คืนค่าประเภทของกลุ่ม series นี้. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | บ่งชี้ว่า series ของกลุ่มนี้ถูกพล็อตบนแกนรองหรือไม่. |
| [getSeries()](#getSeries--) | คืนค่าคอลเลกชันของ series. |
| [get_Item(int index)](#get-Item-int-) | ดึง element ที่ตำแหน่ง index ที่ระบุ. |
| [getUpDownBars()](#getUpDownBars--) | ให้การเข้าถึง up/down bars ของแผนภูมิ Line- หรือ Stock-chart. |
| [getGapWidth()](#getGapWidth--) | กำหนดช่องว่างระหว่างกลุ่ม bar หรือ column เป็นเปอร์เซ็นต์ของความกว้างของ bar หรือ column. |
| [setGapWidth(int value)](#setGapWidth-int-) | กำหนดช่องว่างระหว่างกลุ่ม bar หรือ column เป็นเปอร์เซ็นต์ของความกว้างของ bar หรือ column. |
| [getGapDepth()](#getGapDepth--) | คืนค่าหรือกำหนดระยะทางเป็นเปอร์เซ็นต์ของความกว้าง marker ระหว่าง data series ในแผนภูมิ 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | คืนค่าหรือกำหนดระยะทางเป็นเปอร์เซ็นต์ของความกว้าง marker ระหว่าง data series ในแผนภูมิ 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | ดึงหรือกำหนดมุมของชิ้นแรกของแผนภูมิ pie หรือ doughnut เป็นองศา (ตามเข็มนาฬิกาตั้งจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | ดึงหรือกำหนดมุมของชิ้นแรกของแผนภูมิ pie หรือ doughnut เป็นองศา (ตามเข็มนาฬิกาตั้งจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | กำหนดขนาดของรูในแผนภูมิ doughnut (สามารถอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | กำหนดขนาดของรูในแผนภูมิ doughnut (สามารถอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). |
| [getOverlap()](#getOverlap--) | กำหนดว่าบาร์และคอลัมน์ควรทับกันมากเท่าใดในแผนภูมิ 2-D เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | กำหนดว่าบาร์และคอลัมน์ควรทับกันมากเท่าใดในแผนภูมิ 2-D เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | กำหนดขนาดของ pie หรือ bar ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของ pie แรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | กำหนดขนาดของ pie หรือ bar ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของ pie แรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | กำหนดว่าค่าขนาดของ bubble จะถูกแสดงอย่างไรในแผนภูมิ bubble. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | กำหนดว่าค่าขนาดของ bubble จะถูกแสดงอย่างไรในแผนภูมิ bubble. |
| [getPieSplitPosition()](#getPieSplitPosition--) | กำหนดค่าที่จะใช้เพื่อกำหนดว่าจุดข้อมูลใดอยู่ใน pie หรือ bar ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | กำหนดค่าที่จะใช้เพื่อกำหนดว่าจุดข้อมูลใดอยู่ใน pie หรือ bar ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | กำหนดวิธีการที่ใช้เพื่อกำหนดว่าจุดข้อมูลใดอยู่ใน pie หรือ bar ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | กำหนดวิธีการที่ใช้เพื่อกำหนดว่าจุดข้อมูลใดอยู่ใน pie หรือ bar ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [isColorVaried()](#isColorVaried--) | กำหนดว่า marker ของข้อมูลแต่ละตัวใน series มีสีที่ต่างกัน. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | กำหนดว่า marker ของข้อมูลแต่ละตัวใน series มีสีที่ต่างกัน. |
| [hasSeriesLines()](#hasSeriesLines--) | เป็นจริงหาก chart มี series lines. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | เป็นจริงหาก chart มี series lines. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | กำหนดรูปแบบ HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | กำหนดตัวคูณสเกลสำหรับแผนภูมิ bubble (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | กำหนดตัวคูณสเกลสำหรับแผนภูมิ bubble (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | คืนค่าแผนภูมาพาเรนต์. |
| [getSlide()](#getSlide--) | คืนค่า slide พาเรนต์ของ FillFormat. |
| [getPresentation()](#getPresentation--) | คืนค่า presentation พาเรนต์ของ FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

คืนค่าประเภทของกลุ่ม series นี้. อ่านอย่างเดียว [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**คืนค่า:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

บ่งชี้ว่า series ของกลุ่มนี้ถูกพล็อตบนแกนรองหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

คืนค่าคอลเลกชันของ series. อ่านอย่างเดียว [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**คืนค่า:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

ดึง element ที่ตำแหน่ง index ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

ให้การเข้าถึง up/down bars ของแผนภูมิ Line- หรือ Stock-chart. อ่านอย่างเดียว [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**คืนค่า:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

กำหนดช่องว่างระหว่างกลุ่ม bar หรือ column เป็นเปอร์เซ็นต์ของความกว้างของ bar หรือ column. อ่าน/เขียน int.

**คืนค่า:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

กำหนดช่องว่างระหว่างกลุ่ม bar หรือ column เป็นเปอร์เซ็นต์ของความกว้างของ bar หรือ column. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

คืนค่าหรือกำหนดระยะทางเป็นเปอร์เซ็นต์ของความกว้าง marker ระหว่าง data series ในแผนภูมิ 3D. อ่าน/เขียน int.

**คืนค่า:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

คืนค่าหรือกำหนดระยะทางเป็นเปอร์เซ็นต์ของความกว้าง marker ระหว่าง data series ในแผนภูมิ 3D. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

ดึงหรือกำหนดมุมของชิ้นแรกของแผนภูมิ pie หรือ doughnut เป็นองศา (ตามเข็มนาฬิกาตั้งจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). อ่าน/เขียน int.

**คืนค่า:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

ดึงหรือกำหนดมุมของชิ้นแรกของแผนภูมิ pie หรือ doughnut เป็นองศา (ตามเข็มนาฬิกาตั้งจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

กำหนดขนาดของรูในแผนภูมิ doughnut (สามารถอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). อ่าน/เขียน byte.

**คืนค่า:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

กำหนดขนาดของรูในแผนภูมิ doughnut (สามารถอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

กำหนดว่าบาร์และคอลัมน์ควรทับกันมากเท่าใดในแผนภูมิ 2-D เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). - -100%: ช่องว่างสูงสุด (บาร์แยกจากกันอย่างสิ้นเชิง). - 0%: บาร์จัดเรียงต่อกันโดยไม่ทับหรือช่องว่าง. - 100%: ทับสูงสุด (บาร์ทับกันเต็มที่). คุณสมบัตินี้เป็นอ่าน/เขียน byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // ตั้งค่าการทับซ้อนเป็น 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

กำหนดว่าบาร์และคอลัมน์ควรทับกันมากเท่าใดในแผนภูมิ 2-D เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). - -100%: ช่องว่างสูงสุด (บาร์แยกจากกันอย่างสิ้นเชิง). - 0%: บาร์จัดเรียงต่อกันโดยไม่ทับหรือช่องว่าง. - 100%: ทับสูงสุด (บาร์ทับกันเต็มที่). คุณสมบัตินี้เป็นอ่าน/เขียน byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // ตั้งค่าการทับซ้อนเป็น 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

กำหนดขนาดของ pie หรือ bar ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของ pie แรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน/เขียน int.

**คืนค่า:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

กำหนดขนาดของ pie หรือ bar ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของ pie แรก (สามารถอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

กำหนดว่าค่าขนาดของ bubble จะถูกแสดงอย่างไรในแผนภูมิ bubble. อ่าน/เขียน [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**คืนค่า:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

กำหนดว่าค่าขนาดของ bubble จะถูกแสดงอย่างไรในแผนภูมิ bubble. อ่าน/เขียน [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

กำหนดค่าที่จะใช้เพื่อกำหนดว่าจุดข้อมูลใดอยู่ใน pie หรือ bar ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน double.

**คืนค่า:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

กำหนดค่าที่จะใช้เพื่อกำหนดว่าจุดข้อมูลใดอยู่ใน pie หรือ bar ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

กำหนดวิธีการที่ใช้เพื่อกำหนดว่าจุดข้อมูลใดอยู่ใน pie หรือ bar ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [PieSplitType](../../com.aspose.slides/piesplittype).

**คืนค่า:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

กำหนดวิธีการที่ใช้เพื่อกำหนดว่าจุดข้อมูลใดอยู่ใน pie หรือ bar ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [PieSplitType](../../com.aspose.slides/piesplittype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

กำหนดว่า marker ของข้อมูลแต่ละตัวใน series มีสีที่ต่างกัน. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

กำหนดว่า marker ของข้อมูลแต่ละตัวใน series มีสีที่ต่างกัน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

เป็นจริงหาก chart มี series lines. ใช้กับแผนภูมิ stacked bar และ OfPie. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

เป็นจริงหาก chart มี series lines. ใช้กับแผนภูมิ stacked bar และ OfPie. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

กำหนดรูปแบบ HiLowLines. HiLowLines ใช้ร่วมกับประเภทแผนภูมิ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose.

**คืนค่า:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

กำหนดตัวคูณสเกลสำหรับแผนภูมิ bubble (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). อ่าน/เขียน int.

**คืนค่า:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

กำหนดตัวคูณสเกลสำหรับแผนภูมิ bubble (สามารถอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. มีจุดข้อมูลที่ควรวาดใน pie หรือ bar ที่สองของแผนภูมิดังกล่าว. อ่านอย่างเดียว [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**คืนค่า:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่าออบเจกต์ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

คืนค่าแผนภูมาพาเรนต์. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนค่า slide พาเรนต์ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**คืนค่า:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนค่า presentation พาเรนต์ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation)