---
title: IMathPhantom
second_title: การอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: เป็นตัวแทนของวัตถุคณิตศาสตร์ phantom ltmphantgt ที่ส่งผลต่อการจัดวางขององค์ประกอบลูกโดยไม่จำเป็นต้องแสดงผล.
type: docs
url: /th/com.aspose.slides/imathphantom/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathPhantom extends IMathElement
```

แทนวัตถุคณิตศาสตร์ชนิด phantom (<m:phant>) ที่ส่งผลต่อการจัดวางขององค์ประกอบลูกโดยไม่จำเป็นต้องแสดงผล ตัว phantom สามารถซ่อนนิพจน์ฐานขณะยังคงรักษาความกว้าง, ความสูง หรือความลึกเพื่อจัดตำแหน่งสูตรหรือสงวนพื้นที่ พฤติกรรมการมองเห็นและเรขาคณิตควบคุมโดยคุณสมบัติต่าง ๆ เช่น Show, ZeroWid, ZeroAsc, ZeroDesc, และ Transp.

--------------------

> ```
> Example:
>  
>  IMathPhantom phantom = new MathPhantom(new MathematicalText("1/2"));
>  phantom.setShow(false);          // ซ่อนเนื้อหา
>  phantom.setZeroWidth(false);     // คงความกว้าง
>  ```

## Methods

| Method | Description |
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
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

อาร์กิวเมนต์ฐาน

--------------------

> ```
> Example:
>  
>  MathPhantom mathBar = new MathPhantom(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
>  ```


**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getShow() {#getShow--}
```
public abstract boolean getShow()
```

รับหรือกำหนดค่าที่บ่งชี้ว่าธาตุฐานจะแสดงหรือไม่

--------------------

เมื่อเป็น false, ธาตุฐานจะถูกซ่อนแต่ยังอาจครอบครองพื้นที่ขึ้นอยู่กับการตั้งค่า phantom อื่น ๆ สอดคล้องกับแอตทริบิวต์ OMML m:show.

**Returns:**
boolean
### setShow(boolean value) {#setShow-boolean-}
```
public abstract void setShow(boolean value)
```

รับหรือกำหนดค่าที่บ่งชี้ว่าธาตุฐานจะแสดงหรือไม่

--------------------

เมื่อเป็น false, ธาตุฐานจะถูกซ่อนแต่ยังอาจครอบครองพื้นที่ขึ้นอยู่กับการตั้งค่า phantom อื่น ๆ สอดคล้องกับแอตทริบิวต์ OMML m:show.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroWidth() {#getZeroWidth--}
```
public abstract boolean getZeroWidth()
```

รับหรือกำหนดค่าที่บ่งชี้ว่าความกว้างของธาตุฐานควรถือเป็นศูนย์หรือไม่

--------------------

เมื่อเป็น true, phantom จะไม่สงวนพื้นที่แนวนอนสำหรับฐานของมัน สอดคล้องกับแอตทริบิวต์ OMML m:zeroWid.

**Returns:**
boolean
### setZeroWidth(boolean value) {#setZeroWidth-boolean-}
```
public abstract void setZeroWidth(boolean value)
```

รับหรือกำหนดค่าที่บ่งชี้ว่าความกว้างของธาตุฐานควรถือเป็นศูนย์หรือไม่

--------------------

เมื่อเป็น true, phantom จะไม่สงวนพื้นที่แนวนอนสำหรับฐานของมัน สอดคล้องกับแอตทริบิวต์ OMML m:zeroWid.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroAsc() {#getZeroAsc--}
```
public abstract boolean getZeroAsc()
```

รับหรือกำหนดค่าที่บ่งชี้ว่าการยก (ความสูงเหนือบรรทัดฐาน) ของธาตุฐานควรถือเป็นศูนย์หรือไม่

--------------------

เมื่อเป็น true, phantom ไม่ยกบรรทัดฐานของบรรทัดคณิตศาสตร์โดยรอบ สอดคล้องกับแอตทริบิวต์ OMML m:zeroAsc.

**Returns:**
boolean
### setZeroAsc(boolean value) {#setZeroAsc-boolean-}
```
public abstract void setZeroAsc(boolean value)
```

รับหรือกำหนดค่าที่บ่งชี้ว่าการยก (ความสูงเหนือบรรทัดฐาน) ของธาตุฐานควรถือเป็นศูนย์หรือไม่

--------------------

เมื่อเป็น true, phantom ไม่ยกบรรทัดฐานของบรรทัดคณิตศาสตร์โดยรอบ สอดคล้องกับแอตทริบิวต์ OMML m:zeroAsc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getZeroDesc() {#getZeroDesc--}
```
public abstract boolean getZeroDesc()
```

รับหรือกำหนดค่าที่บ่งชี้ว่าการลง (ความลึกต่ำกว่าบรรทัดฐาน) ของธาตุฐานควรถือเป็นศูนย์หรือไม่

--------------------

เมื่อเป็น true, phantom ไม่ทำให้บรรทัดฐานของบรรทัดคณิตศาสตร์โดยรอบลดลง สอดคล้องกับแอตทริบิวต์ OMML m:zeroDesc.

**Returns:**
boolean
### setZeroDesc(boolean value) {#setZeroDesc-boolean-}
```
public abstract void setZeroDesc(boolean value)
```

รับหรือกำหนดค่าที่บ่งชี้ว่าการลง (ความลึกต่ำกว่าบรรทัดฐาน) ของธาตุฐานควรถือเป็นศูนย์หรือไม่

--------------------

เมื่อเป็น true, phantom ไม่ทำให้บรรทัดฐานของบรรทัดคณิตศาสตร์โดยรอบลดลง สอดคล้องกับแอตทริบิวต์ OMML m:zeroDesc.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getTransp() {#getTransp--}
```
public abstract boolean getTransp()
```

รับหรือกำหนดค่าที่บ่งชี้ว่า phantom มีความโปร่งใสต่อกฎการเว้นวรรคแบบ class-based หรือไม่

--------------------

เมื่อเป็น true, ตัวดำเนินการและสัญลักษณ์ภายใน phantom ยังคงส่งผลต่อการเว้นวรรคคณิตศาสตร์รอบ ๆ phantom (เหมือนว่ามองเห็นได้) เมื่อเป็น false, การเว้นวรรคแบบ class-based จะถูกละเลย สอดคล้องกับแอตทริบิวต์ OMML m:transp.

**Returns:**
boolean
### setTransp(boolean value) {#setTransp-boolean-}
```
public abstract void setTransp(boolean value)
```

รับหรือกำหนดค่าที่บ่งชี้ว่า phantom มีความโปร่งใสต่อกฎการเว้นวรรคแบบ class-based หรือไม่

--------------------

เมื่อเป็น true, ตัวดำเนินการและสัญลักษณ์ภายใน phantom ยังคงส่งผลต่อการเว้นวรรคคณิตศาสตร์รอบ ๆ phantom (เหมือนว่ามองเห็นได้) เมื่อเป็น false, การเว้นวรรคแบบ class-based จะถูกละเลย สอดคล้องกับแอตทริบิวต์ OMML m:transp.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |