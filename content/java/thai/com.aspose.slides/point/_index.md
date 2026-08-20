---
title: Point
second_title: เอกสารอ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงจุดแอนิเมชัน.
type: docs
url: /th/com.aspose.slides/point/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการใช้งานทั้งหมด:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

แสดงจุดแอนิเมชัน.
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [Point()](#Point--) | ตัวสร้างเริ่มต้น. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | สร้างจุดแอนิเมชันด้วยเวลา, ค่าและสูตร. |
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getTime()](#getTime--) | แสดงค่าของเวลา. |
| [setTime(float value)](#setTime-float-) | แสดงค่าของเวลา. |
| [getValue()](#getValue--) | แสดงค่าของจุด. |
| [setValue(Object value)](#setValue-java.lang.Object-) | แสดงค่าของจุด. |
| [getFormula()](#getFormula--) | สูตรภายในค่า, from, to, by attributes สามารถประกอบด้วยสิ่งต่อไปนี้: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" อ่าน/เขียน String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | สูตรภายในค่า, from, to, by attributes สามารถประกอบด้วยสิ่งต่อไปนี้: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" อ่าน/เขียน String. |
### Point() {#Point--}
```
public Point()
```

ตัวสร้างเริ่มต้น.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

สร้างจุดแอนิเมชันด้วยเวลา, ค่าและสูตร.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| time | float | ค่าของเวลา. |
| value | java.lang.Object | ค่าของจุด. |
| formula | java.lang.String | สูตร. |

### getTime() {#getTime--}
```
public final float getTime()
```

แสดงค่าของเวลา. อ่าน/เขียน float.

**คืนค่า:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

แสดงค่าของเวลา. อ่าน/เขียน float.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

แสดงค่าของจุด. เฉพาะ: bool, ColorFormat, float, int, string. อ่าน/เขียน Object.

**คืนค่า:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

แสดงค่าของจุด. เฉพาะ: bool, ColorFormat, float, int, string. อ่าน/เขียน Object.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

สูตรภายในค่า, from, to, by attributes สามารถประกอบด้วยสิ่งต่อไปนี้: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" อ่าน/เขียน String.

**คืนค่า:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

สูตรภายในค่า, from, to, by attributes สามารถประกอบด้วยสิ่งต่อไปนี้: Standard arithmetic operators: '+', '-', '*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" อ่าน/เขียน String.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | java.lang.String |  |