---
title: IDataLabel
second_title: Aspose.Slides สำหรับ Java - เอกสารอ้างอิง API
description: เป็นตัวแทนของป้ายกำกับชุดข้อมูล.
type: docs
url: /th/com.aspose.slides/idatalabel/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

เป็นตัวแทนของป้ายกำกับชุดข้อมูล
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [isVisible()](#isVisible--) | False หมายความว่าป้ายกำกับข้อมูลไม่แสดง (และจึงทำให้ฟล็าก Show\*-flags (ShowValue, ...) เป็น false) |
| [hide()](#hide--) | ทำให้ป้ายกำกับข้อมูลซ่อนโดยตั้งค่าฟล็าก Show\*-flags (ShowValue, ...) เป็นสถานะ false |
| [getDataLabelFormat()](#getDataLabelFormat--) | คืนค่ารูปแบบของป้ายกำกับข้อมูล |
| [getValueFromCell()](#getValueFromCell--) | รับหรือกำหนดเซลล์ข้อมูลของเวิร์กบุ๊ก |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | รับหรือกำหนดเซลล์ข้อมูลของเวิร์กบุ๊ก |
| [getActualLabelText()](#getActualLabelText--) | คืนค่าข้อความป้ายกำกับจริงตามการตั้งค่า DataLabelFormat หรือค่า TextFrameForOverriding.Text |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False หมายความว่าป้ายกำกับข้อมูลไม่แสดง (และจึงทำให้ฟล็าก Show\*-flags (ShowValue, ...) เป็น false) อ่านอย่างเดียว boolean.

--------------------

หากป้ายกำกับข้อมูลแสดงอยู่ คุณสามารถทำให้มันซ่อนได้ด้วยเมธอด Hide() แต่หากป้ายกำกับข้อมูลไม่แสดง (IsVisible เป็น false) คุณสามารถทำให้ป้ายกำกับข้อมูลแสดงได้โดยตั้งค่าฟล็าก Show\*-flags (ShowValue, ...) เป็นสถานะ true

**คืนค่า:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

ทำให้ป้ายกำกับข้อมูลซ่อนโดยตั้งค่าฟล็าก Show\*-flags (ShowValue, ...) เป็นสถานะ false. IsVisible จะเป็น false หลังจากนี้.

--------------------

หากป้ายกำกับข้อมูลไม่แสดง (IsVisible เป็น false) คุณสามารถทำให้ป้ายกำกับข้อมูลแสดงได้โดยตั้งค่าฟล็าก Show\*-flags (ShowValue, ...) เป็นสถานะ true

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

คืนค่ารูปแบบของป้ายกำกับข้อมูล. อ่านอย่างเดียว [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**คืนค่า:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

รับหรือกำหนดเซลล์ข้อมูลของเวิร์กบุ๊ก ใช้เมื่อตัวแปร IDataLabelFormat.ShowLabelValueFromCell มีค่าเป็น true.

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

รับหรือกำหนดเซลล์ข้อมูลของเวิร์กบุ๊ก ใช้เมื่อตัวแปร IDataLabelFormat.ShowLabelValueFromCell มีค่าเป็น true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |

### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

คืนค่าข้อความป้ายกำกับจริงตามการตั้งค่า DataLabelFormat หรือค่า TextFrameForOverriding.Text

**คืนค่า:**
java.lang.String - ข้อความป้ายกำกับจริง String