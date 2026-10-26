---
title: MathBorderBox
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: วาดกรอบสี่เหลี่ยมหรือกรอบรูปแบบอื่นรอบ IMathElement.
type: docs
url: /th/com.aspose.slides/mathborderbox/
---
**การสืบทอด:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**  
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

วาดกรอบสี่เหลี่ยมหรือกรอบรูปแบบอื่นรอบ ๆ IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | สร้าง MathBorderBox element พร้อมกรอบสี่เหลี่ยม |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | สร้าง MathBorderBox element |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getHideTop()](#getHideTop--) | ซ่อนขอบด้านบน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านบนของกล่องกรอบ |
| [setHideTop(boolean value)](#setHideTop-boolean-) | ซ่อนขอบด้านบน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านบนของกล่องกรอบ |
| [getHideBottom()](#getHideBottom--) | ซ่อนขอบด้านล่าง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านล่างของกล่องกรอบ |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | ซ่อนขอบด้านล่าง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านล่างของกล่องกรอบ |
| [getHideLeft()](#getHideLeft--) | ซ่อนขอบด้านซ้าย (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านซ้ายของกล่องกรอบ |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | ซ่อนขอบด้านซ้าย (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านซ้ายของกล่องกรอบ |
| [getHideRight()](#getHideRight--) | ซ่อนขอบด้านขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านขวาของกล่องกรอบ |
| [setHideRight(boolean value)](#setHideRight-boolean-) | ซ่อนขอบด้านขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านขวาของกล่องกรอบ |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | เส้นขีดทับแนวนอน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดทับแนวนอน |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | เส้นขีดทับแนวนอน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดทับแนวนอน |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | เส้นขีดทับแนวตั้ง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดทับแนวตั้ง |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | เส้นขีดทับแนวตั้ง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดทับแนวตั้ง |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | เส้นขีดทับจากด้านล่างซ้ายไปด้านบนขวา (ค่าเริ่มต้นคือ false) |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | เส้นขีดทับจากด้านล่างซ้ายไปด้านบนขวา (ค่าเริ่มต้นคือ false) |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | เส้นขีดทับจากด้านบนซ้ายไปด้านล่างขวา (ค่าเริ่มต้นคือ false) |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | เส้นขีดทับจากด้านบนซ้ายไปด้านล่างขวา (ค่าเริ่มต้นคือ false) |
| [getChildren()](#getChildren--) | รับองค์ประกอบลูก |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

สร้าง MathBorderBox element พร้อมกรอบสี่เหลี่ยม

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบฐานที่กรอบจะถูกนำไปใช้ สามารถเป็น null ได้ |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

สร้าง MathBorderBox element

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบฐานที่กรอบจะถูกนำไปใช้ |
| hideTop | boolean | ซ่อนขอบด้านบน |
| hideBottom | boolean | ซ่อนขอบด้านล่าง |
| hideLeft | boolean | ซ่อนขอบด้านซ้าย |
| hideRight | boolean | ซ่อนขอบด้านขวา |
| strikethroughHorizontal | boolean | เส้นขีดทับแนวนอน |
| strikethroughVertical | boolean | เส้นขีดทับแนวตั้ง |
| strikethroughBottomLeftToTopRight | boolean | เส้นขีดทับจากด้านล่างซ้ายไปด้านบนขวา |
| strikethroughTopLeftToBottomRight | boolean | เส้นขีดทับจากด้านบนซ้ายไปด้านล่างขวา |

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

**ค่าที่คืนกลับ:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

ซ่อนขอบด้านบน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านบนของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**ค่าที่คืนกลับ:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

ซ่อนขอบด้านบน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านบนของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

ซ่อนขอบด้านล่าง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านล่างของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**ค่าที่คืนกลับ:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

ซ่อนขอบด้านล่าง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านล่างของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

ซ่อนขอบด้านซ้าย (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านซ้ายของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**ค่าที่คืนกลับ:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

ซ่อนขอบด้านซ้าย (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านซ้ายของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

ซ่อนขอบด้านขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านขวาของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**ค่าที่คืนกลับ:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

ซ่อนขอบด้านขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของขอบด้านขวาของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

เส้นขีดทับแนวนอน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดทับแนวนอน

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**ค่าที่คืนกลับ:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

เส้นขีดทับแนวนอน (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดทับแนวนอน

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

เส้นขีดทับแนวตั้ง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดทับแนวตั้ง

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**ค่าที่คืนกลับ:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

เส้นขีดทับแนวตั้ง (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นขีดทับแนวตั้ง

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

เส้นขีดทับจากด้านล่างซ้ายไปด้านบนขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นทแยงมุมจากมุมล่างซ้ายไปมุมบนขวาของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**ค่าที่คืนกลับ:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

เส้นขีดทับจากด้านล่างซ้ายไปด้านบนขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นทแยงมุมจากมุมล่างซ้ายไปมุมบนขวาของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

เส้นขีดทับจากด้านบนซ้ายไปด้านล่างขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นทแยงมุมจากมุมบนซ้ายไปมุมล่างขวาของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**ค่าที่คืนกลับ:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

เส้นขีดทับจากด้านบนซ้ายไปด้านล่างขวา (ค่าเริ่มต้นคือ false) - ระบุสถานะการซ่อนหรือแสดงของเส้นทแยงมุมจากมุมบนซ้ายไปมุมล่างขวาของกล่องกรอบ

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับองค์ประกอบลูก

**ค่าที่คืนกลับ:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**ค่าที่คืนกลับ:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps