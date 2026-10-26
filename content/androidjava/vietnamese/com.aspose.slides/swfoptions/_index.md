---
title: SwfOptions
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cung cấp các tùy chọn điều khiển cách một bản trình chiếu được lưu dưới định dạng Swf.
type: docs
url: /vi/com.aspose.slides/swfoptions/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu dưới định dạng Swf.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Khởi tạo một đối tượng Presentation đại diện cho tệp trình chiếu
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Lưu trình chiếu và các trang ghi chú
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Hàm khởi tạo mặc định. |
## Các phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Xác định xem tài liệu tạo ra có nên bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Xác định xem tài liệu tạo ra có nên bao gồm các slide ẩn hay không. |
| [getCompressed()](#getCompressed--) | Xác định xem tài liệu SWF tạo ra có nên được nén hay không. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Xác định xem tài liệu SWF tạo ra có nên được nén hay không. |
| [getViewerIncluded()](#getViewerIncluded--) | Xác định xem tài liệu SWF tạo ra có nên bao gồm trình xem tài liệu tích hợp hay không. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Xác định xem tài liệu SWF tạo ra có nên bao gồm trình xem tài liệu tích hợp hay không. |
| [getShowPageBorder()](#getShowPageBorder--) | Xác định xem viền quanh các trang có nên được hiển thị hay không. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Xác định xem viền quanh các trang có nên được hiển thị hay không. |
| [getShowFullScreen()](#getShowFullScreen--) | Hiển thị/ẩn nút toàn màn hình. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Hiển thị/ẩn nút toàn màn hình. |
| [getShowPageStepper()](#getShowPageStepper--) | Hiển thị/ẩn bộ chuyển trang. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Hiển thị/ẩn bộ chuyển trang. |
| [getShowSearch()](#getShowSearch--) | Hiển thị/ẩn phần tìm kiếm. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Hiển thị/ẩn phần tìm kiếm. |
| [getShowTopPane()](#getShowTopPane--) | Hiển thị/ẩn toàn bộ khung trên. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Hiển thị/ẩn toàn bộ khung trên. |
| [getShowBottomPane()](#getShowBottomPane--) | Hiển thị/ẩn khung dưới. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Hiển thị/ẩn khung dưới. |
| [getShowLeftPane()](#getShowLeftPane--) | Hiển thị/ẩn khung trái. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Hiển thị/ẩn khung trái. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Bắt đầu với khung trái mở. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Bắt đầu với khung trái mở. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Bật/tắt menu ngữ cảnh. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Bật/tắt menu ngữ cảnh. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. |
| [getLogoLink()](#getLogoLink--) | Lấy hoặc đặt địa chỉ liên kết đầy đủ cho một logo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Lấy hoặc đặt địa chỉ liên kết đầy đủ cho một logo. |
| [getJpegQuality()](#getJpegQuality--) | Xác định chất lượng của hình ảnh JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Xác định chất lượng của hình ảnh JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

Hàm khởi tạo mặc định.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Xác định xem tài liệu tạo ra có nên bao gồm các slide ẩn hay không. Mặc định là false.

**Trả về:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Xác định xem tài liệu tạo ra có nên bao gồm các slide ẩn hay không. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

Xác định xem tài liệu SWF tạo ra có nên được nén hay không. Mặc định là true.

**Trả về:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

Xác định xem tài liệu SWF tạo ra có nên được nén hay không. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

Xác định xem tài liệu SWF tạo ra có nên bao gồm trình xem tài liệu tích hợp hay không. Mặc định là true.

**Trả về:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

Xác định xem tài liệu SWF tạo ra có nên bao gồm trình xem tài liệu tích hợp hay không. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

Xác định xem viền quanh các trang có nên được hiển thị hay không. Mặc định là true.

**Trả về:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

Xác định xem viền quanh các trang có nên được hiển thị hay không. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public final boolean getShowFullScreen()
```

Hiển thị/ẩn nút toàn màn hình. Có thể được ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public final void setShowFullScreen(boolean value)
```

Hiển thị/ẩn nút toàn màn hình. Có thể được ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public final boolean getShowPageStepper()
```

Hiển thị/ẩn bộ chuyển trang. Có thể được ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public final void setShowPageStepper(boolean value)
```

Hiển thị/ẩn bộ chuyển trang. Có thể được ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public final boolean getShowSearch()
```

Hiển thị/ẩn phần tìm kiếm. Có thể được ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public final void setShowSearch(boolean value)
```

Hiển thị/ẩn phần tìm kiếm. Có thể được ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public final boolean getShowTopPane()
```

Hiển thị/ẩn toàn bộ khung trên. Có thể được ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

Hiển thị/ẩn toàn bộ khung trên. Có thể được ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

Hiển thị/ẩn khung dưới. Có thể được ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

Hiển thị/ẩn khung dưới. Có thể được ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

Hiển thị/ẩn khung trái. Có thể được ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

Hiển thị/ẩn khung trái. Có thể được ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

Bắt đầu với khung trái mở. Có thể được ghi đè trong flashvars. Mặc định là false.

**Trả về:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

Bắt đầu với khung trái mở. Có thể được ghi đè trong flashvars. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public final boolean getEnableContextMenu()
```

Bật/tắt menu ngữ cảnh. Mặc định là true.

**Trả về:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public final void setEnableContextMenu(boolean value)
```

Bật/tắt menu ngữ cảnh. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public final byte[] getLogoImageBytes()
```

Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. Hình ảnh nên là ảnh PNG có kích thước 32x64 pixel, nếu không logo có thể hiển thị không đúng.

**Trả về:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. Hình ảnh nên là ảnh PNG có kích thước 32x64 pixel, nếu không logo có thể hiển thị không đúng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

Lấy hoặc đặt địa chỉ liên kết đầy đủ cho một logo. Chỉ có hiệu lực nếu một (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) được chỉ định.

**Trả về:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

Lấy hoặc đặt địa chỉ liên kết đầy đủ cho một logo. Chỉ có hiệu lực nếu một (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Xác định chất lượng của hình ảnh JPEG. Mặc định là 95.

**Trả về:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Xác định chất lượng của hình ảnh JPEG. Mặc định là 95.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Thuộc tính này không hỗ trợ gán các đối tượng kiểu [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

--------------------

> ```
> Ví dụ:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
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

Lấy hoặc đặt chế độ sắp xếp các slide trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Thuộc tính này không hỗ trợ gán các đối tượng kiểu [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |