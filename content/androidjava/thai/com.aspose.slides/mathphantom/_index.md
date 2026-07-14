---
title: MathPhantom
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงถึงอ็อบเจ็กต์คณิตศาสตร์แฟนท์ ltmphantgt ที่ส่งผลต่อการจัดวางขององค์ประกอบลูกโดยไม่จำเป็นต้องแสดงผลออกมา.
type: docs
url: /th/com.aspose.slides/mathphantom/
---
**การสืบทอด:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IMathPhantom](../../com.aspose.slides/imathphantom), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathPhantom extends MathElementBase implements IMathPhantom, IHasControlCharacterProperties
```

แสดงถึงอ็อบเจ็กต์คณิตศาสตร์แฟนท์ (<m:phant>) ที่ส่งผลต่อการจัดวางขององค์ประกอบลูกโดยไม่จำเป็นต้องแสดงผลออกมา แฟนท์สามารถซ่อนนิพจน์ฐานของมันในขณะที่ยังคงรักษาความกว้าง, ความสูง หรือความลึกไว้เพื่อจัดแนวสูตรหรือสำรองพื้นที่ พฤติกรรมการมองเห็นและรูปทรงถูกควบคุมโดยคุณสมบัติต่าง ๆ เช่น Show, ZeroWid, ZeroAsc, ZeroDesc, และ Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // ซ่อนเนื้อหา
>  phantom.setZeroWidth(false);     // รักษาความกว้าง
> ```
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [MathPhantom(IMathElement element)](#MathPhantom-com.aspose.slides.IMathElement-) | เริ่มต้นอินสแตนซ์ใหม่ของคลาส [MathPhantom](../../com.aspose.slides/mathphantom) ด้วยการใช้องค์ประกอบคณิตศาสตร์ฐานที่ระบุ. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getBase()](#getBase--) | อาร์กิวเมนต์ฐาน |
| [getShow()](#getShow--) | รับหรือกำหนดค่าที่บ่งบอกว่าตัวองค์ประกอบฐานถูกแสดงหรือไม่. |
| [setShow(boolean value)](#setShow-boolean-) | รับหรือกำหนดค่าที่บ่งบอกว่าตัวองค์ประกอบฐานถูกแสดงหรือไม่. |
| [getZeroWidth()](#getZeroWidth--) | รับหรือกำหนดค่าที่บ่งบอกว่าความกว้างของตัวองค์ประกอบฐานควรถูกถือเป็นศูนย์หรือไม่. |
| [setZeroWidth(boolean value)](#setZeroWidth-boolean-) | รับหรือกำหนดค่าที่บ่งบอกว่าความกว้างของตัวองค์ประกอบฐานควรถูกถือเป็นศูนย์หรือไม่. |
| [getZeroAsc()](#getZeroAsc--) | รับหรือกำหนดค่าที่บ่งบอกว่าการยกขึ้น (ความสูงเหนือเส้นฐาน) ของตัวองค์ประกอบฐานควรถูกถือเป็นศูนย์หรือไม่. |
| [setZeroAsc(boolean value)](#setZeroAsc-boolean-) | รับหรือกำหนดค่าที่บ่งบอกว่าการยกขึ้น (ความสูงเหนือเส้นฐาน) ของตัวองค์ประกอบฐานควรถูกถือเป็นศูนย์หรือไม่. |
| [getZeroDesc()](#getZeroDesc--) | รับหรือกำหนดค่าที่บ่งบอกว่าการลงล่าง (ความลึกใต้เส้นฐาน) ของตัวองค์ประกอบฐานควรถูกถือเป็นศูนย์หรือไม่. |
| [setZeroDesc(boolean value)](#setZeroDesc-boolean-) | รับหรือกำหนดค่าที่บ่งบอกว่าการลงล่าง (ความลึกใต้เส้นฐาน) ของตัวองค์ประกอบฐานควรถูกถือเป็นศูนย์หรือไม่. |
| [getTransp()](#getTransp--) | รับหรือกำหนดค่าที่บ่งบอกว่าแฟนท์เป็นโปร่งใสต่อกฎการเว้นระยะแบบอิงคลาสหรือไม่. |
| [setTransp(boolean value)](#setTransp-boolean-) | รับหรือกำหนดค่าที่บ่งบอกว่าแฟนท์เป็นโปร่งใสต่อกฎการเว้นระยะแบบอิงคลาสหรือไม่. |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | คุณสมบัติตัวอักขระควบคุม |
| [getChildren()](#getChildren--) | รับองค์ประกอบลูก |
### MathPhantom(IMathElement element) {#MathPhantom-com.aspose.slides.IMathElement-}
```
public MathPhantom(IMathElement element)
```

เริ่มต้นอินสแตนซ์ใหม่ของคลาส [MathPhantom](../../com.aspose.slides/mathphantom) ด้วยการใช้องค์ประกอบคณิตศาสตร์ฐานที่ระบุ.

--------------------

> ```
> Example:
>  
>  IMathElement fraction = new MathFraction(
>      new MathematicalText("1"),
>      new MathematicalText("2"));
> ```

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | [IMathElement](../../com.aspose.slides/imathelement) ฐานที่การมองเห็นและการจัดวางจะถูกควบคุมโดยแฟนท์ องค์ประกอบนี้กำหนดเนื้อหาที่อาจถูกซ่อนหรือแสดงได้ แต่ยังคงส่งผลต่อการจัดแนวเชิงเรขาคณิตของคณิตศาสตร์โดยรอบ.

--------------------

อ็อบเจ็กต์แฟนท์นี้ใช้เพื่อสำรองหรือกดดันพื้นที่มองเห็นของนิพจน์ฐานโดยไม่จำเป็นต้องแสดงผลออกมา มันสอดคล้องกับองค์ประกอบ OMML <m:phant>. |

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

**ค่าที่ส่งกลับ:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public final boolean getShow()
```

รับหรือกำหนดค่าที่บ่งบอกว่าตัวองค์ประกอบฐานถูกแสดงหรือไม่.

--------------------

เมื่อค่าเป็น false ตัวองค์ประกอบฐานจะถูกซ่อนแต่ยังอาจครอบครองพื้นที่ได้ขึ้นอยู่กับการตั้งค่าแฟนท์อื่น ๆ สอดคล้องกับแอตทริบิวต์ OMML m:show.

**ค่าที่ส่งกลับ:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public final void setShow(boolean value)
```

รับหรือกำหนดค่าที่บ่งบอกว่าตัวองค์ประกอบฐานถูกแสดงหรือไม่.

--------------------

เมื่อค่าเป็น false ตัวองค์ประกอบฐานจะถูกซ่อนแต่ยังอาจครอบครองพื้นที่ได้ขึ้นอยู่กับการตั้งค่าแฟนท์อื่น ๆ สอดคล้องกับแอตทริบิวต์ OMML m:show.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public final boolean getZeroWidth()
```

รับหรือกำหนดค่าที่บ่งบอกว่าความกว้างของตัวองค์ประกอบฐานควรถูกถือเป็นศูนย์หรือไม่.

--------------------

เมื่อค่าเป็น true แฟนท์จะไม่สำรองพื้นที่แนวนอนสำหรับฐานของมัน สอดคล้องกับแอตทริบิวต์ OMML m:zeroWid.

**ค่าที่ส่งกลับ:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public final void setZeroWidth(boolean value)
```

รับหรือกำหนดค่าที่บ่งบอกว่าความกว้างของตัวองค์ประกอบฐานควรถูกถือเป็นศูนย์หรือไม่.

--------------------

เมื่อค่าเป็น true แฟนท์จะไม่สำรองพื้นที่แนวนอนสำหรับฐานของมัน สอดคล้องกับแอตทริบิวต์ OMML m:zeroWid.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public final boolean getZeroAsc()
```

รับหรือกำหนดค่าที่บ่งบอกว่าการยกขึ้น (ความสูงเหนือเส้นฐาน) ของตัวองค์ประกอบฐานควรถูกถือเป็นศูนย์หรือไม่.

--------------------

เมื่อค่าเป็น true แฟนท์จะไม่ยกระดับเส้นฐานของบรรทัดคณิตศาสตร์โดยรอบ สอดคล้องกับแอตทริบิวต์ OMML m:zeroAsc.

**ค่าที่ส่งกลับ:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public final void setZeroAsc(boolean value)
```

รับหรือกำหนดค่าที่บ่งบอกว่าการยกขึ้น (ความสูงเหนือเส้นฐาน) ของตัวองค์ประกอบฐานควรถูกถือเป็นศูนย์หรือไม่.

--------------------

เมื่อค่าเป็น true แฟนท์จะไม่ยกระดับเส้นฐานของบรรทัดคณิตศาสตร์โดยรอบ สอดคล้องกับแอตทริบิวต์ OMML m:zeroAsc.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public final boolean getZeroDesc()
```

รับหรือกำหนดค่าที่บ่งบอกว่าการลงล่าง (ความลึกใต้เส้นฐาน) ของตัวองค์ประกอบฐานควรถูกถือเป็นศูนย์หรือไม่.

--------------------

เมื่อค่าเป็น true แฟนท์จะไม่ทำให้เส้นฐานของบรรทัดคณิตศาสตร์โดยรอบลงล่าง สอดคล้องกับแอตทริบิวต์ OMML m:zeroDesc.

**ค่าที่ส่งกลับ:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public final void setZeroDesc(boolean value)
```

รับหรือกำหนดค่าที่บ่งบอกว่าการลงล่าง (ความลึกใต้เส้นฐาน) ของตัวองค์ประกอบฐานควรถูกถือเป็นศูนย์หรือไม่.

--------------------

เมื่อค่าเป็น true แฟนท์จะไม่ทำให้เส้นฐานของบรรทัดคณิตศาสตร์โดยรอบลงล่าง สอดคล้องกับแอตทริบิวต์ OMML m:zeroDesc.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public final boolean getTransp()
```

รับหรือกำหนดค่าที่บ่งบอกว่าแฟนท์เป็นโปร่งใสต่อกฎการเว้นระยะแบบอิงคลาสหรือไม่.

--------------------

เมื่อค่าเป็น true ตัวดำเนินการและสัญลักษณ์ภายในแฟนท์ยังคงส่งผลต่อการเว้นระยะคณิตศาสตร์รอบ ๆ แฟนท์ (เหมือนเป็นที่มองเห็น) เมื่อค่าเป็น false การเว้นระยะแบบอิงคลาสจะถูกละเลย สอดคล้องกับแอตทริบิวต์ OMML m:transp.

**ค่าที่ส่งกลับ:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public final void setTransp(boolean value)
```

รับหรือกำหนดค่าที่บ่งบอกว่าแฟนท์เป็นโปร่งใสต่อกฎการเว้นระยะแบบอิงคลาสหรือไม่.

--------------------

เมื่อค่าเป็น true ตัวดำเนินการและสัญลักษณ์ภายในแฟนท์ยังคงส่งผลต่อการเว้นระยะคณิตศาสตร์รอบ ๆ แฟนท์ (เหมือนเป็นที่มองเห็น) เมื่อค่าเป็น false การเว้นระยะแบบอิงคลาสจะถูกละเลย สอดคล้องกับแอตทริบิวต์ OMML m:transp.

**พารามิเตอร์:**
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

คุณสมบัติตัวอักขระควบคุม

**ค่าที่ส่งกลับ:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

รับองค์ประกอบลูก

**ค่าที่ส่งกลับ:**
com.aspose.slides.IMathElement[]