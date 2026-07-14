---
title: InkOptions
second_title: Aspose.Slides สำหรับ Android ผ่านการอ้างอิง API ของ Java
description: ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก
type: docs
url: /th/com.aspose.slides/inkoptions/
---
**การสืบทอด:**
java.lang.Object

**อินเทอร์เฟซที่นำไปใช้ทั้งหมด:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

ให้ตัวเลือกที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHideInk()](#getHideInk--) | แสดงหรือซ่อนองค์ประกอบ Ink ในเอกสารที่ส่งออก |
| [setHideInk(boolean value)](#setHideInk-boolean-) | แสดงหรือซ่อนองค์ประกอบ Ink ในเอกสารที่ส่งออก |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | ใช้การดำเนินการ ROP หรือ Opacity สำหรับการเรนเดอร์แปรง |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | ใช้การดำเนินการ ROP หรือ Opacity สำหรับการเรนเดอร์แปรง |
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

ค่าเริ่มต้นคือ false.

**ผลลัพธ์:**
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

ค่าเริ่มต้นคือ false.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |
### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```

ใช้การดำเนินการ ROP หรือ Opacity สำหรับการเรนเดอร์แปรง

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

ค่าเริ่มต้นคือ true.

**ผลลัพธ์:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```

ใช้การดำเนินการ ROP หรือ Opacity สำหรับการเรนเดอร์แปรง

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

ค่าเริ่มต้นคือ true.

**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |