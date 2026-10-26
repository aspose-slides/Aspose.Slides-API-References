---
title: MathBar
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ระบุฟังก์ชันบาร์ที่ประกอบด้วยอาร์กิวเมนต์ฐานและบาร์เหนือหรือบาร์ล่าง
type: docs
url: /th/com.aspose.slides/mathbar/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

ระบุฟังก์ชันบาร์ ซึ่งประกอบด้วยอาร์กิวเมนต์ฐานและบาร์เหนือหรือบาร์ล่าง

--------------------

> ```
> ตัวอย่าง:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | เริ่มต้น MathBar ด้วย overbar (ตำแหน่งบน) |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | เริ่มต้น MathBar ด้วยตำแหน่งที่ระบุ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getPosition()](#getPosition--) | ตำแหน่งของเส้นบาร์ |
| [setPosition(int value)](#setPosition-int-) | ตำแหน่งของเส้นบาร์ |
| [getChildren()](#getChildren--) | ดึงองค์ประกอบลูก |
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
| element | [IMathElement](../../com.aspose.slides/imathelement) | อิลีเมนต์ฐานที่บาร์ถูกนำไปใช้ |

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
| element | [IMathElement](../../com.aspose.slides/imathelement) | อิลีเมนต์ฐานที่บาร์ถูกนำไปใช้ |
| position | int | ตำแหน่งของเส้นบาร์ |

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

ตำแหน่งของเส้นบาร์ ค่าเริ่มต้น: บน

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

ตำแหน่งของเส้นบาร์ ค่าเริ่มต้น: บน

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

ดึงองค์ประกอบลูก

**คืนค่า:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**คืนค่า:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps