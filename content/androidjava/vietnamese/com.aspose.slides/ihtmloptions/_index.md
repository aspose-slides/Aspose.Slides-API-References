---
title: IHtmlOptions
second_title: Tham chiếu API Java cho Aspose.Slides trên Android
description: Biểu diễn các tùy chọn xuất HTML.
type: docs
url: /vi/com.aspose.slides/ihtmloptions/
---
**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IHtmlOptions extends ISaveOptions
```

Biểu diễn các tùy chọn xuất HTML.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getHtmlFormatter()](#getHtmlFormatter--) | Trả về hoặc đặt mẫu HTML. |
| [setHtmlFormatter(IHtmlFormatter value)](#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-) | Trả về hoặc đặt mẫu HTML. |
| [getSlideImageFormat()](#getSlideImageFormat--) | Trả về hoặc đặt các tùy chọn định dạng hình ảnh slide. |
| [setSlideImageFormat(ISlideImageFormat value)](#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-) | Trả về hoặc đặt các tùy chọn định dạng hình ảnh slide. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. |
| [getJpegQuality()](#getJpegQuality--) | Trả về hoặc đặt giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. |
| [setJpegQuality(byte value)](#setJpegQuality-byte-) | Trả về hoặc đặt giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. |
| [getPicturesCompression()](#getPicturesCompression--) | Biểu diễn mức nén hình ảnh Đọc/ghi [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [setPicturesCompression(int value)](#setPicturesCompression-int-) | Biểu diễn mức nén hình ảnh Đọc/ghi [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)). |
| [getDeletePicturesCroppedAreas()](#getDeletePicturesCroppedAreas--) | Cờ boolean cho biết nếu các phần đã cắt còn lại như một phần của tài liệu. |
| [setDeletePicturesCroppedAreas(boolean value)](#setDeletePicturesCroppedAreas-boolean-) | Cờ boolean cho biết nếu các phần đã cắt còn lại như một phần của tài liệu. |
| [getSvgResponsiveLayout()](#getSvgResponsiveLayout--) | Đúng để loại bỏ các thuộc tính width và height khỏi container SVG - sẽ làm bố cục đáp ứng. |
| [setSvgResponsiveLayout(boolean value)](#setSvgResponsiveLayout-boolean-) | Đúng để loại bỏ các thuộc tính width và height khỏi container SVG - sẽ làm bố cục đáp ứng. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Lấy hoặc đặt giá trị cho biết văn bản có được hiển thị mà không sử dụng ligature hay không. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Lấy hoặc đặt giá trị cho biết văn bản có được hiển thị mà không sử dụng ligature hay không. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất. |

### getHtmlFormatter() {#getHtmlFormatter--}
```
public abstract IHtmlFormatter getHtmlFormatter()
```

Trả về hoặc đặt mẫu HTML. Đọc/ghi [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Trả về:**
[IHtmlFormatter](../../com.aspose.slides/ihtmlformatter)

### setHtmlFormatter(IHtmlFormatter value) {#setHtmlFormatter-com.aspose.slides.IHtmlFormatter-}
```
public abstract void setHtmlFormatter(IHtmlFormatter value)
```

Trả về hoặc đặt mẫu HTML. Đọc/ghi [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IHtmlFormatter](../../com.aspose.slides/ihtmlformatter) |  |

### getSlideImageFormat() {#getSlideImageFormat--}
```
public abstract ISlideImageFormat getSlideImageFormat()
```

Trả về hoặc đặt các tùy chọn định dạng hình ảnh slide. Đọc/ghi [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Trả về:**
[ISlideImageFormat](../../com.aspose.slides/islideimageformat)

### setSlideImageFormat(ISlideImageFormat value) {#setSlideImageFormat-com.aspose.slides.ISlideImageFormat-}
```
public abstract void setSlideImageFormat(ISlideImageFormat value)
```

Trả về hoặc đặt các tùy chọn định dạng hình ảnh slide. Đọc/ghi [ISlideImageFormat](../../com.aspose.slides/islideimageformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISlideImageFormat](../../com.aspose.slides/islideimageformat) |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là false.

**Trả về:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract byte getJpegQuality()
```

Trả về hoặc đặt giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. Đọc/ghi byte.

--------------------

Chỉ có tác dụng khi tài liệu chứa hình ảnh JPEG.

Sử dụng thuộc tính này để lấy hoặc đặt chất lượng của các hình ảnh trong tài liệu khi lưu dưới định dạng PDF. Giá trị có thể nằm trong khoảng từ 0 đến 100, trong đó 0 nghĩa là chất lượng thấp nhất nhưng nén tối đa và 100 nghĩa là chất lượng tốt nhất nhưng nén tối thiểu.

Giá trị mặc định là **95**.

**Trả về:**
byte

### setJpegQuality(byte value) {#setJpegQuality-byte-}
```
public abstract void setJpegQuality(byte value)
```

Trả về hoặc đặt giá trị xác định chất lượng của các hình ảnh JPEG trong tài liệu PDF. Đọc/ghi byte.

--------------------

Chỉ có tác dụng khi tài liệu chứa hình ảnh JPEG.

Sử dụng thuộc tính này để lấy hoặc đặt chất lượng của các hình ảnh trong tài liệu khi lưu dưới định dạng PDF. Giá trị có thể nằm trong khoảng từ 0 đến 100, trong đó 0 nghĩa là chất lượng thấp nhất nhưng nén tối đa và 100 nghĩa là chất lượng tốt nhất nhưng nén tối thiểu.

Giá trị mặc định là **95**.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getPicturesCompression() {#getPicturesCompression--}
```
public abstract int getPicturesCompression()
```

Biểu diễn mức nén hình ảnh Đọc/ghi [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Trả về:**
int

### setPicturesCompression(int value) {#setPicturesCompression-int-}
```
public abstract void setPicturesCompression(int value)
```

Biểu diễn mức nén hình ảnh Đọc/ghi [PicturesCompression](../../com.aspose.slides/picturescompression)(\#getPicturesCompression.getPicturesCompression/\#setPicturesCompression(int).setPicturesCompression(int)).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getDeletePicturesCroppedAreas() {#getDeletePicturesCroppedAreas--}
```
public abstract boolean getDeletePicturesCroppedAreas()
```

Cờ boolean cho biết nếu các phần đã cắt còn lại như một phần của tài liệu. Nếu true các phần đã cắt sẽ bị xóa, nếu false chúng sẽ được tuần tự hoá trong tài liệu (có thể dẫn đến tệp lớn hơn) Đọc/ghi boolean.

**Trả về:**
boolean

### setDeletePicturesCroppedAreas(boolean value) {#setDeletePicturesCroppedAreas-boolean-}
```
public abstract void setDeletePicturesCroppedAreas(boolean value)
```

Cờ boolean cho biết nếu các phần đã cắt còn lại như một phần của tài liệu. Nếu true các phần đã cắt sẽ bị xóa, nếu false chúng sẽ được tuần tự hoá trong tài liệu (có thể dẫn đến tệp lớn hơn) Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSvgResponsiveLayout() {#getSvgResponsiveLayout--}
```
public abstract boolean getSvgResponsiveLayout()
```

Đúng để loại bỏ các thuộc tính width và height khỏi container SVG - sẽ làm bố cục đáp ứng. Sai - ngược lại. Đọc/ghi boolean.

**Trả về:**
boolean

### setSvgResponsiveLayout(boolean value) {#setSvgResponsiveLayout-boolean-}
```
public abstract void setSvgResponsiveLayout(boolean value)
```

Đúng để loại bỏ các thuộc tính width và height khỏi container SVG - sẽ làm bố cục đáp ứng. Sai - ngược lại. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Lấy hoặc đặt giá trị cho biết văn bản có được hiển thị mà không sử dụng ligature hay không. Khi đặt thành true, các ligature sẽ bị tắt trong kết quả hiển thị. Mặc định, thuộc tính này được đặt là false.

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
public abstract void setDisableFontLigatures(boolean value)
```

Lấy hoặc đặt giá trị cho biết văn bản có được hiển thị mà không sử dụng ligature hay không. Khi đặt thành true, các ligature sẽ bị tắt trong kết quả hiển thị. Mặc định, thuộc tính này được đặt là false.

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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu đã xuất. Chỉ đọc [IInkOptions](../../com.aspose.slides/iinkoptions)

**Trả về:**
[IInkOptions](../../com.aspose.slides/iinkoptions)