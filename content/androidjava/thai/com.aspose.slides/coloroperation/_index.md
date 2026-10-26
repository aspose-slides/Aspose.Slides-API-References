---
title: ColorOperation
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Android ผ่าน Java
description: แสดงการดำเนินการสีที่แตกต่างกันที่ใช้สำหรับการแปลงสี
type: docs
url: /th/com.aspose.slides/coloroperation/
---
**Inheritance:**  
การสืบทอด

**All Implemented Interfaces:**  
[com.aspose.slides.IColorOperation](../../com.aspose.slides/icoloroperation)  
```
public class ColorOperation implements IColorOperation
```

แทนการทำงานสีที่แตกต่างกันที่ใช้สำหรับการแปลงสี อ็อบเจ็กต์ไม่เปลี่ยนแปลง

## ตัวสร้าง

| Constructor | Description |
| --- | --- |
| [ColorOperation(int op)](#ColorOperation-int-) | สร้างการดำเนินการแปลงสีใหม่ |
| [ColorOperation(int op, float parameter)](#ColorOperation-int-float-) | สร้างการดำเนินการแปลงสีใหม่ |

## วิธีการ

| Method | Description |
| --- | --- |
| [getOperationType()](#getOperationType--) | คืนหรือกำหนดประเภทของการดำเนินการ |
| [getParameter()](#getParameter--) | คืนค่าพารามิเตอร์ของการดำเนินการ |
| [equals(Object obj)](#equals-java.lang.Object-) | กำหนดว่าตัวอย่าง ColorOperation สองตัวเท่ากันหรือไม่ |
| [hashCode()](#hashCode--) | ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะที่เหมาะสมสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช |

### ColorOperation(int op) {#ColorOperation-int-}
```
public ColorOperation(int op)
```

สร้างการดำเนินการแปลงสีใหม่

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | int | ประเภทการดำเนินการ |

### ColorOperation(int op, float parameter) {#ColorOperation-int-float-}
```
public ColorOperation(int op, float parameter)
```

สร้างการดำเนินการแปลงสีใหม่

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| op | int | ประเภทการดำเนินการ |
| parameter | float | พารามิเตอร์การดำเนินการ |

### getOperationType() {#getOperationType--}
```
public final int getOperationType()
```

คืนหรือกำหนดประเภทของการดำเนินการ อ่านอย่างเดียว [ColorTransformOperation](../../com.aspose.slides/colortransformoperation)

**คืนค่า:**
int

### getParameter() {#getParameter--}
```
public final float getParameter()
```

คืนค่าพารามิเตอร์ของการดำเนินการ อ่านอย่างเดียว float

**คืนค่า:**
float

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

กำหนดว่าตัวอย่าง ColorOperation สองตัวเท่ากันหรือไม่

**พารามิเตอร์:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | ColorOperation ที่จะเปรียบเทียบกับ ColorOperation ปัจจุบัน |

**คืนค่า:**
boolean - **true** ถ้า ColorOperation ที่ระบุเท่ากับ ColorOperation ปัจจุบัน; มิฉะนั้น, **false**.

### hashCode() {#hashCode--}
```
public int hashCode()
```

ทำหน้าที่เป็นฟังก์ชันแฮชสำหรับประเภทเฉพาะที่เหมาะสมสำหรับใช้ในอัลกอริทึมแฮชและโครงสร้างข้อมูลเช่น ตารางแฮช

**คืนค่า:**
int