---
title: PdfImportOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị các tùy chọn nhập PDF
type: docs
url: /vi/com.aspose.slides/pdfimportoptions/
---
**Kế thừa:**
java.lang.Object
```
public class PdfImportOptions
```

Biểu thị các tùy chọn nhập PDF
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [PdfImportOptions()](#PdfImportOptions--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getDetectTables()](#getDetectTables--) | Xác định xem có phát hiện bảng khi nhập tệp pdf hay không. |
| [setDetectTables(boolean value)](#setDetectTables-boolean-) | Xác định xem có phát hiện bảng khi nhập tệp pdf hay không. |
### PdfImportOptions() {#PdfImportOptions--}
```
public PdfImportOptions()
```


### getDetectTables() {#getDetectTables--}
```
public final boolean getDetectTables()
```


Xác định xem có phát hiện bảng khi nhập tệp pdf hay không.

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


Xác định xem có phát hiện bảng khi nhập tệp pdf hay không.

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