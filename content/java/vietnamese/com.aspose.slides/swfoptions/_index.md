---
title: SwfOptions
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng Swf.
type: docs
url: /vi/com.aspose.slides/swfoptions/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**Tất cả các giao diện đã thực hiện:**
[com.aspose.slides.ISwfOptions](../../com.aspose.slides/iswfoptions)
```
public class SwfOptions extends SaveOptions implements ISwfOptions
```

Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng Swf.

--------------------

> ```
> The following example shows how to convert PowerPoint to SWF Flash.
>  
>  // Tạo một đối tượng Presentation đại diện cho một tệp trình chiếu
>  Presentation pres = new Presentation("HelloWorld.pptx");
>  try {
>      SwfOptions swfOptions = new SwfOptions();
>      swfOptions.setViewerIncluded(false);
>      INotesCommentsLayoutingOptions notesOptions = swfOptions.getNotesCommentsLayouting();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      // Lưu bản trình chiếu và các trang ghi chú
>      pres.save("SaveAsSwf_out.swf", SaveFormat.Swf, swfOptions);
>      swfOptions.setViewerIncluded(true);
>      pres.save("SaveNotes_out.swf", SaveFormat.Swf, swfOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [SwfOptions()](#SwfOptions--) | Constructor mặc định. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Chỉ định liệu tài liệu được tạo có bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Chỉ định liệu tài liệu được tạo có bao gồm các slide ẩn hay không. |
| [getCompressed()](#getCompressed--) | Chỉ định liệu tài liệu SWF được tạo có được nén hay không. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Chỉ định liệu tài liệu SWF được tạo có được nén hay không. |
| [getViewerIncluded()](#getViewerIncluded--) | Chỉ định liệu tài liệu SWF được tạo có bao gồm trình xem tài liệu tích hợp hay không. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Chỉ định liệu tài liệu SWF được tạo có bao gồm trình xem tài liệu tích hợp hay không. |
| [getShowPageBorder()](#getShowPageBorder--) | Chỉ định liệu viền quanh các trang có được hiển thị hay không. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Chỉ định liệu viền quanh các trang có được hiển thị hay không. |
| [getShowFullScreen()](#getShowFullScreen--) | Hiển thị/ẩn nút toàn màn hình. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Hiển thị/ẩn nút toàn màn hình. |
| [getShowPageStepper()](#getShowPageStepper--) | Hiển thị/ẩn bộ chuyển trang. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Hiển thị/ẩn bộ chuyển trang. |
| [getShowSearch()](#getShowSearch--) | Hiển thị/ẩn phần tìm kiếm. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Hiển thị/ẩn phần tìm kiếm. |
| [getShowTopPane()](#getShowTopPane--) | Hiển thị/ẩn toàn bộ pane trên cùng. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Hiển thị/ẩn toàn bộ pane trên cùng. |
| [getShowBottomPane()](#getShowBottomPane--) | Hiển thị/ẩn pane dưới. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Hiển thị/ẩn pane dưới. |
| [getShowLeftPane()](#getShowLeftPane--) | Hiển thị/ẩn pane trái. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Hiển thị/ẩn pane trái. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Bắt đầu với pane trái mở. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Bắt đầu với pane trái mở. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Bật/tắt menu ngữ cảnh. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Bật/tắt menu ngữ cảnh. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. |
| [getLogoLink()](#getLogoLink--) | Lấy hoặc đặt địa chỉ hyperlink đầy đủ cho logo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Lấy hoặc đặt địa chỉ hyperlink đầy đủ cho logo. |
| [getJpegQuality()](#getJpegQuality--) | Chỉ định chất lượng của các hình ảnh JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Chỉ định chất lượng của các hình ảnh JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### SwfOptions() {#SwfOptions--}
```
public SwfOptions()
```

Constructor mặc định.

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```

Chỉ định liệu tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là false.

**Trả về:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```

Chỉ định liệu tài liệu được tạo có bao gồm các slide ẩn hay không. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getCompressed() {#getCompressed--}
```
public final boolean getCompressed()
```

Chỉ định liệu tài liệu SWF được tạo có được nén hay không. Mặc định là true.

**Trả về:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public final void setCompressed(boolean value)
```

Chỉ định liệu tài liệu SWF được tạo có được nén hay không. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public final boolean getViewerIncluded()
```

Chỉ định liệu tài liệu SWF được tạo có bao gồm trình xem tài liệu tích hợp hay không. Mặc định là true.

**Trả về:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public final void setViewerIncluded(boolean value)
```

Chỉ định liệu tài liệu SWF được tạo có bao gồm trình xem tài liệu tích hợp hay không. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public final boolean getShowPageBorder()
```

Chỉ định liệu viền quanh các trang có được hiển thị hay không. Mặc định là true.

**Trả về:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public final void setShowPageBorder(boolean value)
```

Chỉ định liệu viền quanh các trang có được hiển thị hay không. Mặc định là true.

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

Hiển thị/ẩn toàn bộ pane trên cùng. Có thể được ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public final void setShowTopPane(boolean value)
```

Hiển thị/ẩn toàn bộ pane trên cùng. Có thể được ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public final boolean getShowBottomPane()
```

Hiển thị/ẩn pane dưới. Có thể được ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public final void setShowBottomPane(boolean value)
```

Hiển thị/ẩn pane dưới. Có thể được ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public final boolean getShowLeftPane()
```

Hiển thị/ẩn pane trái. Có thể được ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public final void setShowLeftPane(boolean value)
```

Hiển thị/ẩn pane trái. Có thể được ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public final boolean getStartOpenLeftPane()
```

Bắt đầu với pane trái mở. Có thể được ghi đè trong flashvars. Mặc định là false.

**Trả về:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public final void setStartOpenLeftPane(boolean value)
```

Bắt đầu với pane trái mở. Có thể được ghi đè trong flashvars. Mặc định là false.

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

Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. Hình ảnh phải là PNG 32x64 pixel, nếu không logo có thể hiển thị không đúng.

**Trả về:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public final void setLogoImageBytes(byte[] value)
```

Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. Hình ảnh phải là PNG 32x64 pixel, nếu không logo có thể hiển thị không đúng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public final String getLogoLink()
```

Lấy hoặc đặt địa chỉ hyperlink đầy đủ cho logo. Chỉ có hiệu lực nếu một (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) được chỉ định.

**Trả về:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public final void setLogoLink(String value)
```

Lấy hoặc đặt địa chỉ hyperlink đầy đủ cho logo. Chỉ có hiệu lực nếu một (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public final int getJpegQuality()
```

Chỉ định chất lượng của các hình ảnh JPEG. Mặc định là 95.

**Trả về:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public final void setJpegQuality(int value)
```

Chỉ định chất lượng của các hình ảnh JPEG. Mặc định là 95.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Thuộc tính này không hỗ trợ gán các đối tượng kiểu [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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


**Trả về:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Thuộc tính này không hỗ trợ gán các đối tượng kiểu [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions).

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