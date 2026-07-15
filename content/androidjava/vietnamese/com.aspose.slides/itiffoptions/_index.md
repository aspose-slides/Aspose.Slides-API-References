---
title: ITiffOptions
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp các tùy chọn kiểm soát cách một bản trình bày được lưu ở định dạng TIFF.
type: docs
url: /vi/com.aspose.slides/itiffoptions/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

Cung cấp các tùy chọn kiểm soát cách một bản trình bày được lưu ở định dạng TIFF.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getImageSize()](#getImageSize--) | Xác định kích thước của ảnh TIFF được tạo. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Xác định kích thước của ảnh TIFF được tạo. |
| [getDpiX()](#getDpiX--) | Xác định độ phân giải ngang tính bằng điểm trên inch. |
| [setDpiX(long value)](#setDpiX-long-) | Xác định độ phân giải ngang tính bằng điểm trên inch. |
| [getDpiY()](#getDpiY--) | Xác định độ phân giải dọc tính bằng điểm trên inch. |
| [setDpiY(long value)](#setDpiY-long-) | Xác định độ phân giải dọc tính bằng điểm trên inch. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. |
| [getCompressionType()](#getCompressionType--) | Xác định loại nén. |
| [setCompressionType(int value)](#setCompressionType-int-) | Xác định loại nén. |
| [getPixelFormat()](#getPixelFormat--) | Xác định định dạng pixel cho các ảnh được tạo. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Xác định định dạng pixel cho các ảnh được tạo. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản bản trình bày [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản bản trình bày [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Xác định thuật toán chuyển đổi ảnh màu sang ảnh đen trắng. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Xác định thuật toán chuyển đổi ảnh màu sang ảnh đen trắng. |
| [getInkOptions()](#getInkOptions--) | Cung cấp các tùy chọn kiểm soát giao diện của đối tượng Ink trong tài liệu đã xuất. |

### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

Xác định kích thước của ảnh TIFF được tạo. Giá trị mặc định là 0x0, có nghĩa là kích thước ảnh được tạo sẽ được tính dựa trên giá trị kích thước slide của bản trình bày. Đọc/ghi [Size](../../com.aspose.slides.android/size).

**Trả về:**
[Size](../../com.aspose.slides.android/size)

### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

Xác định kích thước của ảnh TIFF được tạo. Giá trị mặc định là 0x0, có nghĩa là kích thước ảnh sẽ được tính dựa trên giá trị kích thước slide của bản trình bày. Đọc/ghi [Size](../../com.aspose.slides.android/size).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

Xác định độ phân giải ngang tính bằng điểm trên inch. Đọc/ghi long.

**Trả về:**
long

### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

Xác định độ phân giải ngang tính bằng điểm trên inch. Đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

Xác định độ phân giải dọc tính bằng điểm trên inch. Đọc/ghi long.

**Trả về:**
long

### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

Xác định độ phân giải dọc tính bằng điểm trên inch. Đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

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

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

Xác định loại nén. Đọc/ghi [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Trả về:**
int

### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

Xác định loại nén. Đọc/ghi [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

Xác định định dạng pixel cho các ảnh được tạo. Đọc/ghi [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Trả về:**
int

### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

Xác định định dạng pixel cho các ảnh được tạo. Đọc/ghi [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản bản trình bày [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
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

Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản bản trình bày [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

Xác định thuật toán chuyển đổi ảnh màu sang ảnh đen trắng. Tùy chọn này sẽ chỉ được áp dụng nếu CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) được đặt thành [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) hoặc [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Đọc/ghi [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Mặc định là [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Trả về:**
int

### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public abstract void setBwConversionMode(int value)
```

Xác định thuật toán chuyển đổi ảnh màu sang ảnh đen trắng. Tùy chọn này sẽ chỉ được áp dụng nếu CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) được đặt thành [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) hoặc [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Đọc/ghi [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Mặc định là [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Cung cấp các tùy chọn kiểm soát giao diện của đối tượng Ink trong tài liệu đã xuất. Chỉ đọc [IInkOptions](../../com.aspose.slides/iinkoptions)

**Trả về:**
[IInkOptions](../../com.aspose.slides/iinkoptions)