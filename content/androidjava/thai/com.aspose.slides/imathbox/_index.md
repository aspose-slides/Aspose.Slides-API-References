---
title: IMathBox
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง Java API
description: ระบุการบรรจุกล่องตรรกะขององค์ประกอบทางคณิตศาสตร์.
type: docs
url: /th/com.aspose.slides/imathbox/
---
**ทั้งหมดที่ทำหน้าที่เป็น Interface:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

ระบุการกล่องตรรกะ (การบรรจุ) ขององค์ประกอบทางคณิตศาสตร์ ตัวอย่างเช่น วัตถุที่อยู่ในกล่องสามารถทำหน้าที่เป็นตัวจำลองโอเปอเรเตอร์พร้อมหรือไม่มีจุดจัดตำแหน่ง ทำหน้าที่เป็นจุดตัดบรรทัด หรือถูกจัดกลุ่มเพื่อไม่ให้มีการตัดบรรทัดภายใน ตัวอย่างเช่น ตัวดำเนินการ "==" ควรจะถูกใส่ในกล่องเพื่อป้องกันการตัดบรรทัด

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getOperatorEmulator()](#getOperatorEmulator--) | ตัวจำลองโอเปอเรเตอร์. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | ตัวจำลองโอเปอเรเตอร์. |
| [getNoBreak()](#getNoBreak--) | ไม่มีการตัดบรรทัด. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | ไม่มีการตัดบรรทัด. |
| [getDifferential()](#getDifferential--) | เชิงอนุพันธ์. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | เชิงอนุพันธ์. |
| [getAlignmentPoint()](#getAlignmentPoint--) | เมื่อเป็นจริง ตัวจำลองโอเปอเรเตอร์นี้ทำหน้าที่เป็นจุดจัดตำแหน่ง; นั่นคือ จุดจัดตำแหน่งที่กำหนดในสมการอื่น ๆ สามารถจัดตำแหน่งให้ตรงกับมันได้. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | เมื่อเป็นจริง ตัวจำลองโอเปอเรเตอร์นี้ทำหน้าที่เป็นจุดจัดตำแหน่ง; นั่นคือ จุดจัดตำแหน่งที่กำหนดในสมการอื่น ๆ สามารถจัดตำแหน่งให้ตรงกับมันได้. |
| [getExplicitBreak()](#getExplicitBreak--) | การตัดบรรทัดแบบกำหนดล่วงหน้ากำหนดว่ามีการตัดบรรทัดที่จุดเริ่มต้นของวัตถุ Box หรือไม่ ซึ่งทำให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของวัตถุ Box |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | การตัดบรรทัดแบบกำหนดล่วงหน้ากำหนดว่ามีการตัดบรรทัดที่จุดเริ่มต้นของวัตถุ Box หรือไม่ ซึ่งทำให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของวัตถุ Box |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

อาร์กิวเมนต์ฐาน

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

ตัวจำลองโอเปอเรเตอร์. เมื่อเป็นจริง กล่องและเนื้อหาของมันทำงานเป็นโอเปอร์เรเตอร์เดียวและสืบทอดคุณสมบัติของโอเปอเรเตอร์ ซึ่งหมายความว่า ตัวอักษรอาจทำหน้าที่เป็นจุดตัดบรรทัดและสามารถจัดตำแหน่งกับโอเปอเรเตอร์อื่น ๆ ได้ ตัวจำลองโอเปอเรเตอร์มักใช้เมื่อหนึ่งหรือหลาย glyph รวมกันเป็นโอเปอเรเตอร์ เช่น '==' ค่าเริ่มต้น: false

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

ตัวจำลองโอเปอเรเตอร์. เมื่อเป็นจริง กล่องและเนื้อหาของมันทำงานเป็นโอเปอร์เรเตอร์เดียวและสืบทอดคุณสมบัติของโอเปอเรเตอร์ ซึ่งหมายความว่า ตัวอักษรอาจทำหน้าที่เป็นจุดตัดบรรทัดและสามารถจัดตำแหน่งกับโอเปอเรเตอร์อื่น ๆ ได้ ตัวจำลองโอเปอเรเตอร์มักใช้เมื่อหนึ่งหรือหลาย glyph รวมกันเป็นโอเปอเรเตอร์ เช่น '==' ค่าเริ่มต้น: false

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

ไม่มีการตัดบรรทัด. คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องวัตถุ เมื่อเป็นจริง จะไม่มีการตัดบรรทัดภายในกล่อง ซึ่งอาจสำคัญสำหรับตัวจำลองโอเปอเรเตอร์ที่ประกอบด้วยมากกว่าหนึ่งโอเปอเรเตอร์ไบนารี เมื่อไม่ได้ระบุองค์ประกอบนี้ การตัดบรรทัดอาจเกิดขึ้นภายในกล่อง ค่าเริ่มต้น: true

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

ไม่มีการตัดบรรทัด. คุณสมบัตินี้ระบุคุณสมบัติ "unbreakable" บนกล่องวัตถุ เมื่อเป็นจริง จะไม่มีการตัดบรรทัดภายในกล่อง ซึ่งอาจสำคัญสำหรับตัวจำลองโอเปอเรเตอร์ที่ประกอบด้วยมากกว่าหนึ่งโอเปอเรเตอร์ไบนารี เมื่อไม่ได้ระบุองค์ประกอบนี้ การตัดบรรทัดอาจเกิดขึ้นภายในกล่อง ค่าเริ่มต้น: true

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

เชิงอนุพันธ์. เมื่อเป็นจริง กล่องทำหน้าที่เป็นเชิงอนุพันธ์ (เช่น \\ud835\\udc51\\ud835\\udc65 ในอินทิกรัล) และได้รับการจัดช่องว่างแนวนอนที่เหมาะสมสำหรับเชิงอนุพันธ์ทางคณิตศาสตร์ ค่าเริ่มต้น: false

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

เชิงอนุพันธ์. เมื่อเป็นจริง กล่องทำหน้าที่เป็นเชิงอนุพันธ์ (เช่น \\ud835\\udc51\\ud835\\udc65 ในอินทิกรัล) และได้รับการจัดช่องว่างแนวนอนที่เหมาะสมสำหรับเชิงอนุพันธ์ทางคณิตศาสตร์ ค่าเริ่มต้น: false

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

เมื่อเป็นจริง ตัวจำลองโอเปอเรเตอร์นี้ทำหน้าที่เป็นจุดจัดตำแหน่ง; นั่นคือ จุดจัดตำแหน่งที่กำหนดในสมการอื่น ๆ สามารถจัดตำแหน่งให้ตรงกับมันได้. ค่าเริ่มต้น: false

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

เมื่อเป็นจริง ตัวจำลองโอเปอเรเตอร์นี้ทำหน้าที่เป็นจุดจัดตำแหน่ง; นั่นคือ จุดจัดตำแหน่งที่กำหนดในสมการอื่น ๆ สามารถจัดตำแหน่งให้ตรงกับมันได้. ค่าเริ่มต้น: false

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

การตัดบรรทัดแบบกำหนดล่วงหน้ากำหนดว่ามีการตัดบรรทัดที่จุดเริ่มต้นของวัตถุ Box หรือไม่ ซึ่งทำให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของวัตถุ Box. กำหนดหมายเลขของโอเปอเรเตอร์ในบรรทัดก่อนของข้อความคณิตศาสตร์ที่ใช้เป็นจุดจัดตำแหน่งสำหรับบรรทัดปัจจุบันของข้อความคณิตศาสตร์ ค่าที่เป็นไปได้: 1..255 ค่าเริ่มต้น: 0 (ไม่มีการตัดบรรทัดแบบกำหนดล่วงหน้า)

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

การตัดบรรทัดแบบกำหนดล่วงหน้ากำหนดว่ามีการตัดบรรทัดที่จุดเริ่มต้นของวัตถุ Box หรือไม่ ซึ่งทำให้บรรทัดห่อหุ้มที่จุดเริ่มต้นของวัตถุ Box. กำหนดหมายเลขของโอเปอเรเตอร์ในบรรทัดก่อนของข้อความคณิตศาสตร์ที่ใช้เป็นจุดจัดตำแหน่งสำหรับบรรทัดปัจจุบันของข้อความคณิตศาสตร์ ค่าที่เป็นไปได้: 1..255 ค่าเริ่มต้น: 0 (ไม่มีการตัดบรรทัดแบบกำหนดล่วงหน้า)

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