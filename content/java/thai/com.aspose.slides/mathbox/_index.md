---
title: MathBox
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ระบุการบรรจุกล่องเชิงตรรกะของอีลิเมนต์ทางคณิตศาสตร์.
type: docs
url: /th/com.aspose.slides/mathbox/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

กำหนดการบรรจุกล่องเชิงตรรกะ (packaging) ของอีลิเมนต์ทางคณิตศาสตร์ ตัวอย่างเช่น อ็อบเจกต์ที่บรรจุกล่องสามารถทำหน้าที่เป็น operator emulator ที่มีหรือไม่มีจุด alignment, ทำหน้าที่เป็นจุดตัดบรรทัด, หรือถูกจัดกลุ่มเพื่อไม่ให้เกิดการตัดบรรทัดภายใน ตัวอย่างเช่น ตัวดำเนินการ "==" ควรจะถูกบรรจุกล่องเพื่อป้องกันการตัดบรรทัด.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | เริ่มต้น MathBox ด้วยอีลิเมนต์ที่ระบุเป็นอาร์กิวเมนต์ |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getOperatorEmulator()](#getOperatorEmulator--) | Operator Emulator. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Operator Emulator. |
| [getNoBreak()](#getNoBreak--) | No break คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องอ็อบเจกต์ เมื่อเป็นจริง จะไม่มีการตัดบรรทัดภายในกล่อง ซึ่งอาจสำคัญสำหรับ operator emulators ที่ประกอบด้วยตัวดำเนินการไบนารีมากกว่าหนึ่งตัว เมื่อไม่ได้ระบุอีลิเมนต์นี้ การตัดบรรทัดสามารถเกิดขึ้นภายในกล่องได้ ค่าเริ่มต้น: true |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องอ็อบเจกต์ เมื่อเป็นจริง จะไม่มีการตัดบรรทัดภายในกล่อง ซึ่งอาจสำคัญสำหรับ operator emulators ที่ประกอบด้วยตัวดำเนินการไบนารีมากกว่าหนึ่งตัว เมื่อไม่ได้ระบุอีลิเมนต์นี้ การตัดบรรทัดสามารถเกิดขึ้นภายในกล่องได้ ค่าเริ่มต้น: true |
| [getDifferential()](#getDifferential--) | Differential เมื่อเป็นจริง, กล่องทำหน้าที่เป็น differential (เช่น \ud835\udc51\ud835\udc65 ในอินเทเกรนด์) และได้รับการจัดระยะห่างแนวนอนที่เหมาะสมสำหรับ differential ทางคณิตศาสตร์ ค่าเริ่มต้น: false |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential เมื่อเป็นจริง, กล่องทำหน้าที่เป็น differential (เช่น \ud835\udc51\ud835\udc65 ในอินเทเกรนด์) และได้รับการจัดระยะห่างแนวนอนที่เหมาะสมสำหรับ differential ทางคณิตศาสตร์ ค่าเริ่มต้น: false |
| [getAlignmentPoint()](#getAlignmentPoint--) | เมื่อเป็นจริง, this operator emulator ทำหน้าที่เป็น alignment point; นั่นหมายความว่าจุด alignment ที่กำหนดในสมการอื่น ๆ สามารถจัดตำแหน่งให้ตรงกับมันได้ ค่าเริ่มต้น: false |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | เมื่อเป็นจริง, this operator emulator ทำหน้าที่เป็น alignment point; นั่นหมายความว่าจุด alignment ที่กำหนดในสมการอื่น ๆ สามารถจัดตำแหน่งให้ตรงกับมันได้ ค่าเริ่มต้น: false |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break ระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของอ็อบเจกต์ Box หรือไม่ ซึ่งทำให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของอ็อบเจกต์นี้ ระบุจำนวนของตัวดำเนินการในบรรทัดก่อนหน้าของข้อความคณิตศาสตร์ที่จะใช้เป็น alignment point สำหรับบรรทัดปัจจุบัน ค่าที่เป็นไปได้: 1..255 ค่าเริ่มต้น: 0 (ไม่มีการตัดบรรทัดโดยชัดเจน) |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break ระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของอ็อบเจกต์ Box หรือไม่ ซึ่งทำให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของอ็อบเจกต์นี้ ระบุจำนวนของตัวดำเนินการในบรรทัดก่อนหน้าของข้อความคณิตศาสตร์ที่จะใช้เป็น alignment point สำหรับบรรทัดปัจจุบัน ค่าที่เป็นไปได้: 1..255 ค่าเริ่มต้น: 0 (ไม่มีการตัดบรรทัดโดยชัดเจน) |
| [getChildren()](#getChildren--) | ดึงอีลิเมนต์ลูก |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักขระควบคุม |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

เริ่มต้น MathBox ด้วยอีลิเมนต์ที่ระบุเป็นอาร์กิวเมนต์

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | อีลิเมนต์ฐานที่ใช้กับกล่องนี้ สามารถเป็น null ได้ |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```

Operator Emulator. เมื่อเป็นจริง, กล่องและเนื้อหาของมันทำหน้าที่เป็น operator เดียวและสืบทอดคุณสมบัติของ operator ซึ่งหมายความว่าตัวอักษรสามารถทำหน้าที่เป็นจุดตัดบรรทัดและสามารถจัดตำแหน่งให้ตรงกับ operator อื่น ๆ ได้ Operator Emulators มักใช้เมื่อหนึ่งหรือหลาย glyph รวมกันเป็น operator เช่น '==' ค่าเริ่มต้น: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```


**คืนค่า:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```

Operator Emulator. เมื่อเป็นจริง, กล่องและเนื้อหาของมันทำหน้าที่เป็น operator เดียวและสืบทอดคุณสมบัติของ operator ซึ่งหมายความว่าตัวอักษรสามารถทำหน้าที่เป็นจุดตัดบรรทัดและสามารถจัดตำแหน่งให้ตรงกับ operator อื่น ๆ ได้ Operator Emulators มักใช้เมื่อหนึ่งหรือหลาย glyph รวมกันเป็น operator เช่น '==' ค่าเริ่มต้น: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```

No break คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องอ็อบเจกต์ เมื่อเป็นจริง จะไม่มีการตัดบรรทัดภายในกล่อง ซึ่งอาจสำคัญสำหรับ operator emulators ที่ประกอบด้วยตัวดำเนินการไบนารีมากกว่าหนึ่งตัว เมื่อไม่ได้ระบุอีลิเมนต์นี้ การตัดบรรทัดสามารถเกิดขึ้นภายในกล่องได้ ค่าเริ่มต้น: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**คืนค่า:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```

No break คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องอ็อบเจกต์ เมื่อเป็นจริง จะไม่มีการตัดบรรทัดภายในกล่อง ซึ่งอาจสำคัญสำหรับ operator emulators ที่ประกอบด้วยตัวดำเนินการไบนารีมากกว่าหนึ่งตัว เมื่อไม่ได้ระบุอีลิเมนต์นี้ การตัดบรรทัดสามารถเกิดขึ้นภายในกล่องได้ ค่าเริ่มต้น: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```

Differential เมื่อเป็นจริง, กล่องทำหน้าที่เป็น differential (เช่น \ud835\udc51\ud835\udc65 ในอินเทเกรนด์) และได้รับการจัดระยะห่างแนวนอนที่เหมาะสมสำหรับ differential ทางคณิตศาสตร์ ค่าเริ่มต้น: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**คืนค่า:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```

Differential เมื่อเป็นจริง, กล่องทำหน้าที่เป็น differential (เช่น \ud835\udc51\ud835\udc65 ในอินเทเกรนด์) และได้รับการจัดระยะห่างแนวนอนที่เหมาะสมสำหรับ differential ทางคณิตศาสตร์ ค่าเริ่มต้น: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```

เมื่อเป็นจริง, this operator emulator ทำหน้าที่เป็น alignment point; นั่นหมายความว่าจุด alignment ที่กำหนดในสมการอื่น ๆ สามารถจัดตำแหน่งให้ตรงกับมันได้ ค่าเริ่มต้น: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**คืนค่า:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```

เมื่อเป็นจริง, this operator emulator ทำหน้าที่เป็น alignment point; นั่นหมายความว่าจุด alignment ที่กำหนดในสมการอื่น ๆ สามารถจัดตำแหน่งให้ตรงกับมันได้ ค่าเริ่มต้น: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```

Explicit break ระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของอ็อบเจกต์ Box หรือไม่ ซึ่งทำให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของอ็อบเจกต์นี้ ระบุจำนวนของตัวดำเนินการในบรรทัดก่อนหน้าของข้อความคณิตศาสตร์ที่จะใช้เป็น alignment point สำหรับบรรทัดปัจจุบัน ค่าที่เป็นไปได้: 1..255 ค่าเริ่มต้น: 0 (ไม่มีการตัดบรรทัดโดยชัดเจน)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**คืนค่า:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```

Explicit break ระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของอ็อบเจกต์ Box หรือไม่ ซึ่งทำให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของอ็อบเจกต์นี้ ระบุจำนวนของตัวดำเนินการในบรรทัดก่อนหน้าของข้อความคณิตศาสตร์ที่จะใช้เป็น alignment point สำหรับบรรทัดปัจจุบัน ค่าที่เป็นไปได้: 1..255 ค่าเริ่มต้น: 0 (ไม่มีการตัดบรรทัดโดยชัดเจน)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับอีลิเมนต์ลูก

**คืนค่า:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**คืนค่า:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps