---
title: PdfImportOptions
second_title: Aspose.Slides สำหรับ Android ผ่าน Java API Reference
description: แสดงตัวเลือกการนำเข้า PDF
type: docs
url: /th/com.aspose.slides/pdfimportoptions/
---
**การสืบทอด:**  
java.lang.Object
```
public class PdfImportOptions
```

แสดงตัวเลือกการนำเข้า PDF
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | กำหนดว่าควรตรวจจับตารางเมื่อทำการนำเข้าไฟล์ pdf หรือไม่. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | กำหนดว่าควรตรวจจับตารางเมื่อทำการนำเข้าไฟล์ pdf หรือไม่. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```

### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```

กำหนดว่าควรตรวจจับตารางเมื่อทำการนำเข้าไฟล์ pdf หรือไม่.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      {
>          // ตั้งค่าการตรวจจับตาราง
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**คืนค่า:**  
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
``` 
public final void setDetectTables(boolean value)
```

กำหนดว่าควรตรวจจับตารางเมื่อทำการนำเข้าไฟล์ pdf หรือไม่.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      PdfImportOptions pdfImportOptions = new PdfImportOptions();
>      pdfImportOptions.setDetectTables(true);
> 
>      FileInputStream stream = new FileInputStream("document.pdf");
>      {
>          // ตั้งค่าการตรวจจับตาราง
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**พารามิเตอร์:**
| พารามิเตอร์ | ประเภท | คำอธิบาย |
| --- | --- | --- |
| value | boolean |  |