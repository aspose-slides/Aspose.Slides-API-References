---
title: ISaveOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Các tùy chọn kiểm soát cách một bản trình chiếu được lưu.
type: docs
url: /vi/com.aspose.slides/isaveoptions/
---```
public interface ISaveOptions
```

Các tùy chọn kiểm soát cách một bản trình chiếu được lưu.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy. |
| [getProgressCallback()](#getProgressCallback--) | Biểu diễn một đối tượng callback cho việc cập nhật tiến độ lưu dưới dạng phần trăm. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Biểu diễn một đối tượng callback cho việc cập nhật tiến độ lưu dưới dạng phần trăm. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Trả về hoặc đặt phông chữ được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Trả về hoặc đặt phông chữ được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. |
| [getGradientStyle()](#getGradientStyle--) | Trả về hoặc đặt kiểu hiển thị của gradient. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Trả về hoặc đặt kiểu hiển thị của gradient. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Xác định xem có bỏ qua các liên kết siêu văn bản có lệnh JavaScript khi lưu bản trình chiếu hay không. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Xác định xem có bỏ qua các liên kết siêu văn bản có lệnh JavaScript khi lưu bản trình chiếu hay không. |
### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy. Đọc/ghi [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Trả về:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Trả về hoặc đặt một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy. Đọc/ghi [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |
### getProgressCallback() {#getProgressCallback--}
```
public abstract IProgressCallback getProgressCallback()
```

Biểu diễn một đối tượng callback cho việc cập nhật tiến độ lưu dưới dạng phần trăm. Xem [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Trả về:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public abstract void setProgressCallback(IProgressCallback value)
```

Biểu diễn một đối tượng callback cho việc cập nhật tiến độ lưu dưới dạng phần trăm. Xem [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |
### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Trả về hoặc đặt phông chữ được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. Đọc/ghi String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
java.lang.String
### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Trả về hoặc đặt phông chữ được sử dụng trong trường hợp không tìm thấy phông chữ nguồn. Đọc/ghi String.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try
>  {
>      HtmlOptions htmlOpts = new HtmlOptions();
>      htmlOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.html", SaveFormat.Html, htmlOpts);
>      htmlOpts.setDefaultRegularFont("Lucida Console");
>      pres.save("Somepresentation-out-LucidaConsole.html", SaveFormat.Html, htmlOpts);
>      PdfOptions pdfOpts = new PdfOptions();
>      pdfOpts.setDefaultRegularFont("Arial Black");
>      pres.save("SomePresentation-out-ArialBlack.pdf", SaveFormat.Pdf, pdfOpts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getGradientStyle() {#getGradientStyle--}
```
public abstract int getGradientStyle()
```

Trả về hoặc đặt kiểu hiển thị của gradient. Đọc/ghi [GradientStyle](../../com.aspose.slides/gradientstyle).

**Trả về:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public abstract void setGradientStyle(int value)
```

Trả về hoặc đặt kiểu hiển thị của gradient. Đọc/ghi [GradientStyle](../../com.aspose.slides/gradientstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public abstract boolean getSkipJavaScriptLinks()
```

Xác định xem có bỏ qua các liên kết siêu văn bản có lệnh JavaScript khi lưu bản trình chiếu hay không. Đọc/ghi boolean. Giá trị mặc định là false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Khi thuộc tính này được đặt thành true, các liên kết siêu văn bản có lệnh JavaScript sẽ bị bỏ qua khi lưu.

Khi thuộc tính này được đặt thành false, tất cả các liên kết siêu văn bản sẽ được lưu.

**Trả về:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public abstract void setSkipJavaScriptLinks(boolean value)
```

Xác định xem có bỏ qua các liên kết siêu văn bản có lệnh JavaScript khi lưu bản trình chiếu hay không. Đọc/ghi boolean. Giá trị mặc định là false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      HtmlOptions htmlOptions = new HtmlOptions();
>      htmlOptions.setSkipJavaScriptLinks(true);
>      pres.save("result_without_JavaScript_links.html", SaveFormat.Html, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Khi thuộc tính này được đặt thành true, các liên kết siêu văn bản có lệnh JavaScript sẽ bị bỏ qua khi lưu.

Khi thuộc tính này được đặt thành false, tất cả các liên kết siêu văn bản sẽ được lưu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |