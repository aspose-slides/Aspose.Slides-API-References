---
title: IInkOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất.
type: docs
url: /vi/com.aspose.slides/iinkoptions/
---```
public interface IInkOptions
```

Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHideInk()](#getHideInk--) | Hiển thị hoặc ẩn các phần tử Ink trong tài liệu đã xuất. |
| [setHideInk(boolean value)](#setHideInk-boolean-) | Hiển thị hoặc ẩn các phần tử Ink trong tài liệu đã xuất. |
| [getInterpretMaskOpAsOpacity()](#getInterpretMaskOpAsOpacity--) | Sử dụng thao tác ROP hoặc Opacity để render brush. |
| [setInterpretMaskOpAsOpacity(boolean value)](#setInterpretMaskOpAsOpacity-boolean-) | Sử dụng thao tác ROP hoặc Opacity để render brush. |

### getHideInk() {#getHideInk--}
```
public abstract boolean getHideInk()
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
public abstract void setHideInk(boolean value)
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
public abstract boolean getInterpretMaskOpAsOpacity()
```

Sử dụng thao tác ROP hoặc Opacity để render brush.

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

Giá trị mặc định là true.

**Trả về:**  
boolean

### setInterpretMaskOpAsOpacity(boolean value) {#setInterpretMaskOpAsOpacity-boolean-}
```
public abstract void setInterpretMaskOpAsOpacity(boolean value)
```

Sử dụng thao tác ROP hoặc Opacity để render brush.

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

Giá trị mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |