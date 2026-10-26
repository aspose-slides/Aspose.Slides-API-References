---
title: INormalViewRestoredProperties
second_title: Aspose.Slides for Android via Java API Reference
description: ระบุการกำหนดขนาดของพื้นที่สไลด์ (ความกว้างเมื่อเป็นลูกของ restoredTop, ความสูงเมื่อเป็นลูกของ restoredLeft) ของมุมมองปกติเมื่อพื้นที่เป็นขนาดที่เรียกคืนได้ (ไม่ถูกย่อหรือขยาย)
type: docs
url: /th/com.aspose.slides/inormalviewrestoredproperties/
---```
public interface INormalViewRestoredProperties
```

ระบุการกำหนดขนาดของพื้นที่สไลด์ ((ความกว้างเมื่อเป็นลูกของ restoredTop, ความสูงเมื่อเป็นลูกของ restoredLeft) ของมุมมองปกติ, เมื่อพื้นที่เป็นขนาดที่เรียกคืนได้ (ไม่ถูกย่อหรือขยาย)).
## Methods

| Method | Description |
| --- | --- |
| [getDimensionSize()](#getDimensionSize--) | ระบุขนาดของพื้นที่สไลด์ (ความกว้างเมื่อเป็นลูกของ RestoredTop, ความสูงเมื่อเป็นลูกของ RestoredLeft). |
| [setDimensionSize(float value)](#setDimensionSize-float-) | ระบุขนาดของพื้นที่สไลด์ (ความกว้างเมื่อเป็นลูกของ RestoredTop, ความสูงเมื่อเป็นลูกของ RestoredLeft). |
| [getAutoAdjust()](#getAutoAdjust--) | ระบุว่าขนาดของพื้นที่เนื้อหาข้างควรชดเชยขนาดใหม่เมื่อเปลี่ยนขนาดหน้าต่างที่บรรจุมุมมองภายในแอปพลิเคชัน อ่าน/เขียน boolean. |
| [setAutoAdjust(boolean value)](#setAutoAdjust-boolean-) | ระบุว่าขนาดของพื้นที่เนื้อหาข้างควรชดเชยขนาดใหม่เมื่อเปลี่ยนขนาดหน้าต่างที่บรรจุมุมมองภายในแอปพลิเคชัน อ่าน/เขียน boolean. |
### getDimensionSize() {#getDimensionSize--}
```
public abstract float getDimensionSize()
```

ระบุขนาดของพื้นที่สไลด์ (ความกว้างเมื่อเป็นลูกของ RestoredTop, ความสูงเมื่อเป็นลูกของ RestoredLeft). อ่าน/เขียน float.

**Returns:**
float
### setDimensionSize(float value) {#setDimensionSize-float-}
```
public abstract void setDimensionSize(float value)
```

ระบุขนาดของพื้นที่สไลด์ (ความกว้างเมื่อเป็นลูกของ RestoredTop, ความสูงเมื่อเป็นลูกของ RestoredLeft). อ่าน/เขียน float.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getAutoAdjust() {#getAutoAdjust--}
```
public abstract boolean getAutoAdjust()
```

ระบุว่าขนาดของพื้นที่เนื้อหาข้างควรชดเชยขนาดใหม่เมื่อเปลี่ยนขนาดหน้าต่างที่บรรจุมุมมองภายในแอปพลิเคชัน อ่าน/เขียน boolean.

**Returns:**
boolean
### setAutoAdjust(boolean value) {#setAutoAdjust-boolean-}
```
public abstract void setAutoAdjust(boolean value)
```

ระบุว่าขนาดของพื้นที่เนื้อหาข้างควรชดเชยขนาดใหม่เมื่อเปลี่ยนขนาดหน้าต่างที่บรรจุมุมมองภายในแอปพลิเคชัน อ่าน/เขียน boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |