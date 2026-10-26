---
title: SmartArt
second_title: Aspose.Slides สำหรับ Android ผ่านอ้างอิง API Java
description: เป็นแผนภูมิ SmartArt
type: docs
url: /th/com.aspose.slides/smartart/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**ส่วนติดต่อที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.ISmartArt](../../com.aspose.slides/ismartart)
```
public class SmartArt extends GraphicalObject implements ISmartArt
```

เป็นแผนภูมิ SmartArt
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getAllNodes()](#getAllNodes--) | ส่งคืนคอลเลกชันของโหนดทั้งหมดในวัตถุ SmartArt. |
| [getNodes()](#getNodes--) | ส่งคืนคอลเลกชันของโหนดรากในวัตถุ SmartArt. |
| [getLayout()](#getLayout--) | ส่งคืนหรือกำหนดเค้าโครงของวัตถุ SmartArt. |
| [setLayout(int value)](#setLayout-int-) | ส่งคืนหรือกำหนดเค้าโครงของวัตถุ SmartArt. |
| [getQuickStyle()](#getQuickStyle--) | ส่งคืนหรือกำหนดสไตล์ด่วนของวัตถุ SmartArt. |
| [setQuickStyle(int value)](#setQuickStyle-int-) | ส่งคืนหรือกำหนดสไตล์ด่วนของวัตถุ SmartArt. |
| [getColorStyle()](#getColorStyle--) | ส่งคืนหรือกำหนดสไตล์สีของวัตถุ SmartArt. |
| [setColorStyle(int value)](#setColorStyle-int-) | ส่งคืนหรือกำหนดสไตล์สีของวัตถุ SmartArt. |
| [isReversed()](#isReversed--) | ส่งคืนหรือกำหนดสถานะของแผนภูมิ SmartArt เกี่ยวกับ (ซ้ายไปขวา) LTR หรือ (ขวาไปซ้าย) RTL หากแผนภูมิสนับสนุนการกลับทิศ. |
| [setReversed(boolean value)](#setReversed-boolean-) | ส่งคืนหรือกำหนดสถานะของแผนภูมิ SmartArt เกี่ยวกับ (ซ้ายไปขวา) LTR หรือ (ขวาไปซ้าย) RTL หากแผนภูมิสนับสนุนการกลับทิศ. |
### getAllNodes() {#getAllNodes--}
```
public final ISmartArtNodeCollection getAllNodes()
```

ส่งคืนคอลเลกชันของโหนดทั้งหมดในวัตถุ SmartArt. อ่านเท่านั้น [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**ส่งคืน:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getNodes() {#getNodes--}
```
public final ISmartArtNodeCollection getNodes()
```

ส่งคืนคอลเลกชันของโหนดรากในวัตถุ SmartArt. อ่านเท่านั้น [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**ส่งคืน:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getLayout() {#getLayout--}
```
public final int getLayout()
```

ส่งคืนหรือกำหนดเค้าโครงของวัตถุ SmartArt. อ่าน/เขียน [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**ส่งคืน:**
int
### setLayout(int value) {#setLayout-int-}
```
public final void setLayout(int value)
```

ส่งคืนหรือกำหนดเค้าโครงของวัตถุ SmartArt. อ่าน/เขียน [SmartArtLayoutType](../../com.aspose.slides/smartartlayouttype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getQuickStyle() {#getQuickStyle--}
```
public final int getQuickStyle()
```

ส่งคืนหรือกำหนดสไตล์ด่วนของวัตถุ SmartArt. อ่าน/เขียน [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**ส่งคืน:**
int
### setQuickStyle(int value) {#setQuickStyle-int-}
```
public final void setQuickStyle(int value)
```

ส่งคืนหรือกำหนดสไตล์ด่วนของวัตถุ SmartArt. อ่าน/เขียน [SmartArtQuickStyleType](../../com.aspose.slides/smartartquickstyletype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getColorStyle() {#getColorStyle--}
```
public final int getColorStyle()
```

ส่งคืนหรือกำหนดสไตล์สีของวัตถุ SmartArt. อ่าน/เขียน [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**ส่งคืน:**
int
### setColorStyle(int value) {#setColorStyle-int-}
```
public final void setColorStyle(int value)
```

ส่งคืนหรือกำหนดสไตล์สีของวัตถุ SmartArt. อ่าน/เขียน [SmartArtColorType](../../com.aspose.slides/smartartcolortype).

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### isReversed() {#isReversed--}
```
public final boolean isReversed()
```

ส่งคืนหรือกำหนดสถานะของแผนภูมิ SmartArt เกี่ยวกับ (ซ้ายไปขวา) LTR หรือ (ขวาไปซ้าย) RTL หากแผนภูมิสนับสนุนการกลับทิศ. อ่าน/เขียน  boolean .

**ส่งคืน:**
boolean
### setReversed(boolean value) {#setReversed-boolean-}
```
public final void setReversed(boolean value)
```

ส่งคืนหรือกำหนดสถานะของแผนภูมิ SmartArt เกี่ยวกับ (ซ้ายไปขวา) LTR หรือ (ขวาไปซ้าย) RTL หากแผนภูมิสนับสนุนการกลับทิศ. อ่าน/เขียน  boolean .

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |