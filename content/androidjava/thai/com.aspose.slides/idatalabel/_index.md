---
title: IDataLabel
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงป้ายกำกับของซีรีส์
type: docs
url: /th/com.aspose.slides/idatalabel/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IDataLabel extends ILayoutable, IOverridableText, IActualLayout
```

แทนชุดป้ายกำกับของซีรีส์
## เมธอด

| Method | Description |
| --- | --- |
| [isVisible()](#isVisible--) | False หมายความว่าป้ายข้อมูลไม่ปรากฏ (และดังนั้นทุก Show*-flags (ShowValue, ...) เป็น false) |
| [hide()](#hide--) | ทำให้ป้ายข้อมูลซ่อนโดยการตั้งค่าทุก Show*-flags (ShowValue, ...) เป็นสถานะ false |
| [getDataLabelFormat()](#getDataLabelFormat--) | Returns format of the data label. |
| [getValueFromCell()](#getValueFromCell--) | Gets or sets workbook data cell. |
| [setValueFromCell(IChartDataCell value)](#setValueFromCell-com.aspose.slides.IChartDataCell-) | Gets or sets workbook data cell. |
| [getActualLabelText()](#getActualLabelText--) | Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value. |
### isVisible() {#isVisible--}
```
public abstract boolean isVisible()
```

False หมายความว่าป้ายข้อมูลไม่ปรากฏ (และดังนั้นทุก Show*-flags (ShowValue, ...) เป็น false) อ่านอย่างเดียว boolean.

--------------------

หากป้ายข้อมูลปรากฏคุณสามารถทำให้ซ่อนได้ด้วยเมธอด Hide() แต่หากป้ายข้อมูลไม่ปรากฏ (IsVisible เป็น false) คุณสามารถทำให้ป้ายข้อมูลปรากฏได้โดยตั้งค่า Show*-flags (ShowValue, ...) เป็นสถานะ true

**คืนค่า:**
boolean
### hide() {#hide--}
```
public abstract void hide()
```

ทำให้ป้ายข้อมูลซ่อนโดยการตั้งค่าทุก Show*-flags (ShowValue, ...) เป็นสถานะ false IsVisible จะเป็น false หลังจากนี้

--------------------

หากป้ายข้อมูลไม่ปรากฏ (IsVisible เป็น false) คุณสามารถทำให้ป้ายข้อมูลปรากฏได้โดยตั้งค่า Show*-flags (ShowValue, ...) เป็นสถานะ true

### getDataLabelFormat() {#getDataLabelFormat--}
```
public abstract IDataLabelFormat getDataLabelFormat()
```

Returns format of the data label. อ่านอย่างเดียว [IDataLabelFormat](../../com.aspose.slides/idatalabelformat).

**คืนค่า:**
[IDataLabelFormat](../../com.aspose.slides/idatalabelformat)
### getValueFromCell() {#getValueFromCell--}
```
public abstract IChartDataCell getValueFromCell()
```

Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true.

**คืนค่า:**
[IChartDataCell](../../com.aspose.slides/ichartdatacell)
### setValueFromCell(IChartDataCell value) {#setValueFromCell-com.aspose.slides.IChartDataCell-}
```
public abstract void setValueFromCell(IChartDataCell value)
```

Gets or sets workbook data cell. Applied if IDataLabelFormat.ShowLabelValueFromCell property equals true.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IChartDataCell](../../com.aspose.slides/ichartdatacell) |  |
### getActualLabelText() {#getActualLabelText--}
```
public abstract String getActualLabelText()
```

Returns actual label text based on DataLabelFormat settings or TextFrameForOverriding.Text value.

**คืนค่า:**
java.lang.String - ข้อความป้ายกำกับจริง String