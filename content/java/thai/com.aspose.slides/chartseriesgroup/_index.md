---
title: ChartSeriesGroup
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แทนกลุ่มของซีรีส์.
type: docs
url: /th/com.aspose.slides/chartseriesgroup/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

แทนกลุ่มของซีรีส์.

--------------------

1) ดูสรุปและหมายเหตุสำหรับคลาส ChartSeriesGroupCollection และ enum CombinableSeriesTypesGroup. 2) กลุ่มของซีรีส์มีคุณสมบัติบางอย่างที่เป็นเรื่องทั่วไปสำหรับแต่ละซีรีส์ในกลุ่ม (“คุณสมบัติของกลุ่มซีรีส์”). “คุณสมบัติของกลุ่มซีรีส์” ในคลาส ChartSeriesGroup เป็นแบบอ่าน/เขียน. แต่ละ “คุณสมบัติของกลุ่มซีรีส์” สามารถมีการฉายแบบอ่านอย่างเดียวในคลาส ChartSeries.
## เมธอด

| เมธอด | รายละเอียด |
| --- | --- |
| [getType()](#getType--) | ส่งคืนประเภทของกลุ่มซีรีส์นี้. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | ระบุว่าชุดข้อมูลของกลุ่มนี้ถูกพล็อตบนแกนรองหรือไม่. |
| [getSeries()](#getSeries--) | ส่งคืนคอลเล็กชันของซีรีส์. |
| [get_Item(int index)](#get-Item-int-) | รับองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [getUpDownBars()](#getUpDownBars--) | ให้การเข้าถึงแถบขึ้น/ลงของแผนภูมิ Line หรือ Stock. |
| [getGapWidth()](#getGapWidth--) | รับหรือกำหนดระยะห่างระหว่างกลุ่มแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแท่งหรือคอลัมน์. |
| [setGapWidth(int value)](#setGapWidth-int-) | รับหรือกำหนดระยะห่างระหว่างกลุ่มแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแท่งหรือคอลัมน์. |
| [getGapDepth()](#getGapDepth--) | รับหรือกำหนดระยะห่างระหว่างชุดข้อมูลในแผนภูมิ 3 มิติเป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์. |
| [setGapDepth(int value)](#setGapDepth-int-) | รับหรือกำหนดระยะห่างระหว่างชุดข้อมูลในแผนภูมิ 3 มิติเป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | รับหรือกำหนดมุมของส่วนแรกของแผนภูมิพายหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาตั้งแต่ด้านบน, ตั้งแต่ 0 ถึง 360 องศา). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | รับหรือกำหนดมุมของส่วนแรกของแผนภูมิพายหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาตั้งแต่ด้านบน, ตั้งแต่ 0 ถึง 360 องศา). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | ระบุขนาดของรูในแผนภูมิโดนัท (อาจอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | ระบุขนาดของรูในแผนภูมิโดนัท (อาจอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). |
| [getOverlap()](#getOverlap--) | ระบุระดับการทับซ้อนของแท่งและคอลัมน์ในแผนภูมิ 2 มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | ระบุระดับการทับซ้อนของแท่งและคอลัมน์ในแผนภูมิ 2 มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | ระบุขนาดของพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (อาจอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | ระบุขนาดของพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (อาจอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | ระบุวิธีการแสดงค่าขนาดของบับเบิลในแผนภูมิบับเบิล. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | ระบุวิธีการแสดงค่าขนาดของบับเบิลในแผนภูมิบับเบิล. |
| [getPieSplitPosition()](#getPieSplitPosition--) | ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [isColorVaried()](#isColorVaried--) | ระบุว่ามาร์คเกอร์ข้อมูลแต่ละตัวในซีรีส์มีสีที่แตกต่างกัน. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | ระบุว่ามาร์คเกอร์ข้อมูลแต่ละตัวในซีรีส์มีสีที่แตกต่างกัน. |
| [hasSeriesLines()](#hasSeriesLines--) | จริงหากแผนภูมิมีเส้นของซีรีส์. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | จริงหากแผนภูมิมีเส้นของซีรีส์. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | ระบุรูปแบบ HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | ระบุปัจจัยสเกลสำหรับแผนภูมิบับเบิล (อาจอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | ระบุปัจจัยสเกลสำหรับแผนภูมิบับเบิล (อาจอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | ข้อมูลการแยกส่วนแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกส่วนแบบกำหนดเอง. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | ส่งคืนแผนภูมิแม่. |
| [getSlide()](#getSlide--) | ส่งคืนสไลด์แม่ของ FillFormat. |
| [getPresentation()](#getPresentation--) | ส่งคืนการนำเสนอแม่ของ FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

ส่งคืนประเภทของกลุ่มซีรีส์นี้. อ่านอย่างเดียว [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**ส่งคืน:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

ระบุว่าชุดข้อมูลของกลุ่มนี้ถูกพล็อตบนแกนรองหรือไม่. อ่านอย่างเดียว boolean.

**ส่งคืน:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

ส่งคืนคอลเล็กชันของซีรีส์. อ่านอย่างเดียว [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**ส่งคืน:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

รับองค์ประกอบที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| index | int |  |

**ส่งคืน:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

ให้การเข้าถึงแถบขึ้น/ลงของแผนภูมิ Line หรือ Stock. อ่านอย่างเดียว [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**ส่งคืน:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

รับหรือกำหนดระยะห่างระหว่างกลุ่มแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแท่งหรือคอลัมน์. ค่าต้องอยู่ระหว่าง 0 ถึง 500. อ่าน/เขียน int.

--------------------

พร็อพเพอร์ตี้นี้ใช้กับซีรีส์ของประเภทต่อไปนี้: Bar subtypes (ดูวิธีการ [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) ด้วย), Column subtypes (ดูวิธีการ [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) ด้วย), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**ส่งคืน:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

รับหรือกำหนดระยะห่างระหว่างกลุ่มแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแท่งหรือคอลัมน์. ค่าต้องอยู่ระหว่าง 0 ถึง 500. อ่าน/เขียน int.

--------------------

พร็อพเพอร์ตี้นี้ใช้กับซีรีส์ของประเภทต่อไปนี้: Bar subtypes (ดูวิธีการ [ChartTypeCharacterizer.isChartTypeBar(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeBar-int-) ด้วย), Column subtypes (ดูวิธีการ [ChartTypeCharacterizer.isChartTypeColumn(int)](../../com.aspose.slides/charttypecharacterizer\#isChartTypeColumn-int-) ด้วย), [ChartType.BarOfPie](../../com.aspose.slides/charttype\#BarOfPie), [ChartType.PieOfPie](../../com.aspose.slides/charttype\#PieOfPie), [ChartType.BoxAndWhisker](../../com.aspose.slides/charttype\#BoxAndWhisker), [ChartType.Funnel](../../com.aspose.slides/charttype\#Funnel), [ChartType.Histogram](../../com.aspose.slides/charttype\#Histogram), [ChartType.Waterfall](../../com.aspose.slides/charttype\#Waterfall).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

รับหรือกำหนดระยะห่างระหว่างชุดข้อมูลในแผนภูมิ 3 มิติเป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์. ค่าต้องอยู่ระหว่าง 0 ถึง 500. อ่าน/เขียน int.

--------------------

พร็อพเพอร์ตี้นี้ใช้กับซีรีส์ของประเภทต่อไปนี้: 3D bar and column subtypes (ดูวิธีการ [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) ด้วย), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**ส่งคืน:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

รับหรือกำหนดระยะห่างระหว่างชุดข้อมูลในแผนภูมิ 3 มิติเป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์. ค่าต้องอยู่ระหว่าง 0 ถึง 500. อ่าน/เขียน int.

--------------------

พร็อพเพอร์ตี้นี้ใช้กับซีรีส์ของประเภทต่อไปนี้: 3D bar and column subtypes (ดูวิธีการ [ChartTypeCharacterizer.isBar3DChart(int)](../../com.aspose.slides/charttypecharacterizer\#isBar3DChart-int-) ด้วย), [ChartType.Line3D](../../com.aspose.slides/charttype\#Line3D), [ChartType.Area3D](../../com.aspose.slides/charttype\#Area3D), [ChartType.StackedArea3D](../../com.aspose.slides/charttype\#StackedArea3D), [ChartType.PercentsStackedArea3D](../../com.aspose.slides/charttype\#PercentsStackedArea3D).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

รับหรือกำหนดมุมของส่วนแรกของแผนภูมิพายหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาตั้งแต่ด้านบน, ตั้งแต่ 0 ถึง 360 องศา). อ่าน/เขียน int.

**ส่งคืน:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

รับหรือกำหนดมุมของส่วนแรกของแผนภูมิพายหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาตั้งแต่ด้านบน, ตั้งแต่ 0 ถึง 360 องศา). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

ระบุขนาดของรูในแผนภูมิโดนัท (อาจอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). อ่าน/เขียน byte.

**ส่งคืน:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

ระบุขนาดของรูในแผนภูมิโดนัท (อาจอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่พล็อต). อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

ระบุระดับการทับซ้อนของแท่งและคอลัมน์ในแผนภูมิ 2 มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). -100%: ระยะห่างสูงสุด (แท่งแยกจากกันอย่างสมบูรณ์). 0%: แท่งวางเคียงกันโดยไม่มีการทับซ้อนหรือช่องว่าง. 100%: การทับซ้อนสูงสุด (แท่งทับซ้อนกันทั้งหมด). พร็อพเพอร์ตี้นี้เป็นอ่าน/เขียน byte.

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


**ส่งคืน:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public final void setOverlap(byte value)
```

ระบุระดับการทับซ้อนของแท่งและคอลัมน์ในแผนภูมิ 2 มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). -100%: ระยะห่างสูงสุด (แท่งแยกจากกันอย่างสมบูรณ์). 0%: แท่งวางเคียงกันโดยไม่มีการทับซ้อนหรือช่องว่าง. 100%: การทับซ้อนสูงสุด (แท่งทับซ้อนกันทั้งหมด). พร็อพเพอร์ตี้นี้เป็นอ่าน/เขียน byte.

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
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

ระบุขนาดของพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (อาจอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน/เขียน int.

**ส่งคืน:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

ระบุขนาดของพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดพายแรก (อาจอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

ระบุวิธีการแสดงค่าขนาดของบับเบิลในแผนภูมิบับเบิล. อ่าน/เขียน [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**ส่งคืน:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

ระบุวิธีการแสดงค่าขนาดของบับเบิลในแผนภูมิบับเบิล. อ่าน/เขียน [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับพร็อพเพอร์ตี้ PieSplitBy. อ่าน/เขียน double.

**ส่งคืน:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับพร็อพเพอร์ตี้ PieSplitBy. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [PieSplitType](../../com.aspose.slides/piesplittype).

**ส่งคืน:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [PieSplitType](../../com.aspose.slides/piesplittype).

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

ระบุว่ามาร์คเกอร์ข้อมูลแต่ละตัวในซีรีส์มีสีที่แตกต่างกัน. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

ระบุว่ามาร์คเกอร์ข้อมูลแต่ละตัวในซีรีส์มีสีที่แตกต่างกัน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

จริงหากแผนภูมิมีเส้นของซีรีส์. ใช้กับแผนภูมิ stacked bar และ OfPie. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

จริงหากแผนภูมิมีเส้นของซีรีส์. ใช้กับแผนภูมิ stacked bar และ OfPie. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

ระบุรูปแบบ HiLowLines. HiLowLines ใช้ร่วมกับประเภทแผนภูมิ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose.

**ส่งคืน:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

ระบุปัจจัยสเกลสำหรับแผนภูมิบับเบิล (อาจอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). อ่าน/เขียน int.

**ส่งคืน:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

ระบุปัจจัยสเกลสำหรับแผนภูมิบับเบิล (อาจอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | รายละเอียด |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

ข้อมูลการแยกส่วนแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกส่วนแบบกำหนดเอง. มีจุดข้อมูลที่ควรวาดในพายหรือแท่งที่สองของแผนภูมิ. อ่านอย่างเดียว [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**ส่งคืน:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

ส่งคืนวัตถุ Parent_Immediate. อ่านอย่างเดียว IDOMObject.

**ส่งคืน:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

ส่งคืนแผนภูมิแม่. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**ส่งคืน:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

ส่งคืนสไลด์แม่ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**ส่งคืน:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ส่งคืนการนำเสนอแม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**ส่งคืน:**
[IPresentation](../../com.aspose.slides/ipresentation)