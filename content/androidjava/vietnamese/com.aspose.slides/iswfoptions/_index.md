---
title: ISwfOptions
second_title: Tham chiếu API Java của Aspose.Slides cho Android
description: Cung cấp các tùy chọn kiểm soát cách một bản trình chiếu được lưu ở định dạng SWF.
type: docs
url: /vi/com.aspose.slides/iswfoptions/
---
**Tất cả các giao diện đã triển khai:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

Cung cấp các tùy chọn kiểm soát cách một bài thuyết trình được lưu ở định dạng SWF.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getCompressed()](#getCompressed--) | Chỉ định liệu tài liệu SWF được tạo ra có nên nén hay không. |
| [setCompressed(boolean value)](#setCompressed-boolean-) | Chỉ định liệu tài liệu SWF được tạo ra có nên nén hay không. |
| [getViewerIncluded()](#getViewerIncluded--) | Chỉ định liệu tài liệu SWF được tạo ra có nên bao gồm trình xem tài liệu tích hợp hay không. |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | Chỉ định liệu tài liệu SWF được tạo ra có nên bao gồm trình xem tài liệu tích hợp hay không. |
| [getShowPageBorder()](#getShowPageBorder--) | Chỉ định liệu viền quanh các trang có nên được hiển thị hay không. |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | Chỉ định liệu viền quanh các trang có nên được hiển thị hay không. |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | Chỉ định liệu tài liệu được tạo ra có nên bao gồm các slide ẩn hay không. |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | Chỉ định liệu tài liệu được tạo ra có nên bao gồm các slide ẩn hay không. |
| [getShowFullScreen()](#getShowFullScreen--) | Hiển thị/ẩn nút toàn màn hình. |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | Hiển thị/ẩn nút toàn màn hình. |
| [getShowPageStepper()](#getShowPageStepper--) | Hiển thị/ẩn bộ chuyển trang. |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | Hiển thị/ẩn bộ chuyển trang. |
| [getShowSearch()](#getShowSearch--) | Hiển thị/ẩn phần tìm kiếm. |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | Hiển thị/ẩn phần tìm kiếm. |
| [getShowTopPane()](#getShowTopPane--) | Hiển thị/ẩn toàn bộ pane trên cùng. |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | Hiển thị/ẩn toàn bộ pane trên cùng. |
| [getShowBottomPane()](#getShowBottomPane--) | Hiển thị/ẩn pane dưới cùng. |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | Hiển thị/ẩn pane dưới cùng. |
| [getShowLeftPane()](#getShowLeftPane--) | Hiển thị/ẩn pane bên trái. |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | Hiển thị/ẩn pane bên trái. |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | Bắt đầu với pane bên trái mở. |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | Bắt đầu với pane bên trái mở. |
| [getEnableContextMenu()](#getEnableContextMenu--) | Bật/tắt menu ngữ cảnh. |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | Bật/tắt menu ngữ cảnh. |
| [getLogoImageBytes()](#getLogoImageBytes--) | Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. |
| [getLogoLink()](#getLogoLink--) | Lấy hoặc đặt địa chỉ siêu liên kết đầy đủ cho logo. |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | Lấy hoặc đặt địa chỉ siêu liên kết đầy đủ cho logo. |
| [getJpegQuality()](#getJpegQuality--) | Chỉ định chất lượng của ảnh JPEG. |
| [setJpegQuality(int value)](#setJpegQuality-int-) | Chỉ định chất lượng của ảnh JPEG. |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```


Chỉ định liệu tài liệu SWF được tạo ra có nên nén hay không. Mặc định là true.

**Trả về:**
boolean
### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```


Chỉ định liệu tài liệu SWF được tạo ra có nên nén hay không. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```


Chỉ định liệu tài liệu SWF được tạo ra có nên bao gồm trình xem tài liệu tích hợp hay không. Mặc định là true.

**Trả về:**
boolean
### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```


Chỉ định liệu tài liệu SWF được tạo ra có nên bao gồm trình xem tài liệu tích hợp hay không. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```


Chỉ định liệu viền quanh các trang có nên được hiển thị hay không. Mặc định là true.

**Trả về:**
boolean
### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```


Chỉ định liệu viền quanh các trang có nên được hiển thị hay không. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```


Chỉ định liệu tài liệu được tạo ra có nên bao gồm các slide ẩn hay không. Mặc định là false.

**Trả về:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```


Chỉ định liệu tài liệu được tạo ra có nên bao gồm các slide ẩn hay không. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```


Hiển thị/ẩn nút toàn màn hình. Có thể bị ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```


Hiển thị/ẩn nút toàn màn hình. Có thể bị ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```


Hiển thị/ẩn bộ chuyển trang. Có thể bị ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```


Hiển thị/ẩn bộ chuyển trang. Có thể bị ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```


Hiển thị/ẩn phần tìm kiếm. Có thể bị ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```


Hiển thị/ẩn phần tìm kiếm. Có thể bị ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```


Hiển thị/ẩn toàn bộ pane trên cùng. Có thể bị ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```


Hiển thị/ẩn toàn bộ pane trên cùng. Có thể bị ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```


Hiển thị/ẩn pane dưới cùng. Có thể bị ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```


Hiển thị/ẩn pane dưới cùng. Có thể bị ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```


Hiển thị/ẩn pane bên trái. Có thể bị ghi đè trong flashvars. Mặc định là true.

**Trả về:**
boolean
### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```


Hiển thị/ẩn pane bên trái. Có thể bị ghi đè trong flashvars. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```


Bắt đầu với pane bên trái mở. Có thể bị ghi đè trong flashvars. Mặc định là false.

**Trả về:**
boolean
### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```


Bắt đầu với pane bên trái mở. Có thể bị ghi đè trong flashvars. Mặc định là false.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```


Bật/tắt menu ngữ cảnh. Mặc định là true.

**Trả về:**
boolean
### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```


Bật/tắt menu ngữ cảnh. Mặc định là true.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```


Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. Hình ảnh phải là PNG kích thước 32x64 pixel, nếu không logo có thể hiển thị không đúng.

**Trả về:**
byte[]
### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```


Hình ảnh sẽ được hiển thị làm logo ở góc trên bên phải của trình xem. Hình ảnh phải là PNG kích thước 32x64 pixel, nếu không logo có thể hiển thị không đúng.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```


Lấy hoặc đặt địa chỉ siêu liên kết đầy đủ cho logo. Chỉ có hiệu lực nếu một (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) được chỉ định.

**Trả về:**
java.lang.String
### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```


Lấy hoặc đặt địa chỉ siêu liên kết đầy đủ cho logo. Chỉ có hiệu lực nếu một (\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])) được chỉ định.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```


Chỉ định chất lượng của ảnh JPEG. Mặc định là 95.

**Trả về:**
int
### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```


Chỉ định chất lượng của ảnh JPEG. Mặc định là 95.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
``` 
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```


Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Thuộc tính này không hỗ trợ gán các đối tượng kiểu [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


Lấy hoặc đặt chế độ mà các slide được đặt trên trang khi xuất bản trình chiếu [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). Thuộc tính này không hỗ trợ gán các đối tượng kiểu [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions)

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


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |