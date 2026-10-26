---
title: IDataLabelCollection
second_title: Aspose.Slides สำหรับ Java API Reference
description: เป็นตัวแทนของป้ายกำกับซีรีส์.
type: docs
url: /th/com.aspose.slides/idatalabelcollection/
---
**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**  
com.aspose.ms.System.Collections.Generic.IGenericEnumerable, [com.aspose.slides.IChartComponent](../../com.aspose.slides/ichartcomponent)
```
public interface IDataLabelCollection extends System.Collections.Generic.IGenericEnumerable<IDataLabel>, IChartComponent
```

เป็นตัวแทนของป้ายกำกับซีรีส์.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | รับป้ายกำกับข้อมูลสำหรับจุดข้อมูลที่มีดัชนีที่ระบุ. |
| [getDefaultDataLabelFormat()](#getDefaultDataLabelFormat--) | ส่งคืนรูปแบบเริ่มต้นของป้ายกำกับข้อมูลทั้งหมดในคอลเลกชัน. |
| [getLeaderLinesFormat()](#getLeaderLinesFormat--) | เป็นตัวแทนของรูปแบบเส้นนำป้ายกำกับข้อมูล. |
| [isVisible()](#isVisible--) | False หมายความว่าป้ายกำกับข้อมูลไม่แสดงโดยค่าเริ่มต้น (และดังนั้นทุก Show\*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat จะเป็น false). |
| [hide()](#hide--) | ทำให้ป้ายกำกับข้อมูลซ่อนโดยค่าเริ่มต้นโดยตั้งค่าทั้งหมด Show\*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat เป็นสถานะ false. |
| [getCountOfVisibleDataLabels()](#getCountOfVisibleDataLabels--) | รับจำนวนป้ายกำกับข้อมูลที่มองเห็นได้ในคอลเลกชัน. |
| [getCount()](#getCount--) | รับจำนวนป้ายกำกับข้อมูลทั้งหมดในคอลเลกชัน. |
| [getParentSeries()](#getParentSeries--) | ส่งคืนซีรีส์แผนภูมิแม่. |
| [indexOf(IDataLabel value)](#indexOf-com.aspose.slides.IDataLabel-) | ส่งคืนดัชนีของ DataLabel ที่ระบุในคอลเลกชัน. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IDataLabel get_Item(int index)
```

รับป้ายกำกับข้อมูลสำหรับจุดข้อมูลที่มีดัชนีที่ระบุ.

--------------------

วิธีการเข้าถึงป้ายกำกับข้อมูลแบบอื่นคือ: - getSeries().getDataPoints().get_Item(i).getLabel() - จัดการคุณสมบัติของป้ายกำกับ

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| index | int |  |

**คืนค่า:**
[IDataLabel](../../com.aspose.slides/idatalabel)
### getDefaultDataLabelFormat() {#getDefaultDataLabelFormat--}
```
public abstract IDataLabelFormat getDefaultDataLabelFormat()
```

ส่งคืนรูปแบบเริ่มต้นของป้ายกำกับข้อมูลทั้งหมดในคอลเลกชัน. อ่านอย่างเดียว [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**คืนค่า:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getLeaderLinesFormat() {#getLeaderLinesFormat--}
```
public abstract IChartLinesFormat getLeaderLinesFormat()
```

เป็นตัวแทนของรูปแบบเส้นนำป้ายกำกับข้อมูล. อ่านอย่างเดียว [IChartLinesFormat](../../com.aspose.slides/ichartlinesformat).

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
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False หมายความว่าป้ายกำกับข้อมูลไม่แสดงโดยค่าเริ่มต้น (และดังนั้นทุก Show\*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat จะเป็น false). อ่านอย่างเดียว  boolean .

--------------------

หากป้ายกำกับข้อมูลแสดงโดยค่าเริ่มต้นคุณสามารถทำให้มันซ่อนโดยค่าเริ่มต้นด้วยเมธอด Hide()ได้ แต่หากป้ายกำกับข้อมูลไม่แสดงโดยค่าเริ่มต้น (IsVisible เป็น false) คุณสามารถทำให้ป้ายกำกับข้อมูล "แสดงโดยค่าเริ่มต้น" ได้โดยตั้งค่า Show\*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat เป็นสถานะ true.

**คืนค่า:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

ทำให้ป้ายกำกับข้อมูลซ่อนโดยค่าเริ่มต้นโดยตั้งค่าทั้งหมด Show\*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat เป็นสถานะ false. IsVisible จะเป็น false หลังจากนี้.

--------------------

หากป้ายกำกับข้อมูลไม่แสดงโดยค่าเริ่มต้น (IsVisible เป็น false) คุณสามารถทำให้ป้ายกำกับข้อมูล "แสดงโดยค่าเริ่มต้น" ได้โดยตั้งค่า Show\*-flags (ShowValue, ...) ของคุณสมบัติ DefaultDataLabelFormat เป็นสถานะ true.

### getCountOfVisibleDataLabels() {#getCountOfVisibleDataLabels--}
```
public abstract int getCountOfVisibleDataLabels()
```

รับจำนวนป้ายกำกับข้อมูลที่มองเห็นได้ในคอลเลกชัน. อ่านอย่างเดียว  int .

**คืนค่า:**
int
### getCount() {#getCount--}
```
public abstract int getCount()
```

รับจำนวนป้ายกำกับข้อมูลทั้งหมดในคอลเลกชัน. อ่านอย่างเดียว  int .

**คืนค่า:**
int
### getParentSeries() {#getParentSeries--}
```
public abstract IChartSeries getParentSeries()
```

ส่งคืนซีรีส์แผนภูมิแม่. อ่านอย่างเดียว [IChartSeries](../../com.aspose.slides/ichartseries).

**คืนค่า:**
[IChartSeries](../../com.aspose.slides/ichartseries)
### indexOf(IDataLabel value) {#indexOf-com.aspose.slides.IDataLabel-}
```
public abstract int indexOf(IDataLabel value)
```

ส่งคืนดัชนีของ DataLabel ที่ระบุในคอลเลกชัน.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | [IDataLabel](../../com.aspose.slides/idatalabel) | DataLabel ที่จะค้นหา. |

**คืนค่า:**
int - ดัชนีของ DataLabel หรือ -1 หาก DataLabel ไม่ได้มาจากคอลเลกชันนี้.