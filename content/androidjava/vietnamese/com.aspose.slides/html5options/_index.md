---
title: Html5Options
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Đại diện cho các tùy chọn xuất HTML5.
type: docs
url: /vi/com.aspose.slides/html5options/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IHtml5Options](../../com.aspose.slides/ihtml5options)
```
public class Html5Options extends SaveOptions implements IHtml5Options
```

Đại diện cho các tùy chọn xuất HTML5.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-shapes-and-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [Html5Options()](#Html5Options--) | Hàm tạo mặc định. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAnimateTransitions()](#getAnimateTransitions--) | Trả về hoặc đặt tùy chọn hoạt ảnh chuyển đổi. |
| [setAnimateTransitions(boolean value)](#setAnimateTransitions-boolean-) | Trả về hoặc đặt tùy chọn hoạt ảnh chuyển đổi. |
| [getAnimateShapes()](#getAnimateShapes--) | Trả về hoặc đặt tùy chọn hoạt ảnh hình dạng. |
| [setAnimateShapes(boolean value)](#setAnimateShapes-boolean-) | Trả về hoặc đặt tùy chọn hoạt ảnh hình dạng. |
| [getEmbedImages()](#getEmbedImages--) | Trả về hoặc đặt tùy chọn nhúng hình ảnh. |
| [setEmbedImages(boolean value)](#setEmbedImages-boolean-) | Trả về hoặc đặt tùy chọn nhúng hình ảnh. |
| [getOutputPath()](#getOutputPath--) | Xác định vị trí lưu trữ tài nguyên bên ngoài. |
| [setOutputPath(String value)](#setOutputPath-java.lang.String-) | Xác định vị trí lưu trữ tài nguyên bên ngoài. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Lấy hoặc đặt giá trị chỉ ra liệu văn bản có được hiển thị mà không sử dụng ligature hay không. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Lấy hoặc đặt giá trị chỉ ra liệu văn bản có được hiển thị mà không sử dụng ligature hay không. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bài thuyết trình [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bài thuyết trình [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### Html5Options() {#Html5Options--}
```
public Html5Options()
```


Hàm tạo mặc định.

### getAnimateTransitions() {#getAnimateTransitions--}
```
public final boolean getAnimateTransitions()
```


Trả về hoặc đặt tùy chọn hoạt ảnh chuyển đổi. Đọc/ghi boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
boolean
### setAnimateTransitions(boolean value) {#setAnimateTransitions-boolean-}
```
public final void setAnimateTransitions(boolean value)
```


Trả về hoặc đặt tùy chọn hoạt ảnh chuyển đổi. Đọc/ghi boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateTransitions(true);
> 
>      pres.save("demo-animate-transitions.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getAnimateShapes() {#getAnimateShapes--}
```
public final boolean getAnimateShapes()
```


Trả về hoặc đặt tùy chọn hoạt ảnh hình dạng. Đọc/ghi boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
boolean
### setAnimateShapes(boolean value) {#setAnimateShapes-boolean-}
```
public final void setAnimateShapes(boolean value)
```


Trả về hoặc đặt tùy chọn hoạt ảnh hình dạng. Đọc/ghi boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options htmlOptions = new Html5Options();
>      htmlOptions.setAnimateShapes(true);
> 
>      pres.save("demo-animate-shapes.html", SaveFormat.Html5, htmlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getEmbedImages() {#getEmbedImages--}
```
public final boolean getEmbedImages()
```


Trả về hoặc đặt tùy chọn nhúng hình ảnh. Đọc/ghi boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
boolean
### setEmbedImages(boolean value) {#setEmbedImages-boolean-}
```
public final void setEmbedImages(boolean value)
```


Trả về hoặc đặt tùy chọn nhúng hình ảnh. Đọc/ghi boolean.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getOutputPath() {#getOutputPath--}
```
public final String getOutputPath()
```


Xác định vị trí lưu trữ tài nguyên bên ngoài. Đọc/ghi String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
java.lang.String
### setOutputPath(String value) {#setOutputPath-java.lang.String-}
```
public final void setOutputPath(String value)
```


Xác định vị trí lưu trữ tài nguyên bên ngoài. Đọc/ghi String.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      Html5Options html5Options = new Html5Options();
>      html5Options.setEmbedImages(false);
>      html5Options.setOutputPath(the_desired_path);
>      pres.save("demo-linked-images.html", SaveFormat.Html5, html5Options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


Lấy hoặc đặt giá trị chỉ ra liệu văn bản có được hiển thị mà không sử dụng ligature hay không. Khi đặt thành true, các ligature sẽ bị tắt trong đầu ra được hiển thị. Mặc định, thuộc tính này được đặt là false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Vô hiệu hoá ligature trong việc hiển thị văn bản
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```


Lấy hoặc đặt giá trị chỉ ra liệu văn bản có được hiển thị mà không sử dụng ligature hay không. Khi đặt thành true, các ligature sẽ bị tắt trong đầu ra được hiển thị. Mặc định, thuộc tính này được đặt là false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      Html5Options options = new Html5Options();
>      options.setDisableFontLigatures(true); // Vô hiệu hoá ligature trong việc hiển thị văn bản
> 
>      pres.save("output.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bài thuyết trình [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Trả về:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bài thuyết trình [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HandoutLayoutingOptions handoutLayoutingOptions = new HandoutLayoutingOptions();
>      handoutLayoutingOptions.setHandout(HandoutType.Handouts4Horizontal);
>      Html5Options options = new Html5Options();
>      options.setSlidesLayoutOptions(handoutLayoutingOptions);
> 
>      pres.save("pres.html", SaveFormat.Html5, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |