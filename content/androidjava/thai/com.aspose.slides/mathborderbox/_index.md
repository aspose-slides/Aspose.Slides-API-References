---
title: MathBorderBox
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API Java
description: วาดสี่เหลี่ยมหรือเส้นขอบรูปแบบอื่น ๆ รอบ IMathElement.
type: docs
url: /th/com.aspose.slides/mathborderbox/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**  
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

วาดเส้นขอบสี่เหลี่ยมหรือเส้นขอบอื่น ๆ รอบ IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | สร้างอ็อบเจ็กต์ MathBorderBox พร้อมเส้นขอบสี่เหลี่ยม |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | สร้างอ็อบเจ็กต์ MathBorderBox |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getHideTop()](#getHideTop--) | ซ่อนขอบบน (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบบนของกล่องขอบ |
| [setHideTop(boolean value)](#setHideTop-boolean-) | ซ่อนขอบบน (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบบนของกล่องขอบ |
| [getHideBottom()](#getHideBottom--) | ซ่อนขอบล่าง (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบล่างของกล่องขอบ |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | ซ่อนขอบล่าง (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบล่างของกล่องขอบ |
| [getHideLeft()](#getHideLeft--) | ซ่อนขอบซ้าย (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบซ้ายของกล่องขอบ |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | ซ่อนขอบซ้าย (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบซ้ายของกล่องขอบ |
| [getHideRight()](#getHideRight--) | ซ่อนขอบขวา (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบขวาของกล่องขอบ |
| [setHideRight(boolean value)](#setHideRight-boolean-) | ซ่อนขอบขวา (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบขวาของกล่องขอบ |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | ขีดฆ่วงแนวนอน (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของเส้นขีดฆ่วงแนวนอน |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | ขีดฆ่วงแนวนอน (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของเส้นขีดฆ่วงแนวนอน |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | ขีดฆ่วงแนวตั้ง (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของเส้นขีดฆ่วงแนวตั้ง |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | ขีดฆ่วงแนวตั้ง (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของเส้นขีดฆ่วงแนวตั้ง |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | ขีดฆ่วงจากด้านล่างซ้ายไปด้านบนขวา (ค่าเริ่มต้นเป็น false) |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | ขีดฆ่วงจากด้านล่างซ้ายไปด้านบนขวา (ค่าเริ่มต้นเป็น false) |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | ขีดฆ่วงจากด้านบนซ้ายไปด้านล่างขวา (ค่าเริ่มต้นเป็น false) |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | ขีดฆ่วงจากด้านบนซ้ายไปด้านล่างขวา (ค่าเริ่มต้นเป็น false) |
| [getChildren()](#getChildren--) | ดึงเอาอิลิเมนต์ลูก |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |

### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

สร้างอ็อบเจ็กต์ MathBorderBox พร้อมเส้นขอบสี่เหลี่ยม

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | อิลิเมนต์ฐานที่ขอบกล่องจะถูกนำไปใช้ สามารถเป็น null ได้ |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

สร้างอ็อบเจ็กต์ MathBorderBox

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | อิลิเมนต์ฐานที่ขอบกล่องจะถูกนำไปใช้ |
| hideTop | boolean | ซ่อนขอบบน |
| hideBottom | boolean | ซ่อนขอบล่าง |
| hideLeft | boolean | ซ่อนขอบซ้าย |
| hideRight | boolean | ซ่อนขอบขวา |
| strikethroughHorizontal | boolean | ขีดฆ่วงแนวนอน |
| strikethroughVertical | boolean | ขีดฆ่วงแนวตั้ง |
| strikethroughBottomLeftToTopRight | boolean | ขีดฆ่วงจากด้านล่างซ้ายไปด้านบนขวา |
| strikethroughTopLeftToBottomRight | boolean | ขีดฆ่วงจากด้านบนซ้ายไปด้านล่างขวา |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)

### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

ซ่อนขอบบน (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบบนของกล่องขอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**คืนค่า:**
boolean

### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

ซ่อนขอบบน (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบบนของกล่องขอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

ซ่อนขอบล่าง (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบล่างของกล่องขอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**คืนค่า:**
boolean

### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

ซ่อนขอบล่าง (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบล่างของกล่องขอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

ซ่อนขอบซ้าย (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบซ้ายของกล่องขอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**คืนค่า:**
boolean

### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

ซ่อนขอบซ้าย (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบซ้ายของกล่องขอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

ซ่อนขอบขวา (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบขวาของกล่องขอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**คืนค่า:**
boolean

### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

ซ่อนขอบขวา (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของขอบขวาของกล่องขอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

ขีดฆ่วงแนวนอน (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของเส้นขีดฆ่วงแนวนอน

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**คืนค่า:**
boolean

### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

ขีดฆ่วงแนวนอน (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของเส้นขีดฆ่วงแนวนอน

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

ขีดฆ่วงแนวตั้ง (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของเส้นขีดฆ่วงแนวตั้ง

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**คืนค่า:**
boolean

### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

ขีดฆ่าว

แนวตั้ง (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของเส้นขีดฆ่วงแนวตั้ง

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

ขีดฆ่วงจากด้านล่างซ้ายไปด้านบนขวา (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของเส้นขีดฆ่าวแนวทแยงจากมุมล่างซ้ายไปมุมบนขวาของกล่องขอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**คืนค่า:**
boolean

### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

ขีดฆ่วงจากด้านล่างซ้ายไปด้านบนขวา (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของเส้นขีดฆ่าวแนวทแยงจากมุมล่างซ้ายไปมุมบนขวาของกล่องขอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

ขีดฆ่วงจากด้านบนซ้ายไปด้านล่างขวา (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของเส้นขีดฆ่าวแนวทแยงจากมุมบนซ้ายไปมุมล่างขวาของกล่องขอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**คืนค่า:**
boolean

### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

ขีดฆ่วงจากด้านบนซ้ายไปด้านล่างขวา (ค่าเริ่มต้นเป็น false) - ระบุสถานะที่ซ่อนหรือแสดงของเส้นขีดฆ่าวแนวทแยงจากมุมบนซ้ายไปมุมล่างขวาของกล่องขอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

ดึงเอาอิลิเมนต์ลูก

**คืนค่า:**
com.aspose.slides.IMathElement[]

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**คืนค่า:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps