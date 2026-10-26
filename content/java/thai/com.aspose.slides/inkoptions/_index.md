---
title: InkOptions
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของอ็อบเจ็กต์ Ink ในเอกสารที่ส่งออก
type: docs
url: /th/com.aspose.slides/inkoptions/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่ทำการ Implement ทั้งหมด:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

ให้ตัวเลือกที่ควบคุมรูปลักษณ์ของอ็อบเจ็กต์ Ink ในเอกสารที่ส่งออก
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHideInk()](#getHideInk--) | แสดงหรือซ่อนองค์ประกอบ Ink ในเอกสารที่ส่งออก |
| [setHideInk(boolean value)](#setHideInk-boolean-) | แสดงหรือซ่อนองค์ประกอบ Ink ในเอกสารที่ส่งออก |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | ใช้การดำเนินการ ROP หรือความโปร่งแสงสำหรับการเรนเดอร์แปรง |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | ใช้การดำเนินการ ROP หรือความโปร่งแสงสำหรับการเรนเดอร์แปรง |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```

แสดงหรือซ่อนองค์ประกอบ Ink ในเอกสารที่ส่งออก

--------------------

> ```
> Next example demonstrates how to hide Ink elements in exported PDF document:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setHideInk(true);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

ค่าปริยายคือ false.

**คืนค่า:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```

แสดงหรือซ่อนองค์ประกอบ Ink ในเอกสารที่ส่งออก

--------------------

> ```
> Next example demonstrates how to hide Ink elements in exported PDF document:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setHideInk(true);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

ค่าปริยายคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```

ใช้การดำเนินการ ROP หรือความโปร่งแสงสำหรับการเรนเดอร์แปรง

--------------------

> ```
> Next example demonstrates how to set using ROP for expotring Ink elements:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setInterpretMaskOpAsOpacity(false);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

ค่าปริยายคือ true.

**คืนค่า:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```

ใช้การดำเนินการ ROP หรือความโปร่งแสงสำหรับการเรนเดอร์แปรง

--------------------

> ```
> Next example demonstrates how to set using ROP for expotring Ink elements:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      PdfOptions pdfOptions = new PdfOptions();
>      pdfOptions.getInkOptions().setInterpretMaskOpAsOpacity(false);
>      pres.save("output.pptx", SaveFormat.Pdf, pdfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

ค่าปริยายคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |