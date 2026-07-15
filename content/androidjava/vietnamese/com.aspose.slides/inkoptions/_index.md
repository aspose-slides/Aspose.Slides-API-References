---
title: InkOptions
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất.
type: docs
url: /vi/com.aspose.slides/inkoptions/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IInkOptions](../../com.aspose.slides/iinkoptions)
```
public class InkOptions implements IInkOptions
```

Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHideInk()](#getHideInk--) | Hiển thị hoặc ẩn các phần tử Ink trong tài liệu đã xuất. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Hiển thị hoặc ẩn các phần tử Ink trong tài liệu đã xuất. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Sử dụng phép toán ROP hoặc Opacity để vẽ brush. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Sử dụng phép toán ROP hoặc Opacity để vẽ brush. |
### getHideInk() {#getHideInk--}
```
public final boolean getHideInk()
```

Hiển thị hoặc ẩn các phần tử Ink trong tài liệu đã xuất.

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

Giá trị mặc định là false.

**Trả về:**
boolean
### setHideInk(boolean value) {#setHideInk-boolean-}
```
public final void setHideInk(boolean value)
```

Hiển thị hoặc ẩn các phần tử Ink trong tài liệu đã xuất.

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

Giá trị mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getInterpretMaskOpAsOpacity() {#getInterpretMaskOpAsOpacity--}
```
public final boolean getInterpretMaskOpAsOpacity()
```

Sử dụng phép toán ROP hoặc Opacity để vẽ brush.

--------------------

> ```
> Ví dụ tiếp theo minh họa cách thiết lập sử dụng ROP để xuất các phần tử Ink:
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

Giá trị mặc định là true.

**Trả về:**
boolean
### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public final void setInterpretMaskOpAsOpacity(boolean value)
```

Sử dụng phép toán ROP hoặc Opacity để vẽ brush.

--------------------

> ```
> Ví dụ tiếp theo minh họa cách thiết lập sử dụng ROP để xuất các phần tử Ink:
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

Giá trị mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |