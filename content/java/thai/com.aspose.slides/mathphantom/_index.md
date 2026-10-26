---
title: MathPhantom
second_title: Aspose.Slides สำหรับการอ้างอิง API ของ Java
description: แสดงถึงออบเจ็กต์คณิตศาสตร์แบบฟานท์ ltmphantgt ที่ส่งผลต่อการจัดวางขององค์ประกอบลูกโดยไม่จำเป็นต้องแสดงออก
type: docs
url: /th/com.aspose.slides/mathphantom/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

เป็นออบเจ็กต์คณิตศาสตร์แบบฟานท์ (<m:phant>) ที่ส่งผลต่อการจัดวางขององค์ประกอบลูกโดยไม่จำเป็นต้องแสดงออก ฟานท์สามารถซ่อนนิพจน์ฐานของมันในขณะที่คงรักษาความกว้าง ความสูง หรือความลึกไว้เพื่อจัดแนวสูตรหรือสำรองพื้นที่ พฤติกรรมการมองเห็นและรูปทรงจะควบคุมโดยคุณสมบัติเช่น Show, ZeroWid, ZeroAsc, ZeroDesc, และ Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // ซ่อนเนื้อหา
>  phantom.setZeroWidth(false);     // รักษาความกว้าง
> ```
## ตัวสร้าง

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | Initializes a new instance of the [MathPhantom](../../com.aspose.slides/mathphantom) class using the specified base math element. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | Base argument |
| [getShow()](#getShow--) | Gets or sets a value indicating whether the base element is displayed. |
| [setShow(boolean value)](#setShow-boolean-) | Gets or sets a value indicating whether the base element is displayed. |
| [getZeroWidth()](#getZeroWidth--) | Gets or sets a value indicating whether the width of the base element should be treated as zero. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | Gets or sets a value indicating whether the width of the base element should be treated as zero. |
| [getZeroAsc()](#getZeroAsc--) | Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | Gets or sets a value indicating whether the ascent (height above baseline) of the base element should be treated as zero. |
| [getZeroDesc()](#getZeroDesc--) | Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | Gets or sets a value indicating whether the descent (depth below baseline) of the base element should be treated as zero. |
| [getTransp()](#getTransp--) | Gets or sets a value indicating whether the phantom is transparent for class-based spacing rules. |
| [setTransp(boolean value)](#setTransp-boolean-) | Gets or sets a value indicating whether the phantom is transparent for class-based spacing rules. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
| [getChildren()](#getChildren--) | Get children elements |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [MathPhantom](../../com.aspose.slides/mathphantom) โดยใช้องค์ประกอบคณิตศาสตร์ฐานที่ระบุ

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | ฐาน [IMathElement](../../com.aspose.slides/imathelement) ที่การมองเห็นและการจัดวางจะถูกควบคุมโดยฟานท์ องค์ประกอบนี้กำหนดเนื้อหาที่อาจถูกซ่อนหรือแสดง ในขณะที่ยังส่งผลต่อการจัดแนวเชิงเรขาคณิตของคณิตศาสตร์โดยรอบ |

ออบเจ็กต์ฟานท์นี้ใช้สำหรับสำรองหรือกดขนาดพื้นที่ภาพของนิพจน์ฐานโดยไม่จำเป็นต้องแสดงออก มันสอดคล้องกับอิลิเมนต์ OMML <m:phant>. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**ค่าที่ส่งคืน:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

รับหรือกำหนดค่าที่บ่งบอกว่าตัวองค์ประกอบฐานจะแสดงหรือไม่

--------------------

เมื่อเป็น false ตัวองค์ประกอบฐานจะถูกซ่อนแต่ยังอาจครอบครองพื้นที่ขึ้นอยู่กับการตั้งค่าฟานท์อื่น ๆ สอดคล้องกับแอตทริบิวต์ OMML m:show

**ค่าที่ส่งคืน:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

รับหรือกำหนดค่าที่บ่งบอกว่าตัวองค์ประกอบฐานจะแสดงหรือไม่

--------------------

เมื่อเป็น false ตัวองค์ประกอบฐานจะถูกซ่อนแต่ยังอาจครอบครองพื้นที่ขึ้นอยู่กับการตั้งค่าฟานท์อื่น ๆ สอดคล้องกับแอตทริบิวต์ OMML m:show

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

รับหรือกำหนดค่าที่บ่งบอกว่าความกว้างของตัวองค์ประกอบฐานควรถือเป็นศูนย์

--------------------

เมื่อเป็น true ฟานท์จะไม่สำรองพื้นที่แนวนอนสำหรับฐานของมัน สอดคล้องกับแอตทริบิวต์ OMML m:zeroWid

**ค่าที่ส่งคืน:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

รับหรือกำหนดค่าที่บ่งบอกว่าความกว้างของตัวองค์ประกอบฐานควรถือเป็นศูนย์

--------------------

เมื่อเป็น true ฟานท์จะไม่สำรองพื้นที่แนวนอนสำหรับฐานของมัน สอดคล้องกับแอตทริบิวต์ OMML m:zeroWid

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

รับหรือกำหนดค่าที่บ่งบอกว่าการลอยขึ้น (ความสูงเหนือเส้นฐาน) ของตัวองค์ประกอบฐานควรถือเป็นศูนย์

--------------------

เมื่อเป็น true ฟานท์จะไม่ยกเส้นฐานของบรรทัดคณิตศาสตร์โดยรอบ สอดคล้องกับแอตทริบิวต์ OMML m:zeroAsc

**ค่าที่ส่งคืน:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

รับหรือกำหนดค่าที่บ่งบอกว่าการลอยขึ้น (ความสูงเหนือเส้นฐาน) ของตัวองค์ประกอบฐานควรถือเป็นศูนย์

--------------------

เมื่อเป็น true ฟานท์จะไม่ยกเส้นฐานของบรรทัดคณิตศาสตร์โดยรอบ สอดคล้องกับแอตทริบิวต์ OMML m:zeroAsc

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

รับหรือกำหนดค่าที่บ่งบอกว่าการตกลง (ความลึกต่ำกว่าเส้นฐาน) ของตัวองค์ประกอบฐานควรถือเป็นศูนย์

--------------------

เมื่อเป็น true ฟานท์จะไม่ลดระดับเส้นฐานของบรรทัดคณิตศาสตร์โดยรอบ สอดคล้องกับแอตทริบิวต์ OMML m:zeroDesc

**ค่าที่ส่งคืน:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

รับหรือกำหนดค่าที่บ่งบอกว่าการตกลง (ความลึกต่ำกว่าเส้นฐาน) ของตัวองค์ประกอบฐานควรถือเป็นศูนย์

--------------------

เมื่อเป็น true ฟานท์จะไม่ลดระดับเส้นฐานของบรรทัดคณิตศาสตร์โดยรอบ สอดคล้องกับแอตทริบิวต์ OMML m:zeroDesc

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

รับหรือกำหนดค่าที่บ่งบอกว่าฟานท์เป็นแบบโปร่งใสต่อกฎการเว้นระยะตามคลาสหรือไม่

--------------------

เมื่อเป็น true ตัวดำเนินการและสัญลักษณ์ภายในฟานท์ยังคงส่งผลต่อการเว้นระยะคณิตศาสตร์รอบฟานท์ (เหมือนมองเห็นได้) เมื่อเป็น false จะละเว้นการเว้นระยะตามคลาส สอดคล้องกับแอตทริบิวต์ OMML m:transp

**ค่าที่ส่งคืน:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

รับหรือกำหนดค่าที่บ่งบอกว่าฟานท์เป็นแบบโปร่งใสต่อกฎการเว้นระยะตามคลาสหรือไม่

--------------------

เมื่อเป็น true ตัวดำเนินการและสัญลักษณ์ภายในฟานท์ยังคงส่งผลต่อการเว้นระยะคณิตศาสตร์รอบฟานท์ (เหมือนมองเห็นได้) เมื่อเป็น false จะละเว้นการเว้นระยะตามคลาส สอดคล้องกับแอตทริบิวต์ OMML m:transp

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักษรควบคุม

**ค่าที่ส่งคืน:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

ดึงองค์ประกอบลูก

**ค่าที่ส่งคืน:**
com.aspose.slides.IMathElement[]