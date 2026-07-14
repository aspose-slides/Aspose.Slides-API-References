---
title: IDataLabelCollection
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: เป็นตัวแทนของฉลากชุดข้อมูล.
type: docs
url: /th/com.aspose.slides/idatalabelcollection/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

เป็นตัวแทนของฉลากชุดข้อมูล.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับฉลากข้อมูลสำหรับจุดข้อมูลที่มีดัชนีที่ระบุ. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | คืนค่ารูปแบบเริ่มต้นของฉลากข้อมูลทั้งหมดในคอลเลกชัน. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | เป็นตัวแทนของรูปแบบเส้นเชื่อมฉลากข้อมูล. |
| [isVisible()](#isVisible--) | False หมายความว่าฉลากข้อมูลไม่แสดงเป็นค่าเริ่มต้น (และดังนั้นทุก Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat จะเป็น false). |
| [hide()](#hide--) | ทำให้ฉลากข้อมูลซ่อนเป็นค่าเริ่มต้นโดยตั้งค่าทั้งหมด Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat เป็นสถานะ false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | รับจำนวนของฉลากข้อมูลที่มองเห็นได้ในคอลเลกชัน. |
| [getCount()](#getCount--) | รับจำนวนของฉลากข้อมูลทั้งหมดในคอลเลกชัน. |
| [getParentSeries()](#getParentSeries--) | คืนค่าชุดข้อมูลแผนภูมิแม่. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | คืนค่าดัชนีของ DataLabel ที่ระบุในคอลเลกชัน. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```


รับฉลากข้อมูลสำหรับจุดข้อมูลที่มีดัชนีที่ระบุ.

--------------------

วิธีทางเลือกในการเข้าถึงฉลากข้อมูลคือ: - getSeries().getDataPoints().get_Item(i).getLabel() - จัดการคุณสมบัติเฉพาะของฉลาก

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**ผลลัพธ์:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```


คืนค่ารูปแบบเริ่มต้นของฉลากข้อมูลทั้งหมดในคอลเลกชัน. อ่าน-อย่างเดียว [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**ผลลัพธ์:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```


เป็นตัวแทนของรูปแบบเส้นเชื่อมฉลากข้อมูล. อ่าน-อย่างเดียว [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```


False หมายความว่าฉลากข้อมูลไม่แสดงเป็นค่าเริ่มต้น (และดังนั้นทุก Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat จะเป็น false). อ่าน-อย่างเดียว  boolean .

--------------------

หากฉลากข้อมูลแสดงเป็นค่าเริ่มต้นคุณสามารถทำให้ซ่อนเป็นค่าเริ่มต้นด้วยเมธอด Hide() แต่หากฉลากข้อมูลไม่แสดงเป็นค่าเริ่มต้น (IsVisible เป็น false) คุณสามารถทำให้ฉลากข้อมูล "แสดงเป็นค่าเริ่มต้น" โดยตั้งค่า Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat เป็นสถานะ true.

**ผลลัพธ์:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```


ทำให้ฉลากข้อมูลซ่อนเป็นค่าเริ่มต้นโดยตั้งค่าทั้งหมด Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat เป็นสถานะ false. IsVisible จะเป็น false หลังจากนี้.

--------------------

หากฉลากข้อมูลไม่แสดงเป็นค่าเริ่มต้น (IsVisible เป็น false) คุณสามารถทำให้ฉลากข้อมูล "แสดงเป็นค่าเริ่มต้น" โดยตั้งค่า Show*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat เป็นสถานะ true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```


รับจำนวนของฉลากข้อมูลที่มองเห็นได้ในคอลเลกชัน. อ่าน-อย่างเดียว  int .

**ผลลัพธ์:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```


รับจำนวนของฉลากข้อมูลทั้งหมดในคอลเลกชัน. อ่าน-อย่างเดียว  int .

**ผลลัพธ์:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```


คืนค่าชุดข้อมูลแผนภูมิแม่. อ่าน-อย่างเดียว [IChartSeries](../../com.aspose.slides/ichartseries).

**ผลลัพธ์:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```


คืนค่าดัชนีของ DataLabel ที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel ที่ต้องการค้นหา. |

**ผลลัพธ์:**
int - ดัชนีของ DataLabel หรือ -1 หาก DataLabel ไม่อยู่ในคอลเลกชันนี้.