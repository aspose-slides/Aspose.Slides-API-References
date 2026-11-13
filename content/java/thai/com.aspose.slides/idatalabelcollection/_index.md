---
title: IDataLabelCollection
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงฉลากของชุดข้อมูล.
type: docs
url: /th/com.aspose.slides/idatalabelcollection/
---
**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

แสดงฉลากของชุดข้อมูล.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | ดึงฉลากข้อมูลสำหรับจุดข้อมูลที่มีดัชนีที่ระบุ |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | ส่งคืนรูปแบบเริ่มต้นของฉลากข้อมูลทั้งหมดในคอลเลกชัน |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | แสดงรูปแบบเส้นนำของฉลากข้อมูล |
| [isVisible()](#isVisible--) | False หมายความว่าฉลากข้อมูลไม่แสดงโดยค่าเริ่มต้น (และดังนั้น Show*-flags ทั้งหมด (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat จะเป็นค่า false) |
| [hide()](#hide--) | ทำให้ฉลากข้อมูลซ่อนโดยค่าเริ่มต้นโดยตั้งค่า Show*-flags ทั้งหมด (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat เป็นสถานะ false |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | ดึงจำนวนของฉลากข้อมูลที่มองเห็นได้ในคอลเลกชัน |
| [getCount()](#getCount--) | ดึงจำนวนของฉลากข้อมูลทั้งหมดในคอลเลกชัน |
| [getParentSeries()](#getParentSeries--) | ส่งคืนซีรีส์แผนภูมิแม่ |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | ส่งคืนดัชนีของ DataLabel ที่ระบุในคอลเลกชัน |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | ดึงหรือกำหนดประเภทรูปแบบเริ่มต้นสำหรับฉลากข้อมูล |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | ดึงหรือกำหนดประเภทรูปแบบเริ่มต้นสำหรับฉลากข้อมูล |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

ดึงฉลากข้อมูลสำหรับจุดข้อมูลที่มีดัชนีที่ระบุ

--------------------

วิธีการอื่นในการเข้าถึงฉลากข้อมูลคือ: - getSeries().getDataPoints().get_Item(i).getLabel() - จัดการคุณสมบัติของฉลาก

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ค่าที่ส่งคืน:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

ส่งคืนรูปแบบเริ่มต้นของฉลากข้อมูลทั้งหมดในคอลเลกชัน นับว่าอ่านอย่างเดียว [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**ค่าที่ส่งคืน:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

แสดงรูปแบบเส้นนำของฉลากข้อมูล นับว่าอ่านอย่างเดียว [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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


**ค่าที่ส่งคืน:**
[IChartLinesFormat](../../com.aspose.slides/ichartlinesformat)
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False หมายความว่าฉลากข้อมูลไม่แสดงโดยค่าเริ่มต้น (และดังนั้น Show*-flags ทั้งหมด (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat จะเป็นค่า false) นับว่าอ่านอย่างเดียว  boolean .

--------------------

หากฉลากข้อมูลแสดงโดยค่าเริ่มต้นคุณสามารถทำให้ซ่อนโดยค่าเริ่มต้นด้วยเมธอด Hide()  แต่หากฉลากข้อมูลไม่แสดงโดยค่าเริ่มต้น (IsVisible เป็น false) คุณสามารถทำให้ฉลากข้อมูล "แสดงโดยค่าเริ่มต้น" โดยตั้งค่า Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat เป็นสถานะ true

**ค่าที่ส่งคืน:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

ทำให้ฉลากข้อมูลซ่อนโดยค่าเริ่มต้นโดยตั้งค่า Show*-flags ทั้งหมด (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat เป็นสถานะ false  IsVisible จะเป็น false หลังจากนี้.

--------------------

หากฉลากข้อมูลไม่แสดงโดยค่าเริ่มต้น (IsVisible เป็น false) คุณสามารถทำให้ฉลากข้อมูล "แสดงโดยค่าเริ่มต้น" โดยตั้งค่า Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat เป็นสถานะ true

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

ดึงจำนวนของฉลากข้อมูลที่มองเห็นได้ในคอลเลกชัน นับว่าอ่านอย่างเดียว  int .

**ค่าที่ส่งคืน:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

ดึงจำนวนของฉลากข้อมูลทั้งหมดในคอลเลกชัน นับว่าอ่านอย่างเดียว  int .

**ค่าที่ส่งคืน:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

ส่งคืนซีรีส์แผนภูมิแม่ นับว่าอ่านอย่างเดียว [IChartSeries](../../com.aspose.slides/ichartseries).

**ค่าที่ส่งคืน:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

ส่งคืนดัชนีของ DataLabel ที่ระบุในคอลเลกชัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel ที่ต้องการหา. |

**ค่าที่ส่งคืน:**
int - ดัชนีของ DataLabel หรือ -1 หาก DataLabel ไม่อยู่ในคอลเลกชันนี้.
### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public abstract int getDefaultLabelShapeType()
```

ดึงหรือกำหนดประเภทรูปแบบเริ่มต้นสำหรับฉลากข้อมูล หากไม่มีรูปแบบจะส่งคืน [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // กำหนดประเภทรูปร่างของฉลากข้อมูลทั้งหมดในซีรีส์แรกเป็น Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

การตั้งค่าคุณสมบัตินี้ยังทำให้คุณสมบัติ IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) ของฉลากข้อมูลทั้งหมดในคอลเลกชันเป็นค่าเดียวกัน

**ค่าที่ส่งคืน:**
int
### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public abstract void setDefaultLabelShapeType(int value)
```

ดึงหรือกำหนดประเภทรูปแบบเริ่มต้นสำหรับฉลากข้อมูล หากไม่มีรูปแบบจะส่งคืน [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined).

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // กำหนดประเภทรูปร่างของฉลากข้อมูลทั้งหมดในซีรีส์แรกเป็น Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

การตั้งค่าคุณสมบัตินี้ยังทำให้คุณสมบัติ IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) ของฉลากข้อมูลทั้งหมดในคอลเลกชันเป็นค่าเดียวกัน

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | int |  |