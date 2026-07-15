---
title: PdfImportOptions
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn các tùy chọn nhập PDF
type: docs
url: /vi/com.aspose.slides/pdfimportoptions/
---
**Kế thừa:**
java.lang.Object
```
public class PdfImportOptions
```

Biểu diễn các tùy chọn nhập PDF
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Xác định có phát hiện bảng khi nhập tệp PDF hay không. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Xác định có phát hiện bảng khi nhập tệp PDF hay không. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Xác định có phát hiện bảng khi nhập tệp PDF hay không.

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
>          // đặt phát hiện bảng
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Trả về:**
boolean
### setDetectTables(boolean value) {#setDetectTables-boolean-}
```
public final void setDetectTables(boolean value)
```


Xác định có phát hiện bảng khi nhập tệp PDF hay không.

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
>          // đặt phát hiện bảng
>          pres.getSlides().addFromPdf(stream, pdfImportOptions);
>      }
> 
>      pres.save("fromPdfDocument.pptx", SaveFormat.Pptx);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |