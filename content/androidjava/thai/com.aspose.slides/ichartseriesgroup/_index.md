---
title: IChartSeriesGroup
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงกลุ่มของซีรีส์.
type: docs
url: /th/com.aspose.slides/ichartseriesgroup/
---
**อินเทอร์เฟซที่ดำเนินการทั้งหมด:**
[com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IChartSeriesGroup extends IChartComponent
```

แสดงถึงกลุ่มของซีรีส์.

--------------------

1) ดูสรุปและหมายเหตุสำหรับคลาส ChartSeriesGroupCollection และ enum CombinableSeriesTypesGroup. 2) กลุ่มของซีรีส์ประกอบด้วยคุณสมบัติของซีรีส์บางอย่างที่เป็นสากลสำหรับแต่ละซีรีส์ในกลุ่ม ("series group properties"). "Series group properties" ในคลาส ChartSeriesGroup เป็นอ่าน/เขียน. แต่ละ "series group properties" สามารถมีการฉายเป็นอ่านอย่างเดียวในคลาส ChartSeries.

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getType()](#getType--) | Returns a type of this series group. |
| [getPlotOnSecondAxis()](#getPlotOnSecondAxis--) | Indicates if series of this group is plotted on secondary axis. |
| [getSeries()](#getSeries--) | Returns a readonly collection of chart series. |
| [get_Item(int index)](#get-Item-int-) | Gets the element at the specified index. |
| [getUpDownBars()](#getUpDownBars--) | Provede access to up/down bars of Line- or Stock-chart. |
| [getGapWidth()](#getGapWidth--) | Specifies the space between bar or column clusters, as a percentage of the bar or column width. |
| [setGapWidth(int value)](#setGapWidth-int-) | Specifies the space between bar or column clusters, as a percentage of the bar or column width. |
| [getGapDepth()](#getGapDepth--) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. |
| [setGapDepth(int value)](#setGapDepth-int-) | Returns or sets the distance, as a percentage of the marker width, between the data series in a 3D chart. |
| [getFirstSliceAngle()](#getFirstSliceAngle--) | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). |
| [setFirstSliceAngle(int value)](#setFirstSliceAngle-int-) | Gets or sets the angle of the first pie or doughnut chart slice, in degrees (clockwise from up, from 0 to 360 degrees). |
| [isColorVaried()](#isColorVaried--) | Specifies that each data marker in the series has a different color. |
| [setColorVaried(boolean value)](#setColorVaried-boolean-) | Specifies that each data marker in the series has a different color. |
| [hasSeriesLines()](#hasSeriesLines--) | True if chart has series lines. |
| [setSeriesLines(boolean value)](#setSeriesLines-boolean-) | True if chart has series lines. |
| [getOverlap()](#getOverlap--) | Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%). |
| [setOverlap(byte value)](#setOverlap-byte-) | Specifies how much bars and columns shall overlap on 2-D charts, as a percentage (from -100% to 100%). |
| [getSecondPieSize()](#getSecondPieSize--) | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). |
| [setSecondPieSize(int value)](#setSecondPieSize-int-) | Specifies the size of the second pie or bar of a pie-of-pie chart or a bar-of-pie chart, as a percentage of the size of the first pie (can be between 5 and 200 percents). |
| [getPieSplitPosition()](#getPieSplitPosition--) | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [setPieSplitPosition(double value)](#setPieSplitPosition-double-) | Specifies a value that shall be used to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [getPieSplitBy()](#getPieSplitBy--) | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [setPieSplitBy(int value)](#setPieSplitBy-int-) | Specifies how to determine which data points are in the second pie or bar on a pie-of-pie or bar-of-pie chart. |
| [getPieSplitCustomPoints()](#getPieSplitCustomPoints--) | The custom split information for a pie-of-pie or bar-of-pie chart with a custom split. |
| [getDoughnutHoleSize()](#getDoughnutHoleSize--) | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). |
| [setDoughnutHoleSize(byte value)](#setDoughnutHoleSize-byte-) | Specifies the size of the hole in a doughnut chart (can be between 10 and 90 percents of the size of the plot area.). |
| [getBubbleSizeScale()](#getBubbleSizeScale--) | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). |
| [setBubbleSizeScale(int value)](#setBubbleSizeScale-int-) | Specifies the scale factor for the bubble chart (can be between 0 and 300 percents of the default size). |
| [getHiLowLinesFormat()](#getHiLowLinesFormat--) | Specifies HiLowLines format. |
| [getBubbleSizeRepresentation()](#getBubbleSizeRepresentation--) | Specifies how the bubble size values are represented on the bubble chart. |
| [setBubbleSizeRepresentation(int value)](#setBubbleSizeRepresentation-int-) | Specifies how the bubble size values are represented on the bubble chart. |

### getType() {#getType--}
```
public abstract int getType()
```

คืนค่าชนิดของกลุ่มซีรีส์นี้. อ่านอย่างเดียว [CombinableSeriesTypesGroup](../../com.aspose.slides/combinableseriestypesgroup).

**คืนค่า:**
int

### getPlotOnSecondAxis() {#getPlotOnSecondAxis--}
```
public abstract boolean getPlotOnSecondAxis()
```

แสดงว่าซีรีส์ของกลุ่มนี้ถูกพล็อตบนแกนที่สองหรือไม่. อ่านอย่างเดียว boolean.

**คืนค่า:**
boolean

### getSeries() {#getSeries--}
```
public abstract IChartSeriesReadonlyCollection getSeries()
```

คืนค่าการรวบรวมที่อ่านอย่างเดียวของซีรีส์แผนภูมิ. อ่านอย่างเดียว [IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection).

**คืนค่า:**
[IChartSeriesReadonlyCollection](../../com.aspose.slides/ichartseriesreadonlycollection)

### get_Item(int index) {#get-Item-int-}
```
public abstract IChartSeries get_Item(int index)
```

ดึงเอาอิลิเมนต์ที่ตำแหน่ง index ที่ระบุ.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries)

### getUpDownBars() {#getUpDownBars--}
```
public abstract IUpDownBarsManager getUpDownBars()
```

ให้การเข้าถึงบาร์ขึ้น/ลงของแผนภูมิ Line หรือ Stock. อ่านอย่างเดียว [IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager).

**คืนค่า:**
[IUpDownBarsManager](../../com.aspose.slides/iupdownbarsmanager)

### getGapWidth() {#getGapWidth--}
```
public abstract int getGapWidth()
```

ระบุช่องว่างระหว่างกลุ่มบาร์หรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างบาร์หรือคอลัมน์. อ่าน/เขียน int.

**คืนค่า:**
int

### setGapWidth(int value) {#setGapWidth-int-}
```
public abstract void setGapWidth(int value)
```

ระบุช่องว่างระหว่างกลุ่มบาร์หรือคอลัมน์เป็นเปอร์เซ็นต์ของความกว้างบาร์หรือคอลัมน์. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getGapDepth() {#getGapDepth--}
```
public abstract int getGapDepth()
```

คืนค่าหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์ระหว่างซีรีส์ข้อมูลในแผนภูมิ 3D. อ่าน/เขียน int.

**คืนค่า:**
int

### setGapDepth(int value) {#setGapDepth-int-}
```
public abstract void setGapDepth(int value)
```

คืนค่าหรือกำหนดระยะห่างเป็นเปอร์เซ็นต์ของความกว้างมาร์คเกอร์ระหว่างซีรีส์ข้อมูลในแผนภูมิ 3D. อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getFirstSliceAngle() {#getFirstSliceAngle--}
```
public abstract int getFirstSliceAngle()
```

ดึงหรือกำหนดมุมของชิ้นแรกของแผนภูมิเพียวหรือดอนัท, หน่วยองศา (ตามเข็มนาฬิกาตั้งจากบน, 0 ถึง 360 องศา). อ่าน/เขียน int.

**คืนค่า:**
int

### setFirstSliceAngle(int value) {#setFirstSliceAngle-int-}
```
public abstract void setFirstSliceAngle(int value)
```

ดึงหรือกำหนดมุมของชิ้นแรกของแผนภูมิเพียวหรือดอนัท, หน่วยองศา (ตามเข็มนาฬิกาตั้งจากบน, 0 ถึง 360 องศา). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### isColorVaried() {#isColorVaried--}
```
public abstract boolean isColorVaried()
```

ระบุว่าตัวทำเครื่องหมายข้อมูลแต่ละตัวในซีรีส์มีสีที่แตกต่างกัน. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setColorVaried(boolean value) {#setColorVaried-boolean-}
```
public abstract void setColorVaried(boolean value)
```

ระบุว่าตัวทำเครื่องหมายข้อมูลแต่ละตัวในซีรีส์มีสีที่แตกต่างกัน. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### hasSeriesLines() {#hasSeriesLines--}
```
public abstract boolean hasSeriesLines()
```

จริงหากแผนภูมิมีเส้นซีรีส์. ใช้กับแผนภูมิแท่งซ้อนและ OfPie. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setSeriesLines(boolean value) {#setSeriesLines-boolean-}
```
public abstract void setSeriesLines(boolean value)
```

จริงหากแผนภูมิมีเส้นซีรีส์. ใช้กับแผนภูมิแท่งซ้อนและ OfPie. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getOverlap() {#getOverlap--}
```
public abstract byte getOverlap()
```

ระบุว่าบาร์และคอลัมน์ควรทับซ้อนกันเท่าใดในแผนภูมิ 2-D เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). - -100%: ระยะห่างสูงสุด (บาร์แยกจากกันอย่างสมบูรณ์). - 0%: บาร์วางเคียงกันโดยไม่มีการทับหรือช่องว่าง. - 100%: การทับสูงสุด (บาร์ทับกันทั้งหมด). รายการนี้เป็นคุณสมบัติอ่าน/เขียนแบบ byte.

**คืนค่า:**
byte

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

**คืนค่า:**
byte

### setOverlap(byte value) {#setOverlap-byte-}
```
public abstract void setOverlap(byte value)
```

ระบุว่าบาร์และคอลัมน์ควรทับซ้อนกันเท่าใดในแผนภูมิ 2-D เป็นเปอร์เซ็นต์ (จาก -100% ถึง 100%). - -100%: ระยะห่างสูงสุด (บาร์แยกจากกันอย่างสมบูรณ์). - 0%: บาร์วางเคียงกันโดยไม่มีการทับหรือช่องว่าง. - 100%: การทับสูงสุด (บาร์ทับกันทั้งหมด). รายการนี้เป็นคุณสมบัติอ่าน/เขียนแบบ byte.

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
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getSecondPieSize() {#getSecondPieSize--}
```
public abstract int getSecondPieSize()
```

ระบุขนาดของพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของพายแรก (ค่าระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน/เขียน int.

**คืนค่า:**
int

### setSecondPieSize(int value) {#setSecondPieSize-int-}
```
public abstract void setSecondPieSize(int value)
```

ระบุขนาดของพายหรือบาร์ที่สองของแผนภูมิ pie-of-pie หรือ bar-of-pie เป็นเปอร์เซ็นต์ของขนาดของพายแรก (ค่าระหว่าง 5 ถึง 200 เปอร์เซ็นต์). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPieSplitPosition() {#getPieSplitPosition--}
```
public abstract double getPieSplitPosition()
```

ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน double.

**คืนค่า:**
double

### setPieSplitPosition(double value) {#setPieSplitPosition-double-}
```
public abstract void setPieSplitPosition(double value)
```

ระบุค่าที่จะใช้กำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. ใช้ร่วมกับคุณสมบัติ PieSplitBy. อ่าน/เขียน double.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | double |  |

### getPieSplitBy() {#getPieSplitBy--}
```
public abstract int getPieSplitBy()
```

ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [PieSplitType](../../com.aspose.slides/piesplittype).

**คืนค่า:**
int

### setPieSplitBy(int value) {#setPieSplitBy-int-}
```
public abstract void setPieSplitBy(int value)
```

ระบุวิธีการกำหนดว่าจุดข้อมูลใดอยู่ในพายหรือบาร์ที่สองบนแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่าน/เขียน [PieSplitType](../../com.aspose.slides/piesplittype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getPieSplitCustomPoints() {#getPieSplitCustomPoints--}
```
public abstract IPieSplitCustomPointCollection getPieSplitCustomPoints()
```

ข้อมูลการแยกแบบกำหนดเองสำหรับแผนภูมิ pie-of-pie หรือ bar-of-pie ที่มีการแยกแบบกำหนดเอง. มีจุดข้อมูลที่ต้องวาดในพายหรือบาร์ที่สองในแผนภูมิ pie-of-pie หรือ bar-of-pie. อ่านอย่างเดียว [IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection).

**คืนค่า:**
[IPieSplitCustomPointCollection](../../com.aspose.slides/ipiesplitcustompointcollection)

### getDoughnutHoleSize() {#getDoughnutHoleSize--}
```
public abstract byte getDoughnutHoleSize()
```

ระบุขนาดของรูในแผนภูมิดอนัท (ค่าระหว่าง 10 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่วาด). อ่าน/เขียน byte.

**คืนค่า:**
byte

### setDoughnutHoleSize(byte value) {#setDoughnutHoleSize-byte-}
```
public abstract void setDoughnutHoleSize(byte value)
```

ระบุขนาดของรูในแผนภูมิดอนัท (ค่าระหว่าง 10 ถึง 90 เปอร์เซ็นต์ของขนาดพื้นที่วาด). อ่าน/เขียน byte.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getBubbleSizeScale() {#getBubbleSizeScale--}
```
public abstract int getBubbleSizeScale()
```

ระบุตัวคูณสเกลสำหรับแผนภูมิฟอง (ค่าระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). อ่าน/เขียน int.

**คืนค่า:**
int

### setBubbleSizeScale(int value) {#setBubbleSizeScale-int-}
```
public abstract void setBubbleSizeScale(int value)
```

ระบุตัวคูณสเกลสำหรับแผนภูมิฟอง (ค่าระหว่าง 0 ถึง 300 เปอร์เซ็นต์ของขนาดเริ่มต้น). อ่าน/เขียน int.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getHiLowLinesFormat() {#getHiLowLinesFormat--}
```
public abstract IChartLinesFormat getHiLowLinesFormat()
```

ระบุรูปแบบ HiLowLines. HiLowLines ใช้กับประเภทแผนภูมิ HiLowClose, OpenHiLowClose, VolumeHiLowClose และ VolumeOpenHiLowClose.

**คืนค่า:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)

### getBubbleSizeRepresentation() {#getBubbleSizeRepresentation--}
```
public abstract int getBubbleSizeRepresentation()
```

ระบุวิธีการแสดงค่าขนาดฟองบนแผนภูมิฟอง. อ่าน/เขียน [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**คืนค่า:**
int

### setBubbleSizeRepresentation(int value) {#setBubbleSizeRepresentation-int-}
```
public abstract void setBubbleSizeRepresentation(int value)
```

ระบุวิธีการแสดงค่าขนาดฟองบนแผนภูมิฟอง. อ่าน/เขียน [BubbleSizeRepresentationType](../../com.aspose.slides/bubblesizerepresentationtype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |