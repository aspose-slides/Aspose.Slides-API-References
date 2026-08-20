---
title: IMathBox
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ระบุการบรรจูเชิงตรรกะขององค์ประกอบทางคณิตศาสตร์
type: docs
url: /th/com.aspose.slides/imathbox/
---
**ทั้งหมดของ Interface ที่ทำการ Implement:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

ระบุการบรรจุ (packaging) เชิงตรรกะขององค์ประกอบทางคณิตศาสตร์ ตัวอย่างเช่น วัตถุที่ถูกบรรจุสามารถทำหน้าที่เป็นตัวจำลองตัวดำเนินการที่มีหรือไม่มีจุดจัดแนว ทำหน้าที่เป็นจุดการตัดบรรทัด หรือถูกจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน ตัวอย่างเช่น ตัวดำเนินการ "==" ควรจะถูกบรรจุเพื่อป้องกันการตัดบรรทัด

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์พื้นฐาน |
| [getOperatorEmulator()](#getOperatorEmulator--) | ตัวจำลองตัวดำเนินการ. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | ตัวจำลองตัวดำเนินการ. |
| [getNoBreak()](#getNoBreak--) | ไม่มีการตัดบรรทัด. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | ไม่มีการตัดบรรทัด. |
| [getDifferential()](#getDifferential--) | เชิงอนุพันธ์. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | เชิงอนุพันธ์. |
| [getAlignmentPoint()](#getAlignmentPoint--) | เมื่อเป็น true, ตัวจำลองตัวดำเนินการนี้ทำหน้าที่เป็นจุดจัดแนว; นั่นคือ จุดจัดแนวที่กำหนดไว้ในสมการอื่นสามารถจัดแนวกับมันได้. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | เมื่อเป็น true, ตัวจำลองตัวดำเนินการนี้ทำหน้าที่เป็นจุดจัดแนว; นั่นคือ จุดจัดแนวที่กำหนดไว้ในสมการอื่นสามารถจัดแนวกับมันได้. |
| [getExplicitBreak()](#getExplicitBreak--) | การตัดบรรทัดแบบชัดเจนระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของวัตถุ Box หรือไม่, ทำให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของวัตถุ box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | การตัดบรรทัดแบบชัดเจนระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของวัตถุ Box หรือไม่, ทำให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของวัตถุ box. |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

อาร์กิวเมนต์พื้นฐาน

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

ตัวจำลองตัวดำเนินการ. เมื่อเป็น true, กล่องและเนื้อหาในนั้นทำงานเหมือนตัวดำเนินการเดียวและสืบทอดคุณสมบัติของตัวดำเนินการ สิ่งนี้หมายความว่า ตัวอักษรสามารถทำหน้าที่เป็นจุดสำหรับการตัดบรรทัดและสามารถจัดแนวกับตัวดำเนินการอื่น ๆ ตัวจำลองตัวดำเนินการมักใช้เมื่อ glyph หนึ่งหรือหลายตัวรวมกันเป็นตัวดำเนินการ เช่น '==' ค่าเริ่มต้น: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**คืนค่า:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

ตัวจำลองตัวดำเนินการ. เมื่อเป็น true, กล่องและเนื้อหาในนั้นทำงานเหมือนตัวดำเนินการเดียวและสืบทอดคุณสมบัติของตัวดำเนินการ สิ่งนี้หมายความว่า ตัวอักษรสามารถทำหน้าที่เป็นจุดสำหรับการตัดบรรทัดและสามารถจัดแนวกับตัวดำเนินการอื่น ๆ ตัวจำลองตัวดำเนินการมักใช้เมื่อ glyph หนึ่งหรือหลายตัวรวมกันเป็นตัวดำเนินการ เช่น '==' ค่าเริ่มต้น: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

ไม่มีการตัดบรรทัด. คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องวัตถุ เมื่อเป็น true, จะไม่มีการตัดบรรทัดภายในกล่อง ซึ่งอาจสำคัญสำหรับตัวจำลองตัวดำเนินการที่ประกอบด้วยตัวดำเนินการแบบไบนารีมากกว่าหนึ่งตัว เมื่อไม่ได้ระบุคุณสมบัตินี้ การตัดบรรทัดอาจเกิดขึ้นภายในกล่อง ค่าเริ่มต้น: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**คืนค่า:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

ไม่มีการตัดบรรทัด. คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องวัตถุ เมื่อเป็น true, จะไม่มีการตัดบรรทัดภายในกล่อง ซึ่งอาจสำคัญสำหรับตัวจำลองตัวดำเนินการที่ประกอบด้วยตัวดำเนินการแบบไบนารีมากกว่าหนึ่งตัว เมื่อไม่ได้ระบุคุณสมบัตินี้ การตัดบรรทัดอาจเกิดขึ้นภายในกล่อง ค่าเริ่มต้น: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

เชิงอนุพันธ์. เมื่อเป็น true, กล่องทำหน้าที่เป็นเชิงอนุพันธ์ (เช่น \\ud835\\udc51\\ud835\\udc65 ในตัวอินทิเกรต) และรับการจัดวางระยะห่างแนวนอนที่เหมาะสมสำหรับเชิงอนุพันธ์ทางคณิตศาสตร์ ค่าเริ่มต้น: false

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
public abstract void setDifferential(boolean value)
```

เชิงอนุพันธ์. เมื่อเป็น true, กล่องทำหน้าที่เป็นเชิงอนุพันธ์ (เช่น \\ud835\\udc51\\ud835\\udc65 ในตัวอินทิเกรต) และรับการจัดวางระยะห่างแนวนอนที่เหมาะสมสำหรับเชิงอนุพันธ์ทางคณิตศาสตร์ ค่าเริ่มต้น: false

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
public abstract boolean getAlignmentPoint()
```

เมื่อเป็น true, ตัวจำลองตัวดำเนินการนี้ทำหน้าที่เป็นจุดจัดแนว; นั่นคือ จุดจัดแนวที่กำหนดไว้ในสมการอื่นสามารถจัดแนวกับมันได้. ค่าเริ่มต้น: false

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
public abstract void setAlignmentPoint(boolean value)
```

เมื่อเป็น true, ตัวจำลองตัวดำเนินการนี้ทำหน้าที่เป็นจุดจัดแนว; นั่นคือ จุดจัดแนวที่กำหนดไว้ในสมการอื่นสามารถจัดแนวกับมันได้. ค่าเริ่มต้น: false

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
public abstract byte getExplicitBreak()
```

การตัดบรรทัดแบบชัดเจนระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของวัตถุ Box หรือไม่, ทำให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของวัตถุ box. ระบุหมายเลขของตัวดำเนินการบนบรรทัดก่อนหน้าของข้อความคณิตศาสตร์ที่ควรใช้เป็นจุดจัดแนวสำหรับบรรทัดปัจจุบันของข้อความคณิตศาสตร์ ค่าที่เป็นไปได้: 1..255 ค่าเริ่มต้น: 0 (ไม่มีการตัดบรรทัดแบบชัดเจน)

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
public abstract void setExplicitBreak(byte value)
```

การตัดบรรทัดแบบชัดเจนระบุว่ามีการตัดบรรทัดที่จุดเริ่มต้นของวัตถุ Box หรือไม่, ทำให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของวัตถุ box. ระบุหมายเลขของตัวดำเนินการบนบรรทัดก่อนหน้าของข้อความคณิตศาสตร์ที่ควรใช้เป็นจุดจัดแนวสำหรับบรรทัดปัจจุบันของข้อความคณิตศาสตร์ ค่าที่เป็นไปได้: 1..255 ค่าเริ่มต้น: 0 (ไม่มีการตัดบรรทัดแบบชัดเจน)

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