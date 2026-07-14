---
title: ChartSeriesGroup
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แทนกลุ่มของชุดข้อมูล.
type: docs
url: /th/com.aspose.slides/chartseriesgroup/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IChartSeriesGroup](../../com.aspose.slides/ichartseriesgroup), com.aspose.slides.IDOMObject
```
public class ChartSeriesGroup implements IChartSeriesGroup, IDOMObject
```

แทนกลุ่มของชุดข้อมูล.

--------------------

1) ดูสรุปและหมายเหตุสำหรับคลาส ChartSeriesGroupCollection และ enum CombinableSeriesTypesGroup. 2) กลุ่มของชุดข้อมูลมีคุณสมบัติบางอย่างที่เป็นของชุดข้อมูลทั้งหมดในกลุ่ม ("คุณสมบัติของกลุ่มชุดข้อมูล"). "คุณสมบัติของกลุ่มชุดข้อมูล" ในคลาส ChartSeriesGroup เป็นแบบอ่าน/เขียน. แต่ละ "คุณสมบัติของกลุ่มชุดข้อมูล" สามารถมีการฉายแบบอ่านอย่างเดียวในคลาส ChartSeries.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getType()](#getType--) | คืนค่าประเภทของกลุ่มชุดข้อมูลนี้. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | บ่งชี้ว่าชุดข้อมูลของกลุ่มนี้ถูกพล็อตบนแกนรองหรือไม่. |
| [getSeries()](#getSeries--) | คืนค่าคอลเลกชันของชุดข้อมูล. |
| [get_Item(int index)](#get-Item-int-) | ดึงเอาองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [getUpDownBars()](#getUpDownBars--) | ให้การเข้าถึงแถบขึ้น/ลงของแผนภูมิ Line หรือ Stock. |
| [getGapWidth()](#getGapWidth--) | กำหนดระยะห่างระหว่างกลุ่มแถบหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแถบหรือคอลัมน์. |
| [setGapWidth(int value)](#setGapWidth-int-) | กำหนดระยะห่างระหว่างกลุ่มแถบหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแถบหรือคอลัมน์. |
| [getGapDepth()](#getGapDepth--) | คืนค่าหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์ ระหว่างชุดข้อมูลในแผนภูมิ 3D. |
| [setGapDepth(int value)](#setGapDepth-int-) | คืนค่าหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์ ระหว่างชุดข้อมูลในแผนภูมิ 3D. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | ดึงหรือกำหนดมุมของชิ้นแรกของแผนภูมิพายหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | ดึงหรือกำหนดมุมของชิ้นแรกของแผนภูมิพายหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | กำหนดขนาดของรูในแผนภูมิโดนัท (อาจอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่การวาด). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | กำหนดขนาดของรูในแผนภูมิโดนัท (อาจอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่การวาด). |
| [getOverlap()](#getOverlap--) | กำหนดบาร์และคอลัมน์ทับซ้อนกันบนแผนภูมิ 2 มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | กำหนดบาร์และคอลัมน์ทับซ้อนกันบนแผนภูมิ 2 มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | กำหนดขนาดของพายหรือแถบที่สองของแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพาย เป็นเปอร์เซ็นต์ของขนาดของพายแรก (อาจอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | กำหนดขนาดของพายหรือแถบที่สองของแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพาย เป็นเปอร์เซ็นต์ของขนาดของพายแรก (อาจอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | กำหนดวิธีการแสดงค่าขนาดของฟองบนแผนภูมิบับเบิล. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | กำหนดวิธีการแสดงค่าขนาดของฟองบนแผนภูมิบับเบิล. |
| [getPieSplitPosition()](#getPieSplitPosition--) | กำหนดค่าที่ใช้เพื่อระบุว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพาย. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | กำหนดค่าที่ใช้เพื่อระบุว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพาย. |
| [getPieSplitBy()](#getPieSplitBy--) | กำหนดวิธีการระบุว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพาย. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | กำหนดวิธีการระบุว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพาย. |
| [isColorVaried()](#isColorVaried--) | กำหนดว่ามาร์คเกอร์ข้อมูลแต่ละจุดในชุดข้อมูลมีสีที่แตกต่างกัน. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | กำหนดว่ามาร์คเกอร์ข้อมูลแต่ละจุดในชุดข้อมูลมีสีที่แตกต่างกัน. |
| [hasSeriesLines()](#hasSeriesLines--) | เป็นจริงหากแผนภูมิมีเส้นชุดข้อมูล. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | เป็นจริงหากแผนภูมิมีเส้นชุดข้อมูล. |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | กำหนดรูปแบบ HiLowLines. |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | กำหนดปัจจัยสเกลสำหรับแผนภูมิบับเบิล (อาจอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | กำหนดปัจจัยสเกลสำหรับแผนภูมิบับเบิล (อาจอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพายที่มีการแยกแบบกำหนดเอง. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getChart()](#getChart--) | คืนค่าแผนภูมิแม่. |
| [getSlide()](#getSlide--) | คืนค่าสไลด์แม่ของ FillFormat. |
| [getPresentation()](#getPresentation--) | คืนค่า presentation แม่ของ FillFormat. |

### getType() {#getType--}
```
public final int getType()
```

คืนค่าประเภทของกลุ่มชุดข้อมูลนี้. อ่านอย่างเดียว [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**คืนค่า:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public final boolean getPlotOnSecondAxis()
```

บ่งชี้ว่าชุดข้อมูลของกลุ่มนี้ถูกพล็อตบนแกนรองหรือไม่. อ่านอย่างเดียวแบบ boolean.

**คืนค่า:**
boolean

### getSeries() {#getSeries--}
```
public final IChartSeriesReadonlyCollection getSeries()
```

คืนค่าคอลเลกชันของชุดข้อมูล. อ่านอย่างเดียว [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**คืนค่า:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public final IChartSeries get_Item(int index)
```

ดึงเอาองค์ประกอบที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public final IUpDownBarsManager getUpDownBars()
```

ให้การเข้าถึงแถบขึ้น/ลงของแผนภูมิ Line หรือ Stock. อ่านอย่างเดียว [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**คืนค่า:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public final int getGapWidth()
```

กำหนดระยะห่างระหว่างกลุ่มแถบหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแถบหรือคอลัมน์. อ่าน/เขียน int.

**คืนค่า:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public final void setGapWidth(int value)
```

กำหนดระยะห่างระหว่างกลุ่มแถบหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างแถบหรือคอลัมน์. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public final int getGapDepth()
```

คืนค่าหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์ ระหว่างชุดข้อมูลในแผนภูมิ 3D. อ่าน/เขียน int.

**คืนค่า:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public final void setGapDepth(int value)
```

คืนค่าหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์ ระหว่างชุดข้อมูลในแผนภูมิ 3D. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public final int getFirstSliceAngle()
```

ดึงหรือกำหนดมุมของชิ้นแรกของแผนภูมิพายหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). อ่าน/เขียน int.

**คืนค่า:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public final void setFirstSliceAngle(int value)
```

ดึงหรือกำหนดมุมของชิ้นแรกของแผนภูมิพายหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาจากด้านบน, ตั้งแต่ 0 ถึง 360 องศา). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public final byte getDoughnutHoleSize()
```

กำหนดขนาดของรูในแผนภูมิโดนัท (อาจอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่การวาด). อ่าน/เขียน byte.

**คืนค่า:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public final void setDoughnutHoleSize(byte value)
```

กำหนดขนาดของรูในแผนภูมิโดนัท (อาจอยู่ระหว่าง 0 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่การวาด). อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getOverlap() {#getOverlap--}
```
public final byte getOverlap()
```

กำหนดบาร์และคอลัมน์ทับซ้อนกันบนแผนภูมิ 2 มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). -100%: ระยะห่างสูงสุด (บาร์แยกจากกันโดยสิ้นเชิง). 0%: บาร์จัดข้างกันโดยไม่มีการทับซ้อนหรือระยะห่าง. 100%: ทับซ้อนสูงสุด (บาร์ทับซ้อนกันทั้งหมด). คุณสมบัตินี้เป็นอ่าน/เขียน byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // ตั้งค่า overlap เป็น 55%
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

กำหนดบาร์และคอลัมน์ทับซ้อนกันบนแผนภูมิ 2 มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). -100%: ระยะห่างสูงสุด (บาร์แยกจากกันโดยสิ้นเชิง). 0%: บาร์จัดข้างกันโดยไม่มีการทับซ้อนหรือระยะห่าง. 100%: ทับซ้อนสูงสุด (บาร์ทับซ้อนกันทั้งหมด). คุณสมบัตินี้เป็นอ่าน/เขียน byte.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // ตั้งค่า overlap เป็น 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png", ImageFormat.Png);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public final int getSecondPieSize()
```

กำหนดขนาดของพายหรือแถบที่สองของแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพาย เป็นเปอร์เซ็นต์ของขนาดของพายแรก (อาจอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน/เขียน int.

**คืนค่า:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public final void setSecondPieSize(int value)
```

กำหนดขนาดของพายหรือแถบที่สองของแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพาย เป็นเปอร์เซ็นต์ของขนาดของพายแรก (อาจอยู่ระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public final int getBubbleSizeRepresentation()
```

กำหนดวิธีการแสดงค่าขนาดของฟองบนแผนภูมิบับเบิล. อ่าน/เขียน [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**คืนค่า:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public final void setBubbleSizeRepresentation(int value)
```

กำหนดวิธีการแสดงค่าขนาดของฟองบนแผนภูมิบับเบิล. อ่าน/เขียน [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public final double getPieSplitPosition()
```

กำหนดค่าที่ใช้เพื่อระบุว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพาย. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน double.

**คืนค่า:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public final void setPieSplitPosition(double value)
```

กำหนดค่าที่ใช้เพื่อระบุว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพาย. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public final int getPieSplitBy()
```

กำหนดวิธีการระบุว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพาย. อ่าน/เขียน [PieSplitType](../../com.aspose.slides/piesplittype).

**คืนค่า:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public final void setPieSplitBy(int value)
```

กำหนดวิธีการระบุว่าจุดข้อมูลใดอยู่ในพายหรือแถบที่สองบนแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพาย. อ่าน/เขียน [PieSplitType](../../com.aspose.slides/piesplittype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public final boolean isColorVaried()
```

กำหนดว่ามาร์คเกอร์ข้อมูลแต่ละจุดในชุดข้อมูลมีสีที่แตกต่างกัน. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public final void setColorVaried(boolean value)
```

กำหนดว่ามาร์คเกอร์ข้อมูลแต่ละจุดในชุดข้อมูลมีสีที่แตกต่างกัน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public final boolean hasSeriesLines()
```

เป็นจริงหากแผนภูมิมีเส้นชุดข้อมูล. ใช้กับแผนภูมิ stacked bar และ OfPie. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public final void setSeriesLines(boolean value)
```

เป็นจริงหากแผนภูมิมีเส้นชุดข้อมูล. ใช้กับแผนภูมิ stacked bar และ OfPie. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public final IChartLinesFormat getHiLowLinesFormat()
```

กำหนดรูปแบบ HiLowLines. HiLowLines ใช้กับประเภทแผนภูมิ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose.

**คืนค่า:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public final int getBubbleSizeScale()
```

กำหนดปัจจัยสเกลสำหรับแผนภูมิบับเบิล (อาจอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). อ่าน/เขียน int.

**คืนค่า:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public final void setBubbleSizeScale(int value)
```

กำหนดปัจจัยสเกลสำหรับแผนภูมิบับเบิล (อาจอยู่ระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public final IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพายที่มีการแยกแบบกำหนดเอง. มีจุดข้อมูลที่ควรวาดในพายหรือแถบที่สองในแผนภูมีพายของพายหรือแผนภูมิเบอร์ของพาย. อ่านอย่างเดียว [PieSplitCustomPointCollection](../../com.aspose.slides/piesplitcustompointcollection).

**คืนค่า:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

คืนค่า Parent_Immediate object. อ่านอย่างเดียว IDOMObject.

**คืนค่า:**
com.aspose.slides.IDOMObject

### getChart() {#getChart--}
```
public final IChart getChart()
```

คืนค่าแผนภูมิแม่. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart)

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนค่าสไลด์แม่ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**คืนค่า:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนค่า presentation แม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation)