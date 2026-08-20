---
title: NormalViewRestoredProperties
second_title: Aspose.Slides สำหรับอ้างอิง API ของ Java
description: ระบุขนาดของพื้นที่สไลด์ (ความกว้างเมื่อเป็นลูกของ restoredTop, ความสูงเมื่อเป็นลูกของ restoredLeft) ของมุมมองปกติเมื่อพื้นที่มีขนาดที่เปลี่ยนแปลงได้ (ไม่ถูกย่อหรือขยาย)
type: docs
url: /th/com.aspose.slides/normalviewrestoredproperties/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการสืบทอดทั้งหมด:**
[com.aspose.slides.INormalViewRestoredProperties](../../com.aspose.slides/inormalviewrestoredproperties)
```
public class NormalViewRestoredProperties implements INormalViewRestoredProperties
```

ระบุขนาดของพื้นที่สไลด์ ((width when a child of restoredTop, height when a child of restoredLeft) ของมุมมองปกติ, เมื่อพื้นที่มีขนาดที่เปลี่ยนแปลงได้ (neither minimized nor maximized).

## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | ระบุขนาดของพื้นที่สไลด์ (width when a child of RestoredTop, height when a child of RestoredLeft). |
| [setDimensionSize(float value)](#setDimensionSize-float-) | ระบุขนาดของพื้นที่สไลด์ (width when a child of RestoredTop, height when a child of RestoredLeft). |
| [getAutoAdjust()](#getAutoAdjust--) | ระบุว่าขนาดของพื้นที่เนื้อหาข้างเคียงควรชดเชยขนาดใหม่เมื่อปรับขนาดหน้าต่างที่มีมุมมองอยู่ภายในแอปพลิเคชันหรือไม่ Read/write boolean. |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | ระบุว่าขนาดของพื้นที่เนื้อหาข้างเคียงควรชดเชยขนาดใหม่เมื่อปรับขนาดหน้าต่างที่มีมุมมองอยู่ภายในแอปพลิเคชันหรือไม่ Read/write boolean. |

### getDimensionSize() {#getDimensionSize--}
```
public final float getDimensionSize()
```

ระบุขนาดของพื้นที่สไลด์ (width when a child of RestoredTop, height when a child of RestoredLeft). Read/write float.

**คืนค่า:**
float

### setDimensionSize(float value) {#setDimensionSize-float-}
```
public final void setDimensionSize(float value)
```

ระบุขนาดของพื้นที่สไลด์ (width when a child of RestoredTop, height when a child of RestoredLeft). Read/write float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getAutoAdjust() {#getAutoAdjust--}
```
public final boolean getAutoAdjust()
```

ระบุว่าขนาดของพื้นที่เนื้อหาข้างเคียงควรชดเชยขนาดใหม่เมื่อปรับขนาดหน้าต่างที่มีมุมมองอยู่ภายในแอปพลิเคชันหรือไม่ Read/write boolean.

**คืนค่า:**
boolean

### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public final void setAutoAdjust(boolean value)
```

ระบุว่าขนาดของพื้นที่เนื้อหาข้างเคียงควรชดเชยขนาดใหม่เมื่อปรับขนาดหน้าต่างที่มีมุมมองอยู่ภายในแอปพลิเคชันหรือไม่ Read/write boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |