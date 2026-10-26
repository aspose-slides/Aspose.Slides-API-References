---
title: IInkOptions
second_title: Aspose.Slides for Java API Reference
description: จัดหาออปชันที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก.
type: docs
url: /th/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

จัดหาออปชันที่ควบคุมลักษณะของวัตถุ Ink ในเอกสารที่ส่งออก.
## วิธีการ

| เมธอด | คำอธิบาย |
| --- | --- |
| [getHideInk()](#getHideInk--) | แสดงหรือซ่อนองค์ประกอบ Ink ในเอกสารที่ส่งออก. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | แสดงหรือซ่อนองค์ประกอบ Ink ในเอกสารที่ส่งออก. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | ใช้การดำเนินการ ROP หรือความทึบแสงสำหรับการเรนเดอร์แปรง. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | ใช้การดำเนินการ ROP หรือความทึบแสงสำหรับการเรนเดอร์แปรง. |
### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
```

แสดงหรือซ่อนองค์ประกอบ Ink ในเอกสารที่ส่งออก.

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
public abstract void setHideInk(boolean value)
```

แสดงหรือซ่อนองค์ประกอบ Ink ในเอกสารที่ส่งออก.

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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |

### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public abstract boolean getInterpretMaskOpAsOpacity()
```

ใช้การดำเนินการ ROP หรือความทึบแสงสำหรับการเรนเดอร์แปรง.

--------------------

> ```
> Next example demonstrates how to set using ROP for exporting Ink elements:
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
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```

ใช้การดำเนินการ ROP หรือความทึบแสงสำหรับการเรนเดอร์แปรง.

--------------------

> ```
> Next example demonstrates how to set using ROP for exporting Ink elements:
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
| พารามิเตอร์ | ชนิด | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |