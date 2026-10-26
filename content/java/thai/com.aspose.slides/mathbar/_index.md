---
title: MathBar
second_title: Aspose.Slides สำหรับ Java API Reference
description: กำหนดฟังก์ชันบาร์ที่ประกอบด้วยอาร์กิวเมนต์ฐานและเส้นเหนือหรือเส้นใต้
type: docs
url: /th/com.aspose.slides/mathbar/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**ทุกอินเทอร์เฟซที่ทำให้เป็นจริง:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

กำหนดฟังก์ชันบาร์ ที่ประกอบด้วยอาร์กิวเมนต์ฐานและเส้นเหนือหรือเส้นใต้

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | เริ่มต้น MathBar ด้วย overbar (ตำแหน่งบน) |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | เริ่มต้น MathBar ด้วยตำแหน่งที่ระบุ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getPosition()](#getPosition--) | ตำแหน่งของบรรทัดบาร์ |
| [setPosition(int value)](#setPosition-int-) | ตำแหน่งของบรรทัดบาร์ |
| [getChildren()](#getChildren--) | ดึงเอาองค์ประกอบลูก |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```

เริ่มต้น MathBar ด้วย overbar (ตำแหน่งบน)

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบฐานที่บาร์ถูกประยุกต์ใช้ |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```

เริ่มต้น MathBar ด้วยตำแหน่งที่ระบุ

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบฐานที่บาร์ถูกประยุกต์ใช้ |
| position | int | ตำแหน่งของบรรทัดบาร์ |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

ตำแหน่งของบรรทัดบาร์ ค่าเริ่มต้น: บน

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**คืนค่า:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

ตำแหน่งของบรรทัดบาร์ ค่าเริ่มต้น: บน

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

ดึงเอาองค์ประกอบลูก

**คืนค่า:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**คืนค่า:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps