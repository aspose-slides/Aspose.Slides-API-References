---
title: IPoint
second_title: Aspose.Slides for Java เอกสารอ้างอิง API
description: แสดงจุดแอนิเมชัน.
type: docs
url: /th/com.aspose.slides/ipoint/
---```
public interface IPoint
```

แสดงจุดแอนิเมชัน.
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTime()](#getTime--) | แสดงค่าเวลา. |
| [setTime(float value)](#setTime-float-) | แสดงค่าเวลา. |
| [getValue()](#getValue--) | แสดงค่าจุด. |
| [setValue(Object value)](#setValue-java.lang.Object-) | แสดงค่าจุด. |
| [getFormula()](#getFormula--) | สูตรภายในค่า, แอตทริบิวต์ from, to, by สามารถประกอบด้วยสิ่งต่อไปนี้: ตัวดำเนินการคณิตศาสตร์มาตฐาน: '+', '-', '*', '/', '^', '%' (mod) ค่าคงที่: 'pi' 'e' ตัวดำเนินการเชิงเงื่อนไข: 'abs', 'min', 'max', '?' (if) ตัวดำเนินการเปรียบเทียบ: '==', '>=', '', '!=', '!' ตัวดำเนินการตรีโกณมิติ: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' ลอการิทึมธรรมชาติ 'ln()' การอ้างอิงคุณสมบัติ (คุณสมบัติที่โฮสต์สนับสนุน) ตัวอย่างเช่น: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" อ่าน/เขียน String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | สูตรภายในค่า, แอตทริบิวต์ from, to, by สามารถประกอบด้วยสิ่งต่อไปนี้: ตัวดำเนินการคณิตศาสตร์มาตฐาน: '+', '-', '*', '/', '^', '%' (mod) ค่าคงที่: 'pi' 'e' ตัวดำเนินการเชิงเงื่อนไข: 'abs', 'min', 'max', '?' (if) ตัวดำเนินการเปรียบเทียบ: '==', '>=', '', '!=', '!' ตัวดำเนินการตรีโกณมิติ: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' ลอการิทึมธรรมชาติ 'ln()' การอ้างอิงคุณสมบัติ (คุณสมบัติที่โฮสต์สนับสนุน) ตัวอย่างเช่น: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" อ่าน/เขียน String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

แสดงค่าเวลา. อ่าน/เขียน float.

**คืนค่า:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

แสดงค่าเวลา. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

แสดงค่าจุด. Only: bool, ColorFormat, float, int, string. อ่าน/เขียน Object.

**คืนค่า:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

แสดงค่าจุด. Only: bool, ColorFormat, float, int, string. อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

สูตรภายในค่า, แอตทริบิวต์ from, to, by สามารถประกอบด้วยสิ่งต่อไปนี้: ตัวดำเนินการคณิตศาสตร์มาตฐาน: '+', '-', '*', '/', '^', '%' (mod) ค่าคงที่: 'pi' 'e' ตัวดำเนินการเชิงเงื่อนไข: 'abs', 'min', 'max', '?' (if) ตัวดำเนินการเปรียบเทียบ: '==', '>=', '', '!=', '!' ตัวดำเนินการตรีโกณมิติ: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' ลอการิทึมธรรมชาติ 'ln()' การอ้างอิงคุณสมบัติ (คุณสมบัติที่โฮสต์สนับสนุน) ตัวอย่างเช่น: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

สูตรภายในค่า, แอตทริบิวต์ from, to, by สามารถประกอบด้วยสิ่งต่อไปนี้: ตัวดำเนินการคณิตศาสตร์มาตฐาน: '+', '-', '*', '/', '^', '%' (mod) ค่าคงที่: 'pi' 'e' ตัวดำเนินการเชิงเงื่อนไข: 'abs', 'min', 'max', '?' (if) ตัวดำเนินการเปรียบเทียบ: '==', '>=', '', '!=', '!' ตัวดำเนินการตรีโกณมิติ: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' ลอการิทึมธรรมชาติ 'ln()' การอ้างอิงคุณสมบัติ (คุณสมบัติที่โฮสต์สนับสนุน) ตัวอย่างเช่น: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |