---
title: IChartSeriesGroup
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงกลุ่มของซีรีส์.
type: docs
url: /th/com.aspose.slides/ichartseriesgroup/
---
**อินเทอร์เฟซที่ทำทั้งหมด:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

แสดงถึงกลุ่มของซีรีส์

--------------------

1) ดูสรุปและหมายเหตุสำหรับคลาส ChartSeriesGroupCollection และ enum CombinableSeriesTypesGroup 2) กลุ่มของซีรีส์มีคุณสมบัติบางอย่างที่เป็นของร่วมกันสำหรับแต่ละซีรีส์ในกลุ่ม (“คุณสมบัติของกลุ่มซีรีส์”). “คุณสมบัติของกลุ่มซีรีส์” ในคลาส ChartSeriesGroup เป็นแบบอ่าน/เขียน. แต่ละ “คุณสมบัติของกลุ่มซีรีส์” สามารถมีการฉายแบบอ่านอย่างเดียวในคลาส ChartSeries
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getType()](#getType--) | ส่งคืนประเภทของกลุ่มซีรีส์นี้. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | บ่งบอกว่าซีรีส์ของกลุ่มนี้ถูกวางบนแกนรองหรือไม่. |
| [getSeries()](#getSeries--) | ส่งคืนคอลเลกชันแบบอ่านอย่างเดียวของซีรีส์แผนภูมิ. |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [getUpDownBars()](#getUpDownBars--) | ให้การเข้าถึงแถบขึ้น/ลงของแผนภูมิ Line หรือ Stock. |
| [getGapWidth()](#getGapWidth--) | รับหรือกำหนดระยะห่างระหว่างคลัสเตอร์ของแถบหรือคอลัมน์ โดยเป็นเปอร์เซ็นต์ของความกว้างแถบหรือคอลัมน์. |
| [setGapWidth(int value)](#setGapWidth-int-) | รับหรือกำหนดระยะห่างระหว่างคลัสเตอร์ของแถบหรือคอลัมน์ โดยเป็นเปอร์เซ็นต์ของความกว้างแถบหรือคอลัมน์. |
| [getGapDepth()](#getGapDepth--) | รับหรือกำหนดระยะห่างระหว่างซีรีส์ข้อมูลในแผนภูมิ 3 มิติ โดยเป็นเปอร์เซ็นต์ของความกว้างมาร์กเกอร์. |
| [setGapDepth(int value)](#setGapDepth-int-) | รับหรือกำหนดระยะห่างระหว่างซีรีส์ข้อมูลในแผนภูมิ 3 มิติ โดยเป็นเปอร์เซ็นต์ของความกว้างมาร์กเกอร์. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | รับหรือกำหนดมุมของชิ้นแรกของแผนภูมิปายหรือโดนัทเป็นองศา (นาฬิกาเดินจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | รับหรือกำหนดมุมของชิ้นแรกของแผนภูมิปายหรือโดนัทเป็นองศา (นาฬิกาเดินจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). |
| [isColorVaried()](#isColorVaried--) | ระบุว่าตัวบ่งชี้ข้อมูลแต่ละจุดในซีรีส์มีสีต่างกัน. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | ระบุว่าตัวบ่งชี้ข้อมูลแต่ละจุดในซีรีส์มีสีต่างกัน. |
| [hasSeriesLines()](#hasSeriesLines--) | จริงหากแผนภูมิมีเส้นซีรีส์. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | จริงหากแผนภูมิมีเส้นซีรีส์. |
| [getOverlap()](#getOverlap--) | ระบุว่าบาร์และคอลัมน์ควรทับซ้อนกันบนแผนภูมิ 2-มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100 % ถึง 100 %). |
| [setOverlap(byte value)](#setOverlap-byte-) | ระบุว่าบาร์และคอลัมน์ควรทับซ้อนกันบนแผนภูมิ 2-มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100 % ถึง 100 %). |
| [getSecondPieSize()](#getSecondPieSize--) | ระบุขนาดของพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (สามารถอยู่ระหว่าง 5-200 %). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | ระบุขนาดของพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (สามารถอยู่ระหว่าง 5-200 %). |
| [getPieSplitPosition()](#getPieSplitPosition--) | ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | ระบุวิธีกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | ระบุวิธีกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | ระบุขนาดของช่องในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10-90 % ของขนาดพื้นที่พล็อต). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | ระบุขนาดของช่องในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10-90 % ของขนาดพื้นที่พล็อต). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | ระบุค่าสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0-300 % ของขนาดเริ่มต้น). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | ระบุค่าสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0-300 % ของขนาดเริ่มต้น). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | ระบุรูปแบบ HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | ระบุว่าค่าอัตราขนาดฟองบนแผนภูมิบับเบิลจะแสดงอย่างไร. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | ระบุว่าค่าอัตราขนาดฟองบนแผนภูมิบับเบิลจะแสดงอย่างไร. |

### getType() {#getType--}
```
public abstract int getType()
```

ส่งคืนประเภทของกลุ่มซีรีส์นี้. อ่านอย่างเดียว [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**ค่าที่ส่งคืน:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

บ่งบอกว่าซีรีส์ของกลุ่มนี้ถูกวางบนแกนรองหรือไม่. อ่านอย่างเดียว boolean.

**ค่าที่ส่งคืน:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

ส่งคืนคอลเลกชันแบบอ่านอย่างเดียวของซีรีส์แผนภูมิ. อ่านอย่างเดียว [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**ค่าที่ส่งคืน:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งคืน:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

ให้การเข้าถึงแถบขึ้น/ลงของแผนภูมิ Line หรือ Stock. อ่านอย่างเดียว [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**ค่าที่ส่งคืน:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

รับหรือกำหนดระยะห่างระหว่างคลัสเตอร์ของแถบหรือคอลัมน์ โดยเป็นเปอร์เซ็นต์ของความกว้างแถบหรือคอลัมน์. ค่าต้องอยู่ระหว่าง 0 ถึง 500. อ่าน/เขียน int.

--------------------

คุณสมบัตินี้ใช้กับซีรีส์ของประเภทต่อไปนี้: ทุกชนิดของบาร์และคอลัมน์ย่อย, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**ค่าที่ส่งคืน:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

รับหรือกำหนดระยะห่างระหว่างคลัสเตอร์ของแถบหรือคอลัมน์ โดยเป็นเปอร์เซ็นต์ของความกว้างแถบหรือคอลัมน์. ค่าต้องอยู่ระหว่าง 0 ถึง 500. อ่าน/เขียน int.

--------------------

คุณสมบัตินี้ใช้กับซีรีส์ของประเภทต่อไปนี้: ทุกชนิดของบาร์และคอลัมน์ย่อย, [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

รับหรือกำหนดระยะห่างระหว่างซีรีส์ข้อมูลในแผนภูมิ 3 มิติ โดยเป็นเปอร์เซ็นต์ของความกว้างมาร์กเกอร์. ค่าต้องอยู่ระหว่าง 0 ถึง 500. อ่าน/เขียน int.

--------------------

คุณสมบัตินี้ใช้กับซีรีส์ของประเภทต่อไปนี้: ชนิดบาร์และคอลัมน์ 3 มิติย่อย, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**ค่าที่ส่งคืน:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

รับหรือกำหนดระยะห่างระหว่างซีรีส์ข้อมูลในแผนภูมิ 3 มิติ โดยเป็นเปอร์เซ็นต์ของความกว้างมาร์กเกอร์. ค่าต้องอยู่ระหว่าง 0 ถึง 500. อ่าน/เขียน int.

--------------------

คุณสมบัตินี้ใช้กับซีรีส์ของประเภทต่อไปนี้: ชนิดบาร์และคอลัมน์ 3 มิติย่อย, [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

รับหรือกำหนดมุมของชิ้นแรกของแผนภูมิปายหรือโดนัทเป็นองศา (นาฬิกาเดินจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). อ่าน/เขียน int.

**ค่าที่ส่งคืน:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

รับหรือกำหนดมุมของชิ้นแรกของแผนภูมิปายหรือโดนัทเป็นองศา (นาฬิกาเดินจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

ระบุว่าตัวบ่งชี้ข้อมูลแต่ละจุดในซีรีส์มีสีต่างกัน. อ่าน/เขียน boolean.

**ค่าที่ส่งคืน:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

ระบุว่าตัวบ่งชี้ข้อมูลแต่ละจุดในซีรีส์มีสีต่างกัน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

จริงหากแผนภูมิมีเส้นซีรีส์. ใช้กับแผนภูมิ stacked bar และ OfPie. อ่าน/เขียน boolean.

**ค่าที่ส่งคืน:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

จริงหากแผนภูมิมีเส้นซีรีส์. ใช้กับแผนภูมิ stacked bar และ OfPie. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

ระบุว่าบาร์และคอลัมน์ควรทับซ้อนกันบนแผนภูมิ 2-มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100 % ถึง 100 %). - -100 %: ระยะห่างสูงสุด (บาร์แยกจากกันอย่างสมบูรณ์) - 0 %: บาร์วางข้างกันโดยไม่มีการทับซ้อนหรือระยะห่าง - 100 %: ทับซ้อนสูงสุด (บาร์ทับกันทั้งหมด) คุณสมบัตินี้เป็น byte อ่าน/เขียน.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // กำหนดการทับซ้อนเป็น 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**ค่าที่ส่งคืน:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

ระบุว่าบาร์และคอลัมน์ควรทับซ้อนกันบนแผนภูมิ 2-มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100 % ถึง 100 %). - -100 %: ระยะห่างสูงสุด (บาร์แยกจากกันอย่างสมบูรณ์) - 0 %: บาร์วางข้างกันโดยไม่มีการทับซ้อนหรือระยะห่าง - 100 %: ทับซ้อนสูงสุด (บาร์ทับกันทั้งหมด) คุณสมบัตินี้เป็น byte อ่าน/เขียน.

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
public abstract int getSecondPieSize()
```

ระบุขนาดของพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (สามารถอยู่ระหว่าง 5-200 %). อ่าน/เขียน int.

**ค่าที่ส่งคืน:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

ระบุขนาดของพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (สามารถอยู่ระหว่าง 5-200 %). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน double.

**ค่าที่ส่งคืน:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

ระบุวิธีกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [PieSplitType](../../com.aspose.slides/piesplittype).

**ค่าที่ส่งคืน:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

ระบุวิธีกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [PieSplitType](../../com.aspose.slides/piesplittype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. มีจุดข้อมูลที่ควรวาดในพายหรือแถบที่สองของแผนภูมิ. อ่านอย่างเดียว [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**ค่าที่ส่งคืน:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

ระบุขนาดของช่องในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10-90 % ของขนาดพื้นที่พล็อต). อ่าน/เขียน byte.

**ค่าที่ส่งคืน:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

ระบุขนาดของช่องในแผนภูมิโดนัท (สามารถอยู่ระหว่าง 10-90 % ของขนาดพื้นที่พล็อต). อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

ระบุค่าสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0-300 % ของขนาดเริ่มต้น). อ่าน/เขียน int.

**ค่าที่ส่งคืน:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

ระบุค่าสเกลสำหรับแผนภูมิบับเบิล (สามารถอยู่ระหว่าง 0-300 % ของขนาดเริ่มต้น). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

ระบุรูปแบบ HiLowLines. HiLowLines ใช้กับประเภทแผนภูมิ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose.

**ค่าที่ส่งคืน:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

ระบุว่าค่าอัตราขนาดฟองบนแผนภูมิบับเบิลจะแสดงอย่างไร. อ่าน/เขียน [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**ค่าที่ส่งคืน:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

ระบุว่าค่าอัตราขนาดฟองบนแผนภูมิบับเบิลจะแสดงอย่างไร. อ่าน/เขียน [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |