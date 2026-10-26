---
title: DataLabelCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: แทนชุดป้ายกำกับของซีรีส์.
type: docs
url: /th/com.aspose.slides/datalabelcollection/
---
**การสืบทอด:**
java.lang.Object, com.aspose.slides.DomObject

**อินเทอร์เฟซที่ทำตามทั้งหมด:**
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

แทนชุดป้ายกำกับของซีรีส์.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getChart()](#getChart--) | ส่งคืนแผนภูมิแม่. |
| [iterator()](#iterator--) | ส่งคืนตัวนับที่วนผ่านคอลเลกชัน. |
| [iteratorJava()](#iteratorJava--) | ส่งคืนตัววนของ java สำหรับคอลเลกชันทั้งหมด. |
| [isVisible()](#isVisible--) | False หมายความว่าป้ายข้อมูลไม่แสดงตามค่าเริ่มต้น (and so all Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). |
| [hide()](#hide--) | ทำให้ป้ายข้อมูลซ่อนโดยค่าเริ่มต้นโดยตั้งค่าแฟล็ก Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat ให้เป็น false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | รับจำนวนป้ายข้อมูลที่มองเห็นได้ในคอลเลกชัน. |
| [getCount()](#getCount--) | รับจำนวนป้ายข้อมูลทั้งหมดในคอลเลกชัน. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | รับรูปแบบป้ายข้อมูลเริ่มต้น. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | แทนรูปแบบเส้นนำของป้ายข้อมูล. |
| [getParentSeries()](#getParentSeries--) | รับซีรีส์แม่. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | ส่งคืนดัชนีของ DataLabel ที่ระบุในคอลเลกชัน. |
| [get_Item(int index)](#get-Item-int-) | รับป้ายข้อมูลสำหรับจุดข้อมูลที่มีดัชนีที่ระบุ. |
| [getSlide()](#getSlide--) | ส่งคืนสไลด์แม่ของ FillFormat. |
| [getPresentation()](#getPresentation--) | ส่งคืนการนำเสนอแม่ของ FillFormat. |
### getChart() {#getChart--}
```
public final IChart getChart()
```

ส่งคืนแผนภูมิแม่. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**
[IChart](../../com.aspose.slides/ichart)
### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

ส่งคืนตัวนับที่วนผ่านคอลเลกชัน.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - IGenericEnumerator ที่สามารถใช้เพื่อวนผ่านคอลเลกชัน.
### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

ส่งคืนตัววนของ java สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - java.util.Iterator สำหรับคอลเลกชันทั้งหมด.
### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

False หมายความว่าป้ายข้อมูลไม่แสดงตามค่าเริ่มต้น (and so all Show*-flags (ShowValue, ...) of the DefaultDataLabelFormat property are false). อ่านอย่างเดียว boolean.

--------------------

หากป้ายข้อมูลแสดงตามค่าเริ่มต้น คุณสามารถทำให้ซ่อนตามค่าเริ่มต้นด้วยเมธอด Hide() ได้ แต่หากป้ายข้อมูลไม่แสดงตามค่าเริ่มต้น (IsVisible มีค่า false) คุณสามารถทำให้ป้ายข้อมูล "แสดงตามค่าเริ่มต้น" ได้โดยตั้งค่าแฟล็ก Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat ให้เป็น true

**คืนค่า:**
boolean
### hide() {#hide--}
```
public final void hide()
```

ทำให้ป้ายข้อมูลซ่อนตามค่าเริ่มต้นโดยตั้งค่าแฟล็ก Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat ให้เป็น false. IsVisible จะเป็น false หลังจากนี้.

--------------------

หากป้ายข้อมูลไม่แสดงตามค่าเริ่มต้น (IsVisible มีค่า false) คุณสามารถทำให้ป้ายข้อมูล "แสดงตามค่าเริ่มต้น" ได้โดยตั้งค่าแฟล็ก Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat ให้เป็น true

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

รับจำนวนป้ายข้อมูลที่มองเห็นได้ในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int
### getCount() {#getCount--}
```
public final int getCount()
```

รับจำนวนป้ายข้อมูลทั้งหมดในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**
int
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

รับรูปแบบป้ายข้อมูลเริ่มต้น. อ่านอย่างเดียว [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**คืนค่า:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

แทนรูปแบบเส้นนำของป้ายข้อมูล. อ่านอย่างเดียว [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
>      labels.getLeaderLinesFormat().getLine().getFillFormat().getSolidFillColor().setColor(new java.awt.Color(255, 0, 0, 255));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### getParentSeries() {#getParentSeries--}
```
public final IChartSeries getParentSeries()
```

รับซีรีส์แม่. อ่านอย่างเดียว [IChartSeries](../../com.aspose.slides/ichartseries).

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

ส่งคืนดัชนีของ DataLabel ที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel ที่ต้องการค้นหา. |

**คืนค่า:**
int - ดัชนีของ DataLabel หรือ -1 หาก DataLabel ไม่อยู่ในคอลเลกชันนี้.
### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

รับป้ายข้อมูลสำหรับจุดข้อมูลที่มีดัชนีที่ระบุ.

--------------------

วิธีการเข้าถึงป้ายข้อมูลแบบสลับคือ: - series.getDataPoints().get_Item(i).getLabel() - จัดการคุณสมบัติป้าย.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

ส่งคืนสไลด์แม่ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**คืนค่า:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ส่งคืนการนำเสนอแม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**
[IPresentation](../../com.aspose.slides/ipresentation)