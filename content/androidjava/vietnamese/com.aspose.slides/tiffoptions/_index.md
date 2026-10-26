---
title: TiffOptions
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu dưới định dạng TIFF.
type: docs
url: /vi/com.aspose.slides/tiffoptions/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu dưới dạng TIFF.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // Tạo một đối tượng Presentation đại diện cho một tệp trình chiếu
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // Lưu bản trình chiếu thành tài liệu TIFF
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // Tạo một đối tượng Presentation đại diện cho một tệp Presentation
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // Tạo một thể hiện của lớp TiffOptions
>      TiffOptions opts = new TiffOptions();
>      // Đặt loại nén
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // Các loại nén
>      // Mặc định - Xác định sơ đồ nén mặc định (LZW).
>      // Không - Xác định không có nén.
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // Độ sâu phụ thuộc vào loại nén và không thể đặt thủ công.
>      // Đơn vị độ phân giải luôn bằng 2 (điểm trên mỗi inch)
>      // Đặt DPI cho ảnh
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // Đặt kích thước ảnh
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // Lưu bản trình chiếu thành TIFF với kích thước ảnh đã chỉ định
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // Tạo một đối tượng Presentation đại diện cho một tệp Presentation
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      // ImagePixelFormat chứa các giá trị sau (như có thể thấy trong tài liệu):
>      //Format1bppIndexed; // 1 bit mỗi pixel, có chỉ mục.
>      //Format4bppIndexed; // 4 bit mỗi pixel, có chỉ mục.
>      //Format8bppIndexed; // 8 bit mỗi pixel, có chỉ mục.
>      //Format24bppRgb; // 24 bit mỗi pixel, RGB.
>      //Format32bppArgb; // 32 bit mỗi pixel, ARGB.
> 
>      // Lưu bản trình chiếu thành TIFF với kích thước ảnh đã chỉ định
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Các hàm khởi tạo

| Constructor | Mô tả |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | Hàm khởi tạo mặc định. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu xuất. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. |
| [getImageSize()](#getImageSize--) | Xác định kích thước của hình ảnh TIFF được tạo. |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | Xác định kích thước của hình ảnh TIFF được tạo. |
| [getDpiX()](#getDpiX--) | Xác định độ phân giải theo chiều ngang tính bằng dot per inch. |
| [setDpiX(long value)](#setDpiX-long-) | Xác định độ phân giải theo chiều ngang tính bằng dot per inch. |
| [getDpiY()](#getDpiY--) | Xác định độ phân giải theo chiều dọc tính bằng dot per inch. |
| [setDpiY(long value)](#setDpiY-long-) | Xác định độ phân giải theo chiều dọc tính bằng dot per inch. |
| [getCompressionType()](#getCompressionType--) | Xác định loại nén. |
| [setCompressionType(int value)](#setCompressionType-int-) | Xác định loại nén. |
| [getPixelFormat()](#getPixelFormat--) | Xác định định dạng pixel cho các hình ảnh được tạo. |
| [setPixelFormat(int value)](#setPixelFormat-int-) | Xác định định dạng pixel cho các hình ảnh được tạo. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getBwConversionMode()](#getBwConversionMode--) | Xác định thuật toán chuyển đổi hình ảnh màu sang đen trắng. |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | Xác định thuật toán chuyển đổi hình ảnh màu sang đen trắng. |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```


Hàm khởi tạo mặc định.

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


Cung cấp các tùy chọn kiểm soát giao diện của các đối tượng Ink trong tài liệu xuất. Chỉ đọc [IInkOptions](../../com.aspose.slides/iinkoptions)

**Trả về:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là false.

**Trả về:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


Xác định xem tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```


Xác định kích thước của hình ảnh TIFF được tạo. Giá trị mặc định là 0x0, có nghĩa là kích thước hình ảnh sẽ được tính dựa trên kích thước slide của bản trình chiếu. Đọc/ghi [Size](../../com.aspose.slides.android/size).

**Trả về:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```


Xác định kích thước của hình ảnh TIFF được tạo. Giá trị mặc định là 0x0, có nghĩa là kích thước hình ảnh sẽ được tính dựa trên kích thước slide của bản trình chiếu. Đọc/ghi [Size](../../com.aspose.slides.android/size).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```


Xác định độ phân giải theo chiều ngang tính bằng dot per inch. Đọc/ghi long.

**Trả về:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```


Xác định độ phân giải theo chiều ngang tính bằng dot per inch. Đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```


Xác định độ phân giải theo chiều dọc tính bằng dot per inch. Đọc/ghi long.

**Trả về:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```


Xác định độ phân giải theo chiều dọc tính bằng dot per inch. Đọc/ghi long.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```


Xác định loại nén. Đọc/ghi [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Trả về:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```


Xác định loại nén. Đọc/ghi [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```


Xác định định dạng pixel cho các hình ảnh được tạo. Đọc/ghi [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Trả về:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```


Xác định định dạng pixel cho các hình ảnh được tạo. Đọc/ghi [ImagePixelFormat](../../com.aspose.slides/imagepixelformat).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
public final int getBwConversionMode()
```


Xác định thuật toán chuyển đổi hình ảnh màu sang đen trắng. Tùy chọn này sẽ được áp dụng chỉ nếu CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) được đặt thành [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) hoặc [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Đọc/ghi [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Mặc định là [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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
public final void setBwConversionMode(int value)
```


Xác định thuật toán chuyển đổi hình ảnh màu sang đen trắng. Tùy chọn này sẽ được áp dụng chỉ nếu CompressionType (\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)) được đặt thành [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) hoặc [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) Đọc/ghi [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode). Mặc định là [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default).

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