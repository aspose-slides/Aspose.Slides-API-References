---
title: ILegend
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงคุณสมบัติของ legend ของแผนภูมิ.
type: docs
url: /th/com.aspose.slides/ilegend/
---
**อินเทอร์เฟสที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

แสดงคุณสมบัติของ legend ของแผนภูมิ.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOverlay()](#getOverlay--) | กำหนดว่าองค์ประกอบแผนภูมิอื่น ๆ จะได้รับอนุญาตให้ทับ legend หรือไม่. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | กำหนดว่าองค์ประกอบแผนภูมิอื่น ๆ จะได้รับอนุญาตให้ทับ legend หรือไม่. |
| [getPosition()](#getPosition--) | ระบุตำแหน่งของ legend บนแผนภูมิ. |
| [setPosition(int value)](#setPosition-int-) | ระบุตำแหน่งของ legend บนแผนภูมิ. |
| [getFormat()](#getFormat--) | คืนค่ารูปแบบของ legend. |
| [getEntries()](#getEntries--) | รับรายการ legend. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

กำหนดว่าองค์ประกอบแผนภูมิอื่น ๆ จะได้รับอนุญาตให้ทับ legend หรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

กำหนดว่าองค์ประกอบแผนภูมิอื่น ๆ จะได้รับอนุญาตให้ทับ legend หรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

ระบุตำแหน่งของ legend บนแผนภูมิ. ค่าที่ไม่ใช่ NaN ของคุณสมบัติ X, Y, Width, Heigt จะครอบคลุมผลของคุณสมบัตินี้. อ่าน/เขียน [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**คืนค่า:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

ระบุตำแหน่งของ legend บนแผนภูมิ. ค่าที่ไม่ใช่ NaN ของคุณสมบัติ X, Y, Width, Heigt จะครอบคลุมผลของคุณสมบัตินี้. อ่าน/เขียน [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

คืนค่ารูปแบบของ legend. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```

รับรายการ legend. อ่านอย่างเดียว [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**คืนค่า:**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)