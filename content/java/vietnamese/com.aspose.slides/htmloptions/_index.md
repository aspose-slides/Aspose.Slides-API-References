---
title: HtmlOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu diễn các tùy chọn xuất HTML.
type: docs
url: /vi/com.aspose.slides/htmloptions/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IHtmlOptions](../../com.aspose.slides/ihtmloptions)
```
public class HtmlOptions extends SaveOptions implements IHtmlOptions
```

Biểu diễn các tùy chọn xuất HTML.
## Các hàm tạo

| Constructor | Description |
| --- | --- |
| [HtmlOptions(ILinkEmbedController linkEmbedController)](#HtmlOptions-com.aspose.slides.ILinkEmbedController-) | Tạo một đối tượng HtmlOptions mới chỉ định callback. |
| [HtmlOptions()](#HtmlOptions--) | Tạo một đối tượng HtmlOptions mới để lưu thành một tệp HTML duy nhất. |
## Phương thức

| Method | Description |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất một bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất một bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Chỉ định xem tài liệu được tạo có nên bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Chỉ định xem tài liệu được tạo có nên bao gồm các slide ẩn hay không. |
| [getHtmlFormatter()](#getHtmlFormatter--) | Trả về hoặc đặt mẫu HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Trả về hoặc đặt mẫu HTML. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Lấy hoặc đặt giá trị cho biết văn bản có được hiển thị mà không sử dụng ligature hay không. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Lấy hoặc đặt giá trị cho biết văn bản có được hiển thị mà không sử dụng ligature hay không. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Trả về hoặc đặt các tùy chọn định dạng ảnh slide. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Trả về hoặc đặt các tùy chọn định dạng ảnh slide. |
| [getJpegQuality()](#getJpegQuality--) | Trả về hoặc đặt giá trị xác định chất lượng của các ảnh JPEG trong tài liệu PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Trả về hoặc đặt giá trị xác định chất lượng của các ảnh JPEG trong tài liệu PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Biểu diễn mức độ nén hình ảnh |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Biểu diễn mức độ nén hình ảnh |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Cờ boolean cho biết các phần đã cắt có còn là một phần của tài liệu hay không. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Cờ boolean cho biết các phần đã cắt có còn là một phần của tài liệu hay không. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Đặt true để loại bỏ các thuộc tính width và height khỏi container svg - sẽ làm bố cục đáp ứng. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Đặt true để loại bỏ các thuộc tính width và height khỏi container svg - sẽ làm bố cục đáp ứng. |
### HtmlOptions(ILinkEmbedController linkEmbedController) {#HtmlOptions-com.aspose.slides.ILinkEmbedController-}
```
public HtmlOptions(ILinkEmbedController linkEmbedController)
```

Tạo một đối tượng HtmlOptions mới chỉ định callback.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| linkEmbedController | [ILinkEmbedController](../../com.aspose.slides/ilinkembedcontroller) | Đối tượng callback kiểm soát việc lưu dự án. |

### HtmlOptions() {#HtmlOptions--}
```
public HtmlOptions()
```

Tạo một đối tượng HtmlOptions mới để lưu thành một tệp HTML duy nhất.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất một bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
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

Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất một bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất. Chỉ đọc [IInkOptions](../../com.aspose.slides/iinkoptions)

**Trả về:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Chỉ định xem tài liệu được tạo có nên bao gồm các slide ẩn hay không. Mặc định là false.

**Trả về:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Chỉ định xem tài liệu được tạo có nên bao gồm các slide ẩn hay không. Mặc định là false.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public final IHtmlFormatter getHtmlFormatter()
```

Trả về hoặc đặt mẫu HTML. Đọc/ghi [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Trả về:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)
### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public final void setHtmlFormatter(IHtmlFormatter value)
```

Trả về hoặc đặt mẫu HTML. Đọc/ghi [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

Lấy hoặc đặt giá trị cho biết văn bản có được hiển thị mà không sử dụng ligature hay không. Khi đặt là true, các ligature sẽ bị tắt trong đầu ra đã render. Mặc định, thuộc tính này được đặt là false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
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

Lấy hoặc đặt giá trị cho biết văn bản có được hiển thị mà không sử dụng ligature hay không. Khi đặt là true, các ligature sẽ bị tắt trong đầu ra đã render. Mặc định, thuộc tính này được đặt là false.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      HtmlOptions options = new HtmlOptions();
>      options.setDisableFontLigatures(true);
>      pres.save("presentation.html", SaveFormat.Html, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public final ISlideImageFormat getSlideImageFormat()
```

Trả về hoặc đặt các tùy chọn định dạng ảnh slide. Đọc/ghi [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Trả về:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)
### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public final void setSlideImageFormat(ISlideImageFormat value)
```

Trả về hoặc đặt các tùy chọn định dạng ảnh slide. Đọc/ghi [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getJpegQuality() {#getJpegQuality--}
```
public final byte getJpegQuality()
```

Trả về hoặc đặt giá trị xác định chất lượng của các ảnh JPEG trong tài liệu PDF. Đọc/ghi byte.

--------------------

Có hiệu lực chỉ khi tài liệu chứa ảnh JPEG.

Sử dụng thuộc tính này để lấy hoặc đặt chất lượng của các ảnh trong tài liệu khi lưu ở định dạng PDF. Giá trị có thể từ 0 đến 100, trong đó 0 có nghĩa là chất lượng kém nhất nhưng nén tối đa và 100 có nghĩa là chất lượng tốt nhất nhưng nén tối thiểu.

Giá trị mặc định là **95**.

**Trả về:**
byte
### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public final void setJpegQuality(byte value)
```

Trả về hoặc đặt giá trị xác định chất lượng của các ảnh JPEG trong tài liệu PDF. Đọc/ghi byte.

--------------------

Có hiệu lực chỉ khi tài liệu chứa ảnh JPEG.

Sử dụng thuộc tính này để lấy hoặc đặt chất lượng của các ảnh trong tài liệu khi lưu ở định dạng PDF. Giá trị có thể từ 0 đến 100, trong đó 0 có nghĩa là chất lượng kém nhất nhưng nén tối đa và 100 có nghĩa là chất lượng tốt nhất nhưng nén tối thiểu.

Giá trị mặc định là **95**.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public final int getPicturesCompression()
```

Biểu diễn mức độ nén hình ảnh

**Trả về:**
int
### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public final void setPicturesCompression(int value)
```

Biểu diễn mức độ nén hình ảnh

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public final boolean getDeletePicturesCroppedAreas()
```

Cờ boolean cho biết các phần đã cắt có còn là một phần của tài liệu hay không. Nếu true các phần đã cắt sẽ bị xóa, nếu false chúng sẽ được tuần tự hoá trong tài liệu (có thể dẫn đến tệp lớn hơn).

**Trả về:**
boolean
### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public final void setDeletePicturesCroppedAreas(boolean value)
```

Cờ boolean cho biết các phần đã cắt có còn là một phần của tài liệu hay không. Nếu true các phần đã cắt sẽ bị xóa, nếu false chúng sẽ được tuần tự hoá trong tài liệu (có thể dẫn đến tệp lớn hơn).

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public final boolean getSvgResponsiveLayout()
```

Đặt true để loại bỏ các thuộc tính width và height khỏi container svg - sẽ làm bố cục đáp ứng. False - ngược lại. Đọc/ghi boolean.

**Trả về:**
boolean
### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public final void setSvgResponsiveLayout(boolean value)
```

Đặt true để loại bỏ các thuộc tính width và height khỏi container svg - sẽ làm bố cục đáp ứng. False - ngược lại. Đọc/ghi boolean.

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |