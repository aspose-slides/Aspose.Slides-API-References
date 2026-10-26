---
title: IChartTitle
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงคุณลักษณะของชื่อแผนภูมิ.
type: docs
url: /th/com.aspose.slides/icharttitle/
---
**อินเทอร์เฟซทั้งหมดที่ใช้งาน:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

แสดงคุณลักษณะของชื่อแผนภูมิ.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOverlay()](#getOverlay--) | กำหนดว่าองค์ประกอบแผนภูมิอื่น ๆ จะได้รับอนุญาตให้ซ้อนทับชื่อหรือไม่. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | กำหนดว่าองค์ประกอบแผนภูมิอื่น ๆ จะได้รับอนุญาตให้ซ้อนทับชื่อหรือไม่. |
| [getFormat()](#getFormat--) | ส่งคืนสไตล์การเติม สี เส้น เอฟเฟกต์ของชื่อ. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

กำหนดว่าองค์ประกอบแผนภูมิอื่น ๆ จะได้รับอนุญาตให้ซ้อนทับชื่อหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

กำหนดว่าองค์ประกอบแผนภูมิอื่น ๆ จะได้รับอนุญาตให้ซ้อนทับชื่อหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

ส่งคืนสไตล์การเติม สี เส้น เอฟเฟกต์ของชื่อ. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)