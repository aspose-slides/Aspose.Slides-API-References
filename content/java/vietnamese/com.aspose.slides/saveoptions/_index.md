---
title: SaveOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Lớp trừu tượng với các tùy chọn kiểm soát cách một bản trình bày được lưu.
type: docs
url: /vi/com.aspose.slides/saveoptions/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public abstract class SaveOptions implements ISaveOptions
```

Lớp trừu tượng với các tùy chọn kiểm soát cách một bản trình bày được lưu.
## Hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [SaveOptions()](#SaveOptions--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getWarningCallback()](#getWarningCallback--) | Trả về hoặc thiết lập một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Trả về hoặc thiết lập một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy. |
| [getProgressCallback()](#getProgressCallback--) | Đại diện cho một đối tượng callback để cập nhật tiến độ lưu dưới dạng phần trăm. |
| [setProgressCallback(IProgressCallback value)](#setProgressCallback-com.aspose.slides.IProgressCallback-) | Đại diện cho một đối tượng callback để cập nhật tiến độ lưu dưới dạng phần trăm. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Trả về hoặc thiết lập phông chữ được sử dụng trong trường hợp không tìm thấy phông nguồn. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Trả về hoặc thiết lập phông chữ được sử dụng trong trường hợp không tìm thấy phông nguồn. |
| [getGradientStyle()](#getGradientStyle--) | Trả về hoặc thiết lập kiểu hiển thị của gradient. |
| [setGradientStyle(int value)](#setGradientStyle-int-) | Trả về hoặc thiết lập kiểu hiển thị của gradient. |
| [getSkipJavaScriptLinks()](#getSkipJavaScriptLinks--) | Chỉ định liệu có bỏ qua các siêu liên kết có lời gọi JavaScript khi lưu bản trình bày hay không. |
| [setSkipJavaScriptLinks(boolean value)](#setSkipJavaScriptLinks-boolean-) | Chỉ định liệu có bỏ qua các siêu liên kết có lời gọi JavaScript khi lưu bản trình bày hay không. |
### SaveOptions() {#SaveOptions--}
```
public SaveOptions()
```


### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```


Trả về hoặc thiết lập một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy. Đọc/ghi [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Trả về:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)
### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```


Trả về hoặc thiết lập một đối tượng nhận cảnh báo và quyết định liệu quá trình tải sẽ tiếp tục hay bị hủy. Đọc/ghi [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getProgressCallback() {#getProgressCallback--}
```
public final IProgressCallback getProgressCallback()
```


Đại diện cho một đối tượng callback để cập nhật tiến độ lưu dưới dạng phần trăm. Xem [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Trả về:**
[IProgressCallback](../../com.aspose.slides/iprogresscallback)
### setProgressCallback(IProgressCallback value) {#setProgressCallback-com.aspose.slides.IProgressCallback-}
```
public final void setProgressCallback(IProgressCallback value)
```


Đại diện cho một đối tượng callback để cập nhật tiến độ lưu dưới dạng phần trăm. Xem [IProgressCallback](../../com.aspose.slides/iprogresscallback).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IProgressCallback](../../com.aspose.slides/iprogresscallback) |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```


Trả về hoặc thiết lập phông chữ được sử dụng trong trường hợp không tìm thấy phông nguồn. Đọc/ghi String.

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
public final void setDefaultRegularFont(String value)
```


Trả về hoặc thiết lập phông chữ được sử dụng trong trường hợp không tìm thấy phông nguồn. Đọc/ghi String.

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
public final int getGradientStyle()
```


Trả về hoặc thiết lập kiểu hiển thị của gradient. Đọc/ghi [GradientStyle](../../com.aspose.slides/gradientstyle).

**Trả về:**
int
### setGradientStyle(int value) {#setGradientStyle-int-}
```
public final void setGradientStyle(int value)
```


Trả về hoặc thiết lập kiểu hiển thị của gradient. Đọc/ghi [GradientStyle](../../com.aspose.slides/gradientstyle).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSkipJavaScriptLinks() {#getSkipJavaScriptLinks--}
```
public final boolean getSkipJavaScriptLinks()
```


Chỉ định liệu có bỏ qua các siêu liên kết có lời gọi JavaScript khi lưu bản trình bày hay không. Đọc/ghi boolean. Giá trị mặc định là false.

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

Khi thuộc tính này được đặt thành true, các siêu liên kết có lời gọi JavaScript sẽ bị bỏ qua khi lưu.

Khi thuộc tính này được đặt thành false, tất cả các siêu liên kết sẽ được lưu.

**Trả về:**
boolean
### setSkipJavaScriptLinks(boolean value) {#setSkipJavaScriptLinks-boolean-}
```
public final void setSkipJavaScriptLinks(boolean value)
```


Chỉ định liệu có bỏ qua các siêu liên kết có lời gọi JavaScript khi lưu bản trình bày hay không. Đọc/ghi boolean. Giá trị mặc định là false.

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

Khi thuộc tính này được đặt thành true, các siêu liên kết có lời gọi JavaScript sẽ bị bỏ qua khi lưu.

Khi thuộc tính này được đặt thành false, tất cả các siêu liên kết sẽ được lưu.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |