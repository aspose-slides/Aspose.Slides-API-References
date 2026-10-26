---
title: IChartTitle
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงคุณสมบัติของหัวเรื่องแผนภูมิ.
type: docs
url: /th/com.aspose.slides/icharttitle/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface IChartTitle extends ILayoutable, IOverridableText, IActualLayout
```

แสดงคุณสมบัติของหัวเรื่องแผนภูมิ.
## เมธอด

| Method | Description |
| --- | --- |
| [getOverlay()](#getOverlay--) | กำหนดว่าองค์ประกอบแผนภูมิอื่น ๆ จะอนุญาตให้ซ้อนทับหัวเรื่องหรือไม่. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | กำหนดว่าองค์ประกอบแผนภูมิอื่น ๆ จะอนุญาตให้ซ้อนทับหัวเรื่องหรือไม่. |
| [getFormat()](#getFormat--) | ส่งคืนสไตล์การเติม, เส้น, เอฟเฟกต์ ของหัวเรื่อง. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```

กำหนดว่าองค์ประกอบแผนภูมิอื่น ๆ จะอนุญาตให้ซ้อนทับหัวเรื่องหรือไม่. อ่าน/เขียน boolean.

**คืนค่า:**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```

กำหนดว่าองค์ประกอบแผนภูมิอื่น ๆ จะอนุญาตให้ซ้อนทับหัวเรื่องหรือไม่. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

ส่งคืนสไตล์การเติม, เส้น, เอฟเฟกต์ ของหัวเรื่อง. อ่านอย่างเดียว [IFormat](../../com.aspose.slides/iformat).

**คืนค่า:**
[IFormat](../../com.aspose.slides/iformat)