---
title: INormalViewRestoredProperties
second_title: Aspose.Slides for Java API Reference
description: Specifies the sizing of the slide region width when a child of restoredTop height when a child of restoredLeft of the normal view when the region is of a variable restored sizeneither minimized nor maximized.
type: docs
url: /th/com.aspose.slides/inormalviewrestoredproperties/
---```
public interface INormalViewRestoredProperties
```

ระบุขนาดของบริเวณสไลด์ ((ความกว้างเมื่อเป็นลูกของ restoredTop, ความสูงเมื่อเป็นลูกของ restoredLeft) ของมุมมองปกติ, เมื่อบริเวณมีขนาดปรับได้ (ไม่ถูกย่อหรือขยาย)).

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | ระบุขนาดของบริเวณสไลด์ (ความกว้างเมื่อเป็นลูกของ RestoredTop, ความสูงเมื่อเป็นลูกของ RestoredLeft). |
| [setDimensionSize(float value)](#setDimensionSize-float-) | ระบุขนาดของบริเวณสไลด์ (ความกว้างเมื่อเป็นลูกของ RestoredTop, ความสูงเมื่อเป็นลูกของ RestoredLeft). |
| [getAutoAdjust()](#getAutoAdjust--) | ระบุว่าขนาดของบริเวณเนื้อหาด้านข้างควรชดเชยขนาดใหม่เมื่อปรับขนาดหน้าต่างที่มีการมองดูในแอปพลิเคชันหรือไม่ อ่าน/เขียน boolean. |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | ระบุว่าขนาดของบริเวณเนื้อหาด้านข้างควรชดเชยขนาดใหม่เมื่อปรับขนาดหน้าต่างที่มีการมองดูในแอปพลิเคชันหรือไม่ อ่าน/เขียน boolean. |

### getDimensionSize() {#getDimensionSize--}
```
public abstract float getDimensionSize()
```

ระบุขนาดของบริเวณสไลด์ (ความกว้างเมื่อเป็นลูกของ RestoredTop, ความสูงเมื่อเป็นลูกของ RestoredLeft). อ่าน/เขียน float.

**คืนค่า:**
float

### setDimensionSize(float value) {#setDimensionSize-float-}
```
public abstract void setDimensionSize(float value)
```

ระบุขนาดของบริเวณสไลด์ (ความกว้างเมื่อเป็นลูกของ RestoredTop, ความสูงเมื่อเป็นลูกของ RestoredLeft). อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getAutoAdjust() {#getAutoAdjust--}
```
public abstract boolean getAutoAdjust()
```

ระบุว่าขนาดของบริเวณเนื้อหาด้านข้างควรชดเชยขนาดใหม่เมื่อปรับขนาดหน้าต่างที่มีการมองดูในแอปพลิเคชันหรือไม่ อ่าน/เขียน boolean.

**คืนค่า:**
boolean

### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public abstract void setAutoAdjust(boolean value)
```

ระบุว่าขนาดของบริเวณเนื้อหาด้านข้างควรชดเชยขนาดใหม่เมื่อปรับขนาดหน้าต่างที่มีการมองดูในแอปพลิเคชันหรือไม่ อ่าน/เขียน boolean.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |