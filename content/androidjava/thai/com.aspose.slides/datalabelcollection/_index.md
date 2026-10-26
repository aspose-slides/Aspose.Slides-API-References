---
title: DataLabelCollection
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของป้ายกำกับชุดข้อมูล.
type: docs
url: /th/com.aspose.slides/datalabelcollection/
---
**สืบทอด:**  
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)  
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

แสดงป้ายกำกับของชุดข้อมูล.  
## เมธอด

| Method | Description |
| --- | --- |
| [getChart()](#getChart--) | คืนแผนภูมิต้นแบบ. |
| [iterator()](#iterator--) | คืน enumerator ที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | คืน java iterator สำหรับคอลเลกชันทั้งหมด. |
| [isVisible()](#isVisible--) | ค่า false หมายถึงป้ายข้อมูลไม่แสดงเป็นค่าเริ่มต้น (และดังนั้นแฟล็ก Show*-ทั้งหมด (ShowValue, ...) ของ property DefaultDataLabelFormat จะเป็น false). |
| [hide()](#hide--) | ทำให้ป้ายข้อมูลซ่อนโดยค่าเริ่มต้นโดยตั้งค่าแฟล็ก Show*-ทั้งหมด (ShowValue, ...) ของ property DefaultDataLabelFormat ให้เป็น false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | รับจำนวนของป้ายข้อมูลที่มองเห็นได้ในคอลเลกชัน. |
| [getCount()](#getCount--) | รับจำนวนของป้ายข้อมูลทั้งหมดในคอลเลกชัน. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | รับรูปแบบป้ายข้อมูลเริ่มต้น. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | แสดงรูปแบบเส้นนำของป้ายข้อมูล. |
| [getParentSeries()](#getParentSeries--) | รับชุดข้อมูลพาเรนท์. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | คืนดัชนีของ DataLabel ที่ระบุในคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | รับป้ายข้อมูลสำหรับจุดข้อมูลที่มีดัชนีที่ระบุ. |
| [getSlide()](#getSlide--) | คืนสไลด์แม่ของ FillFormat. |
| [getPresentation()](#getPresentation--) | คืนการนำเสนอแม่ของ FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

คืนแผนภูมิต้นแบบ อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**ผลลัพธ์:**  
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

คืน enumerator ที่วนผ่านคอลเลกชัน.

**ผลลัพธ์:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

คืน java iterator สำหรับคอลเลกชันทั้งหมด.

**ผลลัพธ์:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

ค่า false หมายถึงป้ายข้อมูลไม่แสดงเป็นค่าเริ่มต้น (และดังนั้นแฟล็ก Show*-ทั้งหมด (ShowValue, ...) ของ property DefaultDataLabelFormat จะเป็น false). อ่านอย่างเดียว boolean.

--------------------

หากป้ายข้อมูลแสดงเป็นค่าเริ่มต้นคุณสามารถทำให้ซ่อนโดยค่าเริ่มต้นด้วยเมธอด Hide() แต่หากป้ายข้อมูลไม่แสดงเป็นค่าเริ่มต้น (IsVisible คือ false) คุณสามารถทำให้ป้ายข้อมูล "แสดงโดยค่าเริ่มต้น" ได้โดยตั้งค่าแฟล็ก Show*- (ShowValue, ...) ของ property DefaultDataLabelFormat ให้เป็น true

**ผลลัพธ์:**  
boolean
### hide() {#hide--}
```
public final void hide()
```

ทำให้ป้ายข้อมูลซ่อนโดยค่าเริ่มต้นโดยตั้งค่าแฟล็ก Show*-ทั้งหมด (ShowValue, ...) ของ property DefaultDataLabelFormat ให้เป็น false สถานะ. IsVisible จะเป็น false หลังจากนี้.

--------------------

หากป้ายข้อมูลไม่แสดงเป็นค่าเริ่มต้น (IsVisible คือ false) คุณสามารถทำให้ป้ายข้อมูล "แสดงโดยค่าเริ่มต้น" ได้โดยตั้งค่าแฟล็ก Show*- (ShowValue, ...) ของ property DefaultDataLabelFormat ให้เป็น true

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

รับจำนวนของป้ายข้อมูลที่มองเห็นได้ในคอลเลกชัน. อ่านอย่างเดียว int.

**ผลลัพธ์:**  
int
### getCount() {#getCount--}
```
public final int getCount()
```

รับจำนวนของป้ายข้อมูลทั้งหมดในคอลเลกชัน. อ่านอย่างเดียว int.

**ผลลัพธ์:**  
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

รับรูปแบบป้ายข้อมูลเริ่มต้น. อ่านอย่างเดียว [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**ผลลัพธ์:**  
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

แสดงรูปแบบเส้นนำของป้ายข้อมูล. อ่านอย่างเดียว [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      IChart chart = (IChart) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IChartSeriesCollection series = chart.getChartData().getSeries();
>      IDataLabelCollection labels = series.get_Item(0).getLabels();
>      labels.getLeaderLinesFormat().getLine().getFillFormat().setFillType(FillType.Solid);
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(Color.RED);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**  
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

รับชุดข้อมูลพาเรนท์. อ่านอย่างเดียว [IChartSeries](../../com.aspose.slides/ichartseries).

**ผลลัพธ์:**  
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

คืนดัชนีของ DataLabel ที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel เพื่อค้นหา. |

**ผลลัพธ์:**  
int - Index of a DataLabel or -1 if DataLabel not from this collection.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

รับป้ายข้อมูลสำหรับจุดข้อมูลที่มีดัชนีที่ระบุ.

--------------------

วิธีการเข้าถึงป้ายข้อมูลแบบอื่นคือ: - series.getDataPoints().get_Item(i).getLabel() - จัดการคุณสมบัติป้าย

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**  
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนสไลด์แม่ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**ผลลัพธ์:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนการนำเสนอแม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**ผลลัพธ์:**  
[IPresentation](../../com.aspose.slides/ipresentation)