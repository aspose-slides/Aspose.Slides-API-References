---
title: ILegend
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงคุณสมบัติเสียงของแผนภูมิ
type: docs
url: /th/com.aspose.slides/ilegend/
---
**อินเทอร์เฟซที่ใช้งานทั้งหมด:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

แสดงคุณสมบัติเสียงของแผนภูมิ
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOverlay()](#getOverlay--) | กำหนดว่าตัวองค์ประกอบแผนภูมิอื่น ๆ จะอนุญาตให้ทับซ้อนกับเลเจนด์หรือไม่ |
| [setOverlay(boolean value)](#setOverlay-boolean-) | กำหนดว่าตัวองค์ประกอบแผนภูมิอื่น ๆ จะอนุญาตให้ทับซ้อนกับเลเจนด์หรือไม่ |
| [getPosition()](#getPosition--) | ระบุตำแหน่งของเลเจนด์บนแผนภูมิ |
| [setPosition(int value)](#setPosition-int-) | ระบุตำแหน่งของเลเจนด์บนแผนภูมิ |
| [getFormat()](#getFormat--) | ส่งคืนรูปแบบของเลเจนด์ |
| [getEntries()](#getEntries--) | รับรายการเลเจนด์ |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

กำหนดว่าตัวองค์ประกอบแผนภูมิอื่น ๆ จะอนุญาตให้ทับซ้อนกับเลเจนด์หรือไม่ อ่าน/เขียน boolean

**คืนค่า:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

กำหนดว่าตัวองค์ประกอบแผนภูมิอื่น ๆ จะอนุญาตให้ทับซ้อนกับเลเจนด์หรือไม่ อ่าน/เขียน boolean

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

ระบุตำแหน่งของเลเจนด์บนแผนภูมิ ค่าที่ไม่ใช่ NaN ของคุณสมบัติ X, Y, Width, Heigt จะเขียนทับผลของคุณสมบัตินี้ อ่าน/เขียน [LegendPositionType](../../com.aspose.slides/legendpositiontype)

**คืนค่า:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

ระบุตำแหน่งของเลเจนด์บนแผนภูมิ ค่าที่ไม่ใช่ NaN ของคุณสมบัติ X, Y, Width, Heigt จะเขียนทับผลของคุณสมบัตินี้ อ่าน/เขียน [LegendPositionType](../../com.aspose.slides/legendpositiontype)

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

ส่งคืนรูปแบบของเลเจนด์ อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat)

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

รับรายการเลเจนด์ อ่านอย่างเดียว [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)

**คืนค่า:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)