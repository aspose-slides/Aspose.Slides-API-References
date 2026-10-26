---
title: Point
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: แสดงจุดแอนิเมชัน.
type: docs
url: /th/com.aspose.slides/point/
---
**การสืบทอด:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)  
```
public class Point implements IPoint
```

แสดงจุดแอนิเมชัน.

## ตัวสร้าง

| Constructor | Description |
| --- | --- |
| [Point()](#Point--) | คอนสตรัคเตอร์เริ่มต้น. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | สร้างจุดแอนิเมชันด้วยเวลา, ค่าและสูตร. |

## เมธอด

| Method | Description |
| --- | --- |
| [getTime()](#getTime--) | แสดงค่าเวลา. |
| [setTime(float value)](#setTime-float-) | แสดงค่าเวลา. |
| [getValue()](#getValue--) | แสดงค่าจุด. |
| [setValue(Object value)](#setValue-java.lang.Object-) | แสดงค่าจุด. |
| [getFormula()](#getFormula--) | สูตรภายในค่า, แอตริบิวต์ from, to, by สามารถสร้างจากสิ่งต่อไปนี้: ตัวดำเนินการคณิตศาสตร์พื้นฐาน: '+', '-', '*', '/', '^', '%' (mod) ค่าคงที่: 'pi' 'e' ตัวดำเนินการเชิงเงื่อนไข: 'abs', 'min', 'max', '?' (if) ตัวดำเนินการเปรียบเทียบ: '==', '>=', '', '!=', '!' ตัวดำเนินการตรีโกณมิติ: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' ลอการิทึมธรรมชาติ 'ln()' การอ้างอิงคุณสมบัติ (คุณสมบัติที่โฮสต์สนับสนุน) ตัวอย่างเช่น: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" อ่าน/เขียน String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | สูตรภายในค่า, แอตริบิวต์ from, to, by สามารถสร้างจากสิ่งต่อไปนี้: ตัวดำเนินการคณิตศาสตร์พื้นฐาน: '+', '-', '*', '/', '^', '%' (mod) ค่าคงที่: 'pi' 'e' ตัวดำเนินการเชิงเงื่อนไข: 'abs', 'min', 'max', '?' (if) ตัวดำเนินการเปรียบเทียบ: '==', '>=', '', '!=', '!' ตัวดำเนินการตรีโกณมิติ: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' ลอการิทึมธรรมชาติ 'ln()' การอ้างอิงคุณสมบัติ (คุณสมบัติที่โฮสต์สนับสนุน) ตัวอย่างเช่น: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" อ่าน/เขียน String. |

### Point() {#Point--}
```
public Point()
```

คอนสตรัคเตอร์เริ่มต้น.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

สร้างจุดแอนิเมชันด้วยเวลา, ค่าและสูตร.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| time | float | ค่าเวลา. |
| value | java.lang.Object | ค่าจุด. |
| formula | java.lang.String | สูตร. |

### getTime() {#getTime--}
```
public final float getTime()
```

แสดงค่าเวลา. อ่าน/เขียน float.

**คืนค่า:**
float

### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

แสดงค่าเวลา. อ่าน/เขียน float.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

แสดงค่าจุด. เฉพาะ: bool, ColorFormat, float, int, string. อ่าน/เขียน Object.

**คืนค่า:**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

แสดงค่าจุด. เฉพาะ: bool, ColorFormat, float, int, string. อ่าน/เขียน Object.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

สูตรภายในค่า, แอตริบิวต์ from, to, by สามารถสร้างจากสิ่งต่อไปนี้: ตัวดำเนินการคณิตศาสตร์พื้นฐาน: '+', '-', '*', '/', '^', '%' (mod) ค่าคงที่: 'pi' 'e' ตัวดำเนินการเชิงเงื่อนไข: 'abs', 'min', 'max', '?' (if) ตัวดำเนินการเปรียบเทียบ: '==', '>=', '', '!=', '!' ตัวดำเนินการตรีโกณมิติ: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' ลอการิทึมธรรมชาติ 'ln()' การอ้างอิงคุณสมบัติ (คุณสมบัติที่โฮสต์สนับสนุน) ตัวอย่างเช่น: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" อ่าน/เขียน String.

**คืนค่า:**
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

สูตรภายในค่า, แอตริบิวต์ from, to, by สามารถสร้างจากสิ่งต่อไปนี้: ตัวดำเนินการคณิตศาสตร์พื้นฐาน: '+', '-', '*', '/', '^', '%' (mod) ค่าคงที่: 'pi' 'e' ตัวดำเนินการเชิงเงื่อนไข: 'abs', 'min', 'max', '?' (if) ตัวดำเนินการเปรียบเทียบ: '==', '>=', '', '!=', '!' ตัวดำเนินการตรีโกณมิติ: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' ลอการิทึมธรรมชาติ 'ln()' การอ้างอิงคุณสมบัติ (คุณสมบัติที่โฮสต์สนับสนุน) ตัวอย่างเช่น: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" อ่าน/เขียน String.

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |