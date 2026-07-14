---
title: ISmartArt
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: เป็นตัวแทนของไดอะแกรม SmartArt.
type: docs
url: /th/com.aspose.slides/ismartart/
---
**ทุกรายการอินเทอร์เฟซที่นำไปใช้:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ISmartArt extends IGraphicalObject
```

Represents a SmartArt diagram.

## วิธีการ

| Method | Description |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | ส่งคืนคอลเลกชันของโหนดทั้งหมดในอ็อบเจกต์ SmartArt. |
| [getNodes()](#getNodes--) | ส่งคืนคอลเลกชันของโหนดรากในอ็อบเจกต์ SmartArt. |
| [getLayout()](#getLayout--) | ส่งคืนหรือกำหนดเค้าโครงของอ็อบเจกต์ SmartArt. |
| [setLayout(int value)](#setLayout-int-) | ส่งคืนหรือกำหนดเค้าโครงของอ็อบเจกต์ SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | ส่งคืนหรือกำหนดสไตล์ด่วนของอ็อบเจกต์ SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | ส่งคืนหรือกำหนดสไตล์ด่วนของอ็อบเจกต์ SmartArt. |
| [getColorStyle()](#getColorStyle--) | ส่งคืนหรือกำหนดสไตล์สีของอ็อบเจกต์ SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | ส่งคืนหรือกำหนดสไตล์สีของอ็อบเจกต์ SmartArt. |
| [isReversed()](#isReversed--) | ส่งคืนหรือกำหนดสถานะของแผนภาพ SmartArt ที่เกี่ยวกับ (จากซ้ายไปขวา) LTR หรือ (จากขวาไปซ้าย) RTL หากแผนภาพสนับสนุนการย้อนกลับ. |
| [setReversed(boolean value)](#setReversed-boolean-) | ส่งคืนหรือกำหนดสถานะของแผนภาพ SmartArt ที่เกี่ยวกับ (จากซ้ายไปขวา) LTR หรือ (จากขวาไปซ้าย) RTL หากแผนภาพสนับสนุนการย้อนกลับ. |

### getAllNodes() {#getAllNodes--}
```
public abstract ISmartArtNodeCollection getAllNodes()
```

ส่งคืนคอลเลกชันของโหนดทั้งหมดในอ็อบเจกต์ SmartArt. อ่านอย่างเดียว [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**คืนค่า:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getNodes() {#getNodes--}
```
public abstract ISmartArtNodeCollection getNodes()
```

ส่งคืนคอลเลกชันของโหนดรากในอ็อบเจกต์ SmartArt. อ่านอย่างเดียว [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**คืนค่า:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getLayout() {#getLayout--}
```
public abstract int getLayout()
```

ส่งคืนหรือกำหนดเค้าโครงของอ็อบเจกต์ SmartArt. อ่าน/เขียน [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**คืนค่า:**
int

### setLayout(int value) {#setLayout-int-}
```
public abstract void setLayout(int value)
```

ส่งคืนหรือกำหนดเค้าโครงของอ็อบเจกต์ SmartArt. อ่าน/เขียน [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public abstract int getQuickStyle()
```

ส่งคืนหรือกำหนดสไตล์ด่วนของอ็อบเจกต์ SmartArt. อ่าน/เขียน [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**คืนค่า:**
int

### setQuickStyle(int value) {#setQuickStyle-int-}
```
public abstract void setQuickStyle(int value)
```

ส่งคืนหรือกำหนดสไตล์ด่วนของอ็อบเจกต์ SmartArt. อ่าน/เขียน [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public abstract int getColorStyle()
```

ส่งคืนหรือกำหนดสไตล์สีของอ็อบเจกต์ SmartArt. อ่าน/เขียน [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**คืนค่า:**
int

### setColorStyle(int value) {#setColorStyle-int-}
```
public abstract void setColorStyle(int value)
```

ส่งคืนหรือกำหนดสไตล์สีของอ็อบเจกต์ SmartArt. อ่าน/เขียน [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public abstract boolean isReversed()
```

ส่งคืนหรือกำหนดสถานะของแผนภาพ SmartArt ที่เกี่ยวกับ (จากซ้ายไปขวา) LTR หรือ (จากขวาไปซ้าย) RTL หากแผนภาพสนับสนุนการย้อนกลับ. อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setReversed(boolean value) {#setReversed-boolean-}
```
public abstract void setReversed(boolean value)
```

ส่งคืนหรือกำหนดสถานะของแผนภาพ SmartArt ที่เกี่ยวกับ (จากซ้ายไปขวา) LTR หรือ (จากขวาไปซ้าย) RTL หากแผนภาพสนับสนุนการย้อนกลับ. อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |