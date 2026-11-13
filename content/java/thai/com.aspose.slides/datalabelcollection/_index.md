---
title: DataLabelCollection
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: แสดงฉลากของชุดข้อมูล.
type: docs
url: /th/com.aspose.slides/datalabelcollection/
---
**Inheritance:**  
java.lang.Object, com.aspose.slides.DomObject

**All Implemented Interfaces:**  
[com.aspose.slides.IDataLabelCollection](../../com.aspose.slides/idatalabelcollection)  
```
public class DataLabelCollection extends DomObject<ChartSeries> implements IDataLabelCollection
```

แสดงฉลากของชุดข้อมูล  
## เมธอด

| Method | Description |
| --- | --- |
| [getChart()](#getChart--) | คืนค่าแผนภูมิต้นแบบ |
| [iterator()](#iterator--) | คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน |
| [iteratorJava()](#iteratorJava--) | คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด |
| [isVisible()](#isVisible--) | false หมายความว่า data label ไม่แสดงโดยค่าเริ่มต้น (และทำให้ Show*-flags ทั้งหมด (ShowValue, …) ของคุณสมบัติ DefaultDataLabelFormat เป็น false) |
| [hide()](#hide--) | ทำให้ data label ซ่อนโดยค่าเริ่มต้นโดยตั้งค่า Show*-flags ทั้งหมด (ShowValue, …) ของคุณสมบัติ DefaultDataLabelFormat ให้เป็น false |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | รับจำนวนของ data label ที่มองเห็นได้ในคอลเลกชัน |
| [getCount()](#getCount--) | รับจำนวนของ data label ทั้งหมดในคอลเลกชัน |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | รับรูปแบบ data label เริ่มต้น |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | แสดงรูปแบบเส้นนำของ data label |
| [getParentSeries()](#getParentSeries--) | รับ series ต้นแบบ |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | คืนดัชนีของ DataLabel ที่ระบุในคอลเลกชัน |
| [get_Item(int index)](#get-Item-int-) | รับ data label สำหรับจุดข้อมูลที่มีดัชนีระบุ |
| [getDefaultLabelShapeType()](#getDefaultLabelShapeType--) | รับหรือกำหนดประเภทรูปทรงเริ่มต้นสำหรับ data label |
| [setDefaultLabelShapeType(int value)](#setDefaultLabelShapeType-int-) | รับหรือกำหนดประเภทรูปทรงเริ่มต้นสำหรับ data label |
| [getSlide()](#getSlide--) | คืนสไลด์แม่ของ FillFormat |
| [getPresentation()](#getPresentation--) | คืนการพรีเซนเทชันแม่ของ FillFormat |

### getChart() {#getChart--}
```
public final IChart getChart()
```

คืนแผนภูมิต้นแบบ. อ่านอย่างเดียว [IChart](../../com.aspose.slides/ichart).

**คืนค่า:**  
[IChart](../../com.aspose.slides/ichart)

### iterator() {#iterator--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iterator()
```

คืนค่า enumerator ที่วนซ้ำผ่านคอลเลกชัน.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - A IGenericEnumerator that can be used to iterate through the collection.

### iteratorJava() {#iteratorJava--}
```
public final System.Collections.Generic.IGenericEnumerator<IDataLabel> iteratorJava()
```

คืนค่า java iterator สำหรับคอลเลกชันทั้งหมด.

**คืนค่า:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerator<com.aspose.slides.IDataLabel> - An java.util.Iterator for the entire collection.

### isVisible() {#isVisible--}
```
public final boolean isVisible()
```

false หมายความว่า data label ไม่แสดงโดยค่าเริ่มต้น (และทำให้ Show*-flags ทั้งหมด (ShowValue, …) ของคุณสมบัติ DefaultDataLabelFormat เป็น false). อ่านอย่างเดียว boolean.

--------------------

หาก data label มองเห็นได้โดยค่าเริ่มต้นคุณสามารถทำให้มันซ่อนโดยค่าเริ่มต้นด้วยเมธอด Hide() แต่หาก data label ไม่มองเห็นได้โดยค่าเริ่มต้น (IsVisible เป็น false) คุณสามารถทำให้ data label “มองเห็นได้โดยค่าเริ่มต้น” โดยตั้งค่า Show*-flags (ShowValue, …) ของคุณสมบัติ DefaultDataLabelFormat ให้เป็น true

**คืนค่า:**  
boolean

### hide() {#hide--}
```
public final void hide()
```

ทำให้ data label ซ่อนโดยค่าเริ่มต้นโดยตั้งค่า Show*-flags ทั้งหมด (ShowValue, …) ของคุณสมบัติ DefaultDataLabelFormat ให้เป็น false IsVisible จะเป็น false หลังจากนี้

--------------------

หาก data label ไม่มองเห็นได้โดยค่าเริ่มต้น (IsVisible เป็น false) คุณสามารถทำให้ data label “มองเห็นได้โดยค่าเริ่มต้น” โดยตั้งค่า Show*-flags (ShowValue, …) ของคุณสมบัติ DefaultDataLabelFormat ให้เป็น true

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public final int getCountOfVisibleDataLabels()
```

รับจำนวนของ data label ที่มองเห็นได้ในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getCount() {#getCount--}
```
public final int getCount()
```

รับจำนวนของ data label ทั้งหมดในคอลเลกชัน. อ่านอย่างเดียว int.

**คืนค่า:**  
int

### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public final IDataLabelFormat getDefaultDataLabelFormat()
```

รับรูปแบบ data label เริ่มต้น. อ่านอย่างเดียว [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**คืนค่า:**  
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)

### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public final IChartLinesFormat getLeaderLinesFormat()
```

แสดงรูปแบบเส้นนำของ data label. อ่านอย่างเดียว [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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

รับ series แม่. อ่านอย่างเดียว [IChartSeries](../../com.aspose.slides/ichartseries).

**คืนค่า:**  
[IChartSeries](../../com.aspose.slides/ichartseries)

### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public final int indexOf(IDataLabel value)
```

คืนดัชนีของ DataLabel ที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel ที่ต้องการค้นหา |

**คืนค่า:**  
int - ดัชนีของ DataLabel หรือ -1 หาก DataLabel ไม่ได้มาจากคอลเลกชันนี้

### get_Item(int index) {#get-Item-int-}
```
public final IDataLabel get_Item(int index)
```

รับ data label สำหรับจุดข้อมูลที่มีดัชนีระบุ.

--------------------

วิธีทางเลือกในการเข้าถึง data label คือ: - series.getDataPoints().get_Item(i).getLabel() - จัดการคุณสมบัติของ label.

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**  
[IDataLabel](../../com.aspose.slides/idatalabel)

### getDefaultLabelShapeType() {#getDefaultLabelShapeType--}
```
public final int getDefaultLabelShapeType()
```

รับหรือกำหนดประเภทรูปทรงเริ่มต้นสำหรับ data label. คืนค่า [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) หากไม่ได้กำหนดรูปทรง.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // ตั้งค่าชนิดรูปทรงของทุก data label ใน series แรกเป็น Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

การตั้งค่าคุณสมบัตินี้จะตั้งค่า IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) สำหรับ data label ทั้งหมดในคอลเลกชันให้เป็นค่าเดียวกัน

**คืนค่า:**  
int

### setDefaultLabelShapeType(int value) {#setDefaultLabelShapeType-int-}
```
public final void setDefaultLabelShapeType(int value)
```

รับหรือกำหนดประเภทรูปทรงเริ่มต้นสำหรับ data label. คืนค่า [ShapeType.NotDefined](../../com.aspose.slides/shapetype\#NotDefined) หากไม่ได้กำหนดรูปทรง.

--------------------

> ```
> Presentation pres = new Presentation("Chart.pptx");
>  try {
>      IChart chart = (IChart)pres.getSlides().get_Item(0).getShapes().get_Item(1);
>      IChartSeries firstSeries = chart.getChartData().getSeries().get_Item(0);
>      // ตั้งค่าชนิดรูปทรงของทุก data label ใน series แรกเป็น Ellipse.
>      firstSeries.getLabels().setDefaultLabelShapeType(ShapeType.Ellipse);
>      pres.save("ChartWithEllipseLabels.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

การตั้งค่าคุณสมบัตินี้จะตั้งค่า IDataLabel.LabelShapeType ([IDataLabel.getLabelShapeType](../../com.aspose.slides/idatalabel\#getLabelShapeType)/[IDataLabel.setLabelShapeType(int)](../../com.aspose.slides/idatalabel\#setLabelShapeType-int-)) สำหรับ data label ทั้งหมดในคอลเลกชันให้เป็นค่าเดียวกัน

**พารามิเตอร์:**  
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

คืนสไลด์แม่ของ FillFormat. อ่านอย่างเดียว [BaseSlide](../../com.aspose.slides/baseslide).

**คืนค่า:**  
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

คืนการพรีเซนเทชันแม่ของ FillFormat. อ่านอย่างเดียว [IPresentation](../../com.aspose.slides/ipresentation).

**คืนค่า:**  
[IPresentation](../../com.aspose.slides/ipresentation)