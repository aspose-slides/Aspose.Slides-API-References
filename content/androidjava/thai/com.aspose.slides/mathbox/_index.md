---
title: MathBox
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: ระบุการบรรจุกล่องตรรกะขององค์ประกอบคณิตศาสตร์.
type: docs
url: /th/com.aspose.slides/mathbox/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**ส่วนต่อประสานที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

ระบุการจัดกล่องตรรกะ (การบรรจุ) ขององค์ประกอบคณิตศาสตร์ ตัวอย่างเช่น วัตถุที่ถูกบรรจุสามารถทำหน้าที่เป็นอิมูเลเตอร์ของตัวดำเนินการที่มีหรือไม่มีจุดจัดแนว ทำหน้าที่เป็นจุดตัดบรรทัด หรือจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน ตัวอย่างเช่น ตัวดำเนินการ “==” ควรจะถูกบรรจุเพื่อป้องกันการตัดบรรทัด

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## คอนสตรัคเตอร์

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Initialises MathBox with the specified element as an argument |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getOperatorEmulator()](#getOperatorEmulator--) | อิมูเลเตอร์ตัวดำเนินการ. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | อิมูเลเตอร์ตัวดำเนินการ. |
| [getNoBreak()](#getNoBreak--) | No break คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องวัตถุ |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องวัตถุ |
| [getDifferential()](#getDifferential--) | Differential เมื่อเป็นจริง กรอบทำหน้าที่เป็นต่างอนุพันธ์ (เช่น \\ud835\\udc51\\ud835\\udc65 ในอินทิเกรนด์) และได้รับการจัดช่องว่างแนวนอนที่เหมาะสมสำหรับต่างอนุพันธ์ทางคณิตศาสตร์ |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential เมื่อเป็นจริง กรอบทำหน้าที่เป็นต่างอนุพันธ์ (เช่น \\ud835\\udc51\\ud835\\udc65 ในอินทิเกรนด์) และได้รับการจัดช่องว่างแนวนอนที่เหมาะสมสำหรับต่างอนุพันธ์ทางคณิตศาสตร์ |
| [getAlignmentPoint()](#getAlignmentPoint--) | เมื่อเป็นจริง อิมูเลเตอร์ตัวดำเนินการนี้ทำหน้าที่เป็นจุดจัดแนว; กล่าวคือ จุดจัดแนวที่กำหนดในสมการอื่น ๆ สามารถจัดแนวกับมันได้ |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | เมื่อเป็นจริง อิมูเลเตอร์ตัวดำเนินการนี้ทำหน้าที่เป็นจุดจัดแนว; กล่าวคือ จุดจัดแนวที่กำหนดในสมการอื่น ๆ สามารถจัดแนวกับมันได้ |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break ระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของอ็อบเจกต์ Box หรือไม่ เพื่อให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของอ็อบเจกต์ |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break ระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของอ็อบเจกต์ Box หรือไม่ เพื่อให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของอ็อบเจกต์ |
| [getChildren()](#getChildren--) | ดึงองค์ประกอบลูก |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักษรควบคุม |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```


Initialises MathBox with the specified element as an argument

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | องค์ประกอบฐานที่กล่องจะถูกนำไปใช้ สามารถเป็นค่า null ได้ |

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


อิมูเลเตอร์ตัวดำเนินการ. เมื่อเป็นจริง กล่องและเนื้อหาภายในทำงานเหมือนตัวดำเนินการเดียวและสืบทอดคุณสมบัติของตัวดำเนินการ ซึ่งหมายความว่าตัวอักษรสามารถทำหน้าที่เป็นจุดตัดบรรทัดและจัดแนวกับตัวดำเนินการอื่น ๆ ได้ อิมูเลเตอร์ตัวดำเนินการมักใช้เมื่อ Glyph หนึ่งหรือหลายตัวรวมกันเป็นตัวดำเนินการ เช่น ‘==’. ค่าเริ่มต้น: false

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


อิมูเลเตอร์ตัวดำเนินการ. เมื่อเป็นจริง กล่องและเนื้อหาภายในทำงานเหมือนตัวดำเนินการเดียวและสืบทอดคุณสมบัติของตัวดำเนินการ ซึ่งหมายความว่าตัวอักษรสามารถทำหน้าที่เป็นจุดตัดบรรทัดและจัดแนวกับตัวดำเนินการอื่น ๆ ได้ อิมูเลเตอร์ตัวดำเนินการมักใช้เมื่อ Glyph หนึ่งหรือหลายตัวรวมกันเป็นตัวดำเนินการ เช่น ‘==’. ค่าเริ่มต้น: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```


No break คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องวัตถุ เมื่อเป็นจริง จะไม่มีการตัดบรรทัดภายในกล่อง ซึ่งอาจสำคัญสำหรับอิมูเลเตอร์ตัวดำเนินการที่ประกอบด้วยตัวดำเนินการไบนารีหลายตัว เมื่อไม่ได้ระบุคุณสมบัตินี้ การตัดบรรทัดอาจเกิดขึ้นภายในกล่อง ค่าเริ่มต้น: true

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


No break คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บบนกล่องวัตถุ เมื่อเป็นจริง จะไม่มีการตัดบรรทัดภายในกล่อง ซึ่งอาจสำคัญสำหรับอิมูเลเตอร์ตัวดำเนินการที่ประกอบด้วยตัวดำเนินการไบนารีหลายตัว เมื่อไม่ได้ระบุคุณสมบัตินี้ การตัดบรรทัดอาจเกิดขึ้นภายในกล่อง ค่าเริ่มต้น: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```


Differential เมื่อเป็นจริง กรอบทำหน้าที่เป็นต่างอนุพันธ์ (เช่น \\ud835\\udc51\\ud835\\udc65 ในอินทิเกรนด์) และได้รับการจัดช่องว่างแนวนอนที่เหมาะสมสำหรับต่างอนุพันธ์ทางคณิตศาสตร์ ค่าเริ่มต้น: false

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


Differential เมื่อเป็นจริง กรอบทำหน้าที่เป็นต่างอนุพันธ์ (เช่น \\ud835\\udc51\\ud835\\udc65 ในอินทิเกรนด์) และได้รับการจัดช่องว่างแนวนอนที่เหมาะสมสำหรับต่างอนุพันธ์ทางคณิตศาสตร์ ค่าเริ่มต้น: false

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```


เมื่อเป็นจริง อิมูเลเตอร์ตัวดำเนินการนี้ทำหน้าที่เป็นจุดจัดแนว; กล่าวคือ จุดจัดแนวที่กำหนดในสมการอื่น ๆ สามารถจัดแนวกับมันได้ ค่าเริ่มต้น: false

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


เมื่อเป็นจริง อิมูเลเตอร์ตัวดำเนินการนี้ทำหน้าที่เป็นจุดจัดแนว; กล่าวคือ จุดจัดแนวที่กำหนดในสมการอื่น ๆ สามารถจัดแนวกับมันได้ ค่าเริ่มต้น: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```


Explicit break ระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของอ็อบเจกต์ Box หรือไม่ เพื่อให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของอ็อบเจกต์ กล่อง นอกจากนี้ยังระบุหมายเลขของตัวดำเนินการบนบรรทัดข้อความคณิตศาสตร์ก่อนหน้าที่จะใช้เป็นจุดจัดแนวสำหรับบรรทัดข้อความคณิตศาสตร์ปัจจุบัน ค่าเป็นไปได้: 1..255 ค่าเริ่มต้น: 0 (ไม่มีการตัดบรรทัดแบบชัดเจน)

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


Explicit break ระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของอ็อบเจกต์ Box หรือไม่ เพื่อให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของอ็อบเจกต์ กล่อง นอกจากนี้ยังระบุหมายเลขของตัวดำเนินการบนบรรทัดข้อความคณิตศาสตร์ก่อนหน้าที่จะใช้เป็นจุดจัดแนวสำหรับบรรทัดข้อความคณิตศาสตร์ปัจจุบัน ค่าเป็นไปได้: 1..255 ค่าเริ่มต้น: 0 (ไม่มีการตัดบรรทัดแบบชัดเจน)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | byte |  |

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