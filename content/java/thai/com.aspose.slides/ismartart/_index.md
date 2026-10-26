---
title: ISmartArt
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของแผนภาพ SmartArt.
type: docs
url: /th/com.aspose.slides/ismartart/
---
**อินเทอร์เฟซที่นำมาใช้งานทั้งหมด:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

เป็นตัวแทนของแผนภาพ SmartArt.
## เมธอด

| Method | Description |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | ส่งคืนคอลเลกชันของโหนดทั้งหมดในอ็อบเจกต์ SmartArt. |
| [getNodes()](#getNodes--) | ส่งคืนคอลเลกชันของโหนดรากในอ็อบเจกต์ SmartArt. |
| [getLayout()](#getLayout--) | รับหรือกำหนดเค้าโครงของอ็อบเจกต์ SmartArt. |
| [setLayout(int value)](#setLayout-int-) | รับหรือกำหนดเค้าโครงของอ็อบเจกต์ SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | รับหรือกำหนดสไตล์ด่วนของอ็อบเจกต์ SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | รับหรือกำหนดสไตล์ด่วนของอ็อบเจกต์ SmartArt. |
| [getColorStyle()](#getColorStyle--) | รับหรือกำหนดสไตล์สีของอ็อบเจกต์ SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | รับหรือกำหนดสไตล์สีของอ็อบเจกต์ SmartArt. |
| [isReversed()](#isReversed--) | รับหรือกำหนดสถานะของแผนภาพ SmartArt เกี่ยวกับ (จากซ้ายไปขวา) LTR หรือ (จากขวาไปซ้าย) RTL หากแผนภาพรองรับการกลับทิศ. |
| [setReversed(boolean value)](#setReversed-boolean-) | รับหรือกำหนดสถานะของแผนภาพ SmartArt เกี่ยวกับ (จากซ้ายไปขวา) LTR หรือ (จากขวาไปซ้าย) RTL หากแผนภาพรองรับการกลับทิศ. |
### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

ส่งคืนคอลเลกชันของโหนดทั้งหมดในอ็อบเจกต์ SmartArt. อ่านอย่างเดียว [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**ส่งคืน:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

ส่งคืนคอลเลกชันของโหนดรากในอ็อบเจกต์ SmartArt. อ่านอย่างเดียว [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**ส่งคืน:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

รับหรือกำหนดเค้าโครงของอ็อบเจกต์ SmartArt. อ่าน/เขียน [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**ส่งคืน:**
int
### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

รับหรือกำหนดเค้าโครงของอ็อบเจกต์ SmartArt. อ่าน/เขียน [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

รับหรือกำหนดสไตล์ด่วนของอ็อบเจกต์ SmartArt. อ่าน/เขียน [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**ส่งคืน:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

รับหรือกำหนดสไตล์ด่วนของอ็อบเจกต์ SmartArt. อ่าน/เขียน [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

รับหรือกำหนดสไตล์สีของอ็อบเจกต์ SmartArt. อ่าน/เขียน [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**ส่งคืน:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

รับหรือกำหนดสไตล์สีของอ็อบเจกต์ SmartArt. อ่าน/เขียน [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

รับหรือกำหนดสถานะของแผนภาพ SmartArt เกี่ยวกับ (จากซ้ายไปขวา) LTR หรือ (จากขวาไปซ้าย) RTL หากแผนภาพรองรับการกลับทิศ. อ่าน/เขียน boolean.

**ส่งคืน:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

รับหรือกำหนดสถานะของแผนภาพ SmartArt เกี่ยวกับ (จากซ้ายไปขวา) LTR หรือ (จากขวาไปซ้าย) RTL หากแผนภาพรองรับการกลับทิศ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |