---
title: ColorOperation
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงถึงการดำเนินการสีต่าง ๆ ที่ใช้สำหรับการแปลงสี.
type: docs
url: /th/com.aspose.slides/coloroperation/
---
**การสืบทอด:**
java.lang.Object

**ทุกอินเทอร์เฟซที่ทำการนำเข้า:**
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)
```
public class ColorOperation implements IColorOperation
```

แทนการดำเนินการสีต่าง ๆ ที่ใช้สำหรับการแปลงสี. วัตถุที่ไม่สามารถเปลี่ยนแปลงได้.
## ตัวสร้าง

| ตัวสร้าง | คำอธิบาย |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | สร้างการดำเนินการการแปลงสีใหม่. |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | สร้างการดำเนินการการแปลงสีใหม่. |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getOperationType()](#getOperationType--) | คืนค่า หรือ ตั้งค่าประเภทของการดำเนินการ. |
| [getParameter()](#getParameter--) | คืนค่าพารามิเตอร์ของการดำเนินการ. |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าตัวอย่าง ColorOperation สองตัวเท่ากันหรือไม่. |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่ง, เหมาะสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช. |
### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```


สร้างการดำเนินการการแปลงสีใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| op | int | ประเภทการดำเนินการ. |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```


สร้างการดำเนินการการแปลงสีใหม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| op | int | ประเภทการดำเนินการ. |
| parameter | float | พารามิเตอร์การดำเนินการ. |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```


คืนค่า หรือ ตั้งค่าประเภทของการดำเนินการ. อ่านอย่างเดียว [ColorTransformOperation](../../com.aspose.slides/colortransformoperation).

**คืนค่า:**
int
### getParameter() {#getParameter--}
```
public final float getParameter()
```


คืนค่าพารามิเตอร์ของการดำเนินการ. อ่านอย่างเดียว float.

**คืนค่า:**
float
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


กำหนดว่าตัวอย่าง ColorOperation สองตัวเท่ากันหรือไม่.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| obj | java.lang.Object | ColorOperation ที่จะเปรียบเทียบกับ ColorOperation ปัจจุบัน. |

**คืนค่า:**
boolean - **true** หาก ColorOperation ที่ระบุเท่ากับ ColorOperation ปัจจุบัน; มิฉะนั้น, **false**.
### hashCode() {#hashCode--}
```
public int hashCode()
```


ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทหนึ่ง, เหมาะสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช.

**คืนค่า:**
int