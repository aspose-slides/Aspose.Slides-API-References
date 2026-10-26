---
title: PdfImportOptions
second_title: อ้างอิง API ของ Aspose.Slides สำหรับ Java
description: แสดงตัวเลือกการนำเข้าฟอร์แมต PDF
type: docs
url: /th/com.aspose.slides/pdfimportoptions/
---
**การสืบทอด:**  
java.lang.Object  
```
public class PdfImportOptions
```

แสดงตัวเลือกการนำเข้าฟอร์แมต PDF  
## คอนสตรัคเตอร์

| คอนสตรัคเตอร์ | คำอธิบาย |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |

## เมธอด

| เมธอด | คำอธิบาย |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | กำหนดว่าจะตรวจจับตารางเมื่อทำการนำเข้าไฟล์ PDF หรือไม่ |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | กำหนดว่าจะตรวจจับตารางเมื่อทำการนำเข้าไฟล์ PDF หรือไม่ |

### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```

### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```

กำหนดว่าจะตรวจจับตารางเมื่อทำการนำเข้าไฟล์ PDF หรือไม่

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
>          // set detecting tables
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**ผลลัพธ์:**  
boolean

### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```

กำหนดว่าจะตรวจจับตารางเมื่อทำการนำเข้าไฟล์ PDF หรือไม่

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