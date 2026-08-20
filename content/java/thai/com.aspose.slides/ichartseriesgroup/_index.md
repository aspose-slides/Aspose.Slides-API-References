---
title: IChartSeriesGroup
second_title: Aspose.Slides สำหรับ Java API Reference
description: แสดงถึงกลุ่มของซีรีส์.
type: docs
url: /th/com.aspose.slides/ichartseriesgroup/
---
**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

แสดงถึงกลุ่มของซีรีส์

--------------------

1) ดูสรุปและบันทึกย่อสำหรับคลาส ChartSeriesGroupCollection และ enum CombinableSeriesTypesGroup. 2) กลุ่มของซีรีส์มีคุณสมบัติบางอย่างที่เป็นร่วมกันสำหรับแต่ละซีรีส์ในกลุ่ม (“คุณสมบัติของกลุ่มซีรีส์”). “คุณสมบัติของกลุ่มซีรีส์” ในคลาส ChartSeriesGroup เป็นแบบอ่าน/เขียน. แต่ละ “คุณสมบัติของกลุ่มซีรีส์” สามารถมีการฉายเป็นแบบอ่านอย่างเดียวในคลาส ChartSeries
## เมธอด

| Method | Description |
| --- | --- |
| [getType()](#getType--) | คืนค่าชนิดของกลุ่มซีรีส์นี้. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | ระบุว่าซีรีส์ของกลุ่มนี้ถูกพล็อตบนแกนรองหรือไม่. |
| [getSeries()](#getSeries--) | คืนค่าคอลเลกชันแบบอ่านอย่างเดียวของซีรีส์ชาร์ต. |
| [get_Item(int index)](#get-Item-int-) | รับเอาองค์ประกอบที่ตำแหน่งที่ระบุ. |
| [getUpDownBars()](#getUpDownBars--) | ให้การเข้าถึงแถบ up/down ของแผนภูมิ Line หรือ Stock. |
| [getGapWidth()](#getGapWidth--) | กำหนดระยะห่างระหว่างคลัสเตอร์ของแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างของแท่งหรือคอลัมน์. |
| [setGapWidth(int value)](#setGapWidth-int-) | กำหนดระยะห่างระหว่างคลัสเตอร์ของแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างของแท่งหรือคอลัมน์. |
| [getGapDepth()](#getGapDepth--) | คืนค่าหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างมาร์กเกอร์ระหว่างซีรีส์ข้อมูลในแผนภูมิ 3 มิติ. |
| [setGapDepth(int value)](#setGapDepth-int-) | คืนค่าหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างมาร์กเกอร์ระหว่างซีรีส์ข้อมูลในแผนภูมิ 3 มิติ. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | รับหรือกำหนดมุมของชิ้นแรกของแผนภูมิวงกลมหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาจากตำแหน่งบน, ตั้งแต่ 0 ถึง 360 องศา). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | รับหรือกำหนดมุมของชิ้นแรกของแผนภูมิวงกลมหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาจากตำแหน่งบน, ตั้งแต่ 0 ถึง 360 องศา). |
| [isColorVaried()](#isColorVaried--) | กำหนดว่ามาร์คเกอร์ข้อมูลแต่ละตัวในซีรีส์มีสีที่แตกต่างกัน. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | กำหนดว่ามาร์คเกอร์ข้อมูลแต่ละตัวในซีรีส์มีสีที่แตกต่างกัน. |
| [hasSeriesLines()](#hasSeriesLines--) | จริงหากแผนภูมิมีเส้นซีรีส์. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | จริงหากแผนภูมิมีเส้นซีรีส์. |
| [getOverlap()](#getOverlap--) | กำหนดว่าจะแท่งและคอลัมน์ทับกันเท่าใดในแผนภูมิ 2-มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | กำหนดว่าจะแท่งและคอลัมน์ทับกันเท่าใดในแผนภูมิ 2-มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | กำหนดขนาดของวงกลมหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของวงกลมแรก (ตั้งแต่ 5% ถึง 200%). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | กำหนดขนาดของวงกลมหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของวงกลมแรก (ตั้งแต่ 5% ถึง 200%). |
| [getPieSplitPosition()](#getPieSplitPosition--) | กำหนดค่าที่จะใช้เพื่อระบุว่าจุดข้อมูลใดอยู่ในวงกลมหรือแท่งที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | กำหนดค่าที่จะใช้เพื่อระบุว่าจุดข้อมูลใดอยู่ในวงกลมหรือแท่งที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [getPieSplitBy()](#getPieSplitBy--) | กำหนดวิธีการระบุว่าจุดข้อมูลใดอยู่ในวงกลมหรือแท่งที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | กำหนดวิธีการระบุว่าจุดข้อมูลใดอยู่ในวงกลมหรือแท่งที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | กำหนดขนาดของรูในแผนภูมิโดนัท (ตั้งแต่ 10% ถึง 90% ของขนาดพื้นที่พล็อต). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | กำหนดขนาดของรูในแผนภูมิโดนัท (ตั้งแต่ 10% ถึง 90% ของขนาดพื้นที่พล็อต). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | กำหนดอัตราส่วนการปรับขนาดสำหรับแผนภูมิบับเบิล (ตั้งแต่ 0% ถึง 300% ของขนาดเริ่มต้น). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | กำหนดอัตราส่วนการปรับขนาดสำหรับแผนภูมิบับเบิล (ตั้งแต่ 0% ถึง 300% ของขนาดเริ่มต้น). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | กำหนดรูปแบบ HiLowLines. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | กำหนดวิธีการแสดงค่าขนาดบับเบิลบนแผนภูมิบับเบิล. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | กำหนดวิธีการแสดงค่าขนาดบับเบิลบนแผนภูมิบับเบิล. |

### getType() {#getType--}
```
public abstract int getType()
```

คืนค่าชนิดของกลุ่มซีรีส์นี้. อ่านอย่างเดียว [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**ผลลัพธ์:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

ระบุว่าซีรีส์ของกลุ่มนี้ถูกพล็อตบนแกนรองหรือไม่. บูลีนอ่านอย่างเดียว.

**ผลลัพธ์:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

คืนค่าคอลเลกชันแบบอ่านอย่างเดียวของซีรีส์ชาร์ต. อ่านอย่างเดียว [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**ผลลัพธ์:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

รับเอาองค์ประกอบที่ตำแหน่งที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

ให้การเข้าถึงแถบ up/down ของแผนภูมิ Line หรือ Stock. อ่านอย่างเดียว [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**ผลลัพธ์:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

กำหนดระยะห่างระหว่างคลัสเตอร์ของแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างของแท่งหรือคอลัมน์. อ่าน/เขียน int.

**ผลลัพธ์:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

กำหนดระยะห่างระหว่างคลัสเตอร์ของแท่งหรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างของแท่งหรือคอลัมน์. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

คืนค่าหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างมาร์กเกอร์ระหว่างซีรีส์ข้อมูลในแผนภูมิ 3 มิติ. อ่าน/เขียน int.

**ผลลัพธ์:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

คืนค่าหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างมาร์กเกอร์ระหว่างซีรีส์ข้อมูลในแผนภูมิ 3 มิติ. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

รับหรือกำหนดมุมของชิ้นแรกของแผนภูมิวงกลมหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาจากตำแหน่งบน, ตั้งแต่ 0 ถึง 360 องศา). อ่าน/เขียน int.

**ผลลัพธ์:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

รับหรือกำหนดมุมของชิ้นแรกของแผนภูมิวงกลมหรือโดนัทเป็นองศา (ตามเข็มนาฬิกาจากตำแหน่งบน, ตั้งแต่ 0 ถึง 360 องศา). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

กำหนดว่ามาร์คเกอร์ข้อมูลแต่ละตัวในซีรีส์มีสีที่แตกต่างกัน. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

กำหนดว่ามาร์คเกอร์ข้อมูลแต่ละตัวในซีรีส์มีสีที่แตกต่างกัน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

จริงหากแผนภูมิมีเส้นซีรีส์. ใช้กับแผนภูมิกองแท่งและ OfPie. อ่าน/เขียน boolean.

**ผลลัพธ์:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

จริงหากแผนภูมิมีเส้นซีรีส์. ใช้กับแผนภูมิกองแท่งและ OfPie. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

กำหนดว่าจะแท่งและคอลัมน์ทับกันเท่าใดในแผนภูมิ 2-มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). - -100%: ระยะห่างสูงสุด (แท่งแยกจากกันอย่างสมบูรณ์). - 0%: แท่งวางเคียงกันโดยไม่มีการทับหรือระยะห่าง. - 100%: การทับสูงสุด (แท่งทับกันทั้งหมด). คุณสมบัตินี้เป็น byte แบบอ่าน/เขียน.

--------------------

> ```
> The following example demonstrates how to set the overlap for a chart series group 
>   and render the resulting chart on a form:
>   
>  Presentation pres = new Presentation();
>  try {
>      IChart chart = pres.getSlides().get_Item(0).getShapes().addChart(ChartType.ClusteredColumn, 10, 10, 600, 300);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      series.get_Item(0).getParentSeriesGroup().setOverlap((byte)55); // Set overlap to 55%
>      pres.getSlides().get_Item(0).getImage(1, 1).save("chart.png");
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

กำหนดว่าจะแท่งและคอลัมน์ทับกันเท่าใดในแผนภูมิ 2-มิติเป็นเปอร์เซ็นต์ (ตั้งแต่ -100% ถึง 100%). - -100%: ระยะห่างสูงสุด (แท่งแยกจากกันอย่างสมบูรณ์). - 0%: แท่งวางเคียงกันโดยไม่มีการทับหรือระยะห่าง. - 100%: การทับสูงสุด (แท่งทับกันทั้งหมด). คุณสมบัตินี้เป็น byte แบบอ่าน/เขียน.

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
public abstract int getSecondPieSize()
```

กำหนดขนาดของวงกลมหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของวงกลมแรก (ตั้งแต่ 5% ถึง 200%). อ่าน/เขียน int.

**ผลลัพธ์:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

กำหนดขนาดของวงกลมหรือแท่งที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของวงกลมแรก (ตั้งแต่ 5% ถึง 200%). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

กำหนดค่าที่จะใช้เพื่อระบุว่าจุดข้อมูลใดอยู่ในวงกลมหรือแท่งที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน double.

**ผลลัพธ์:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

กำหนดค่าที่จะใช้เพื่อระบุว่าจุดข้อมูลใดอยู่ในวงกลมหรือแท่งที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

กำหนดวิธีการระบุว่าจุดข้อมูลใดอยู่ในวงกลมหรือแท่งที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [PieSplitType](../../com.aspose.slides/piesplittype).

**ผลลัพธ์:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

กำหนดวิธีการระบุว่าจุดข้อมูลใดอยู่ในวงกลมหรือแท่งที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [PieSplitType](../../com.aspose.slides/piesplittype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. มีจุดข้อมูลที่ควรวาดในวงกลมหรือแท่งที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่านอย่างเดียว [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**ผลลัพธ์:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

กำหนดขนาดของรูในแผนภูมิโดนัท (ตั้งแต่ 10% ถึง 90% ของขนาดพื้นที่พล็อต). อ่าน/เขียน byte.

**ผลลัพธ์:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

กำหนดขนาดของรูในแผนภูมิโดนัท (ตั้งแต่ 10% ถึง 90% ของขนาดพื้นที่พล็อต). อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

กำหนดอัตราส่วนการปรับขนาดสำหรับแผนภูมิบับเบิล (ตั้งแต่ 0% ถึง 300% ของขนาดเริ่มต้น). อ่าน/เขียน int.

**ผลลัพธ์:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

กำหนดอัตราส่วนการปรับขนาดสำหรับแผนภูมิบับเบิล (ตั้งแต่ 0% ถึง 300% ของขนาดเริ่มต้น). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

กำหนดรูปแบบ HiLowLines. HiLowLines ใช้กับประเภทแผนภูมิ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose.

**ผลลัพธ์:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

กำหนดวิธีการแสดงค่าขนาดบับเบิลบนแผนภูมิบับเบิล. อ่าน/เขียน [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**ผลลัพธ์:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

กำหนดวิธีการแสดงค่าขนาดบับเบิลบนแผนภูมิบับเบิล. อ่าน/เขียน [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |