---
title: IMathPhantom
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แทนวัตถุคณิตศาสตร์แบบแฟนท์ ltmphantgt ที่มีผลต่อการจัดวางขององค์ประกอบลูกโดยไม่จำเป็นต้องแสดงผล
type: docs
url: /th/com.aspose.slides/imathphantom/
---
**ส่วนต่อประสานที่ใช้งานทั้งหมด:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

แทนวัตถุคณิตศาสตร์แบบแฟนท์ (<m:phant>) ที่มีผลต่อการจัดวางขององค์ประกอบลูกโดยไม่จำเป็นต้องแสดงผล วัตถุแฟนท์สามารถซ่อนนิพจน์ฐานในขณะที่ยังคงรักษาความกว้าง ความสูง หรือความลึกเพื่อจัดสูตรหรือสงวนพื้นที่ พฤติกรรมการมองเห็นและรูปทรงถูกควบคุมโดยคุณสมบัติต่าง ๆ เช่น Show, ZeroWid, ZeroAsc, ZeroDesc, และ Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // ซ่อนเนื้อหา
>  phantom.setZeroWidth(false);     // เก็บความกว้างไว้
```
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กุเมนต์ฐาน |
| [getShow()](#getShow--) | รับหรือกำหนดค่าที่ระบุว่าตัวองค์ประกอบฐานจะแสดงหรือไม่ |
| [setShow(boolean value)](#setShow-boolean-) | รับหรือกำหนดค่าที่ระบุว่าตัวองค์ประกอบฐานจะแสดงหรือไม่ |
| [getZeroWidth()](#getZeroWidth--) | รับหรือกำหนดค่าที่ระบุว่าความกว้างของตัวองค์ประกอบฐานควรถือเป็นศูนย์หรือไม่ |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | รับหรือกำหนดค่าที่ระบุว่าความกว้างของตัวองค์ประกอบฐานควรถือเป็นศูนย์หรือไม่ |
| [getZeroAsc()](#getZeroAsc--) | รับหรือกำหนดค่าที่ระบุว่าความสูงเหนือบรรทัดฐานของตัวองค์ประกอบฐานควรถือเป็นศูนย์หรือไม่ |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | รับหรือกำหนดค่าที่ระบุว่าความสูงเหนือบรรทัดฐานของตัวองค์ประกอบฐานควรถือเป็นศูนย์หรือไม่ |
| [getZeroDesc()](#getZeroDesc--) | รับหรือกำหนดค่าที่ระบุว่าความลึกต่ำกว่าบรรทัดฐานของตัวองค์ประกอบฐานควรถือเป็นศูนย์หรือไม่ |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | รับหรือกำหนดค่าที่ระบุว่าความลึกต่ำกว่าบรรทัดฐานของตัวองค์ประกอบฐานควรถือเป็นศูนย์หรือไม่ |
| [getTransp()](#getTransp--) | รับหรือกำหนดค่าที่ระบุว่าภาพแฟนท์โปร่งใสต่อกฎการเว้นระยะตามคลาสหรือไม่ |
| [setTransp(boolean value)](#setTransp-boolean-) | รับหรือกำหนดค่าที่ระบุว่าภาพแฟนท์โปร่งใสต่อกฎการเว้นระยะตามคลาสหรือไม่ |

### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

อาร์กุเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**คืนค่า:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

รับหรือกำหนดค่าที่ระบุว่าตัวองค์ประกอบฐานจะแสดงหรือไม่

--------------------

เมื่อเป็น false, ตัวองค์ประกอบฐานจะถูกซ่อนแต่ยังอาจคงใช้พื้นที่อยู่ขึ้นอยู่กับการตั้งค่าแฟนท์อื่น ๆ ตรงกับแอตทริบิวต์ OMML m:show.

**คืนค่า:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

รับหรือกำหนดค่าที่ระบุว่าตัวองค์ประกอบฐานจะแสดงหรือไม่

--------------------

เมื่อเป็น false, ตัวองค์ประกอบฐานจะถูกซ่อนแต่ยังอาจคงใช้พื้นที่อยู่ขึ้นอยู่กับการตั้งค่าแฟนท์อื่น ๆ ตรงกับแอตทริบิวต์ OMML m:show.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

รับหรือกำหนดค่าที่ระบุว่าความกว้างของตัวองค์ประกอบฐานควรถือเป็นศูนย์หรือไม่

--------------------

เมื่อเป็น true, แฟนท์จะไม่สงวนพื้นที่แนวนอนสำหรับฐานของมัน ตรงกับแอตทริบิวต์ OMML m:zeroWid.

**คืนค่า:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

รับหรือกำหนดค่าที่ระบุว่าความกว้างของตัวองค์ประกอบฐานควรถือเป็นศูนย์หรือไม่

--------------------

เมื่อเป็น true, แฟนท์จะไม่สงวนพื้นที่แนวนอนสำหรับฐานของมัน ตรงกับแอตทริบิวต์ OMML m:zeroWid.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

รับหรือกำหนดค่าที่ระบุว่าความสูงเหนือบรรทัดฐานของตัวองค์ประกอบฐานควรถือเป็นศูนย์หรือไม่

--------------------

เมื่อเป็น true, แฟนท์จะไม่ยกบรรทัดฐานของบรรทัดคณิตศาสตร์โดยรอบ ตรงกับแอตทริบิวต์ OMML m:zeroAsc.

**คืนค่า:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

รับหรือกำหนดค่าที่ระบุว่าความสูงเหนือบรรทัดฐานของตัวองค์ประกอบฐานควรถือเป็นศูนย์หรือไม่

--------------------

เมื่อเป็น true, แฟนท์จะไม่ยกบรรทัดฐานของบรรทัดคณิตศาสตร์โดยรอบ ตรงกับแอตทริบิวต์ OMML m:zeroAsc.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

รับหรือกำหนดค่าที่ระบุว่าความลึกต่ำกว่าบรรทัดฐานของตัวองค์ประกอบฐานควรถือเป็นศูนย์หรือไม่

--------------------

เมื่อเป็น true, แฟนท์จะไม่ทำให้บรรทัดฐานของบรรทัดคณิตศาสตร์โดยรอบต่ำลง ตรงกับแอตทริบิวต์ OMML m:zeroDesc.

**คืนค่า:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

รับหรือกำหนดค่าที่ระบุว่าความลึกต่ำกว่าบรรทัดฐานของตัวองค์ประกอบฐานควรถือเป็นศูนย์หรือไม่

--------------------

เมื่อเป็น true, แฟนท์จะไม่ทำให้บรรทัดฐานของบรรทัดคณิตศาสตร์โดยรอบต่ำลง ตรงกับแอตทริบิวต์ OMML m:zeroDesc.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

รับหรือกำหนดค่าที่ระบุว่าภาพแฟนท์โปร่งใสต่อกฎการเว้นระยะตามคลาสหรือไม่

--------------------

เมื่อเป็น true, ตัวดำเนินการและสัญลักษณ์ภายในแฟนท์ยังคงส่งผลต่อการเว้นระยะคณิตศาสตร์รอบแฟนท์ (เหมือนเป็นที่มองเห็น) เมื่อเป็น false, การเว้นระยะตามคลาสจะถูกละเว้น ตรงกับแอตทริบิวต์ OMML m:transp.

**คืนค่า:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

รับหรือกำหนดค่าที่ระบุว่าภาพแฟนท์โปร่งใสต่อกฎการเว้นระยะตามคลาสหรือไม่

--------------------

เมื่อเป็น true, ตัวดำเนินการและสัญลักษณ์ภายในแฟนท์ยังคงส่งผลต่อการเว้นระยะคณิตศาสตร์รอบแฟนท์ (เหมือนเป็นที่มองเห็น) เมื่อเป็น false, การเว้นระยะตามคลาสจะถูกละเว้น ตรงกับแอตทริบิวต์ OMML m:transp.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |