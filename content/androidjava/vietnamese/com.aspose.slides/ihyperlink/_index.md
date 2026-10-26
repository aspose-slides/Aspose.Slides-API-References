---
title: IHyperlink
second_title: Aspose.Slides for Android via Java API Reference
description: Biểu diễn một siêu liên kết.
type: docs
url: /vi/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Biểu diễn một siêu liên kết.
## Phương thức

| Method | Mô tả |
| --- | --- |
| [getActionType()](#getActionType--) | Trả về kiểu của hành động của HyperLinkEx. |
| [getExternalUrl()](#getExternalUrl--) | Xác định URL bên ngoài. Nếu thuộc tính này không null thì thuộc tính TargetSlide sẽ null. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Biểu diễn một siêu liên kết được đặt cho phần này mà không quan tâm đến nội dung thực của phần. |
| [getTargetSlide()](#getTargetSlide--) | Nếu HyperlinkEx hướng tới một slide cụ thể, trả về slide đó. |
| [getTargetFrame()](#getTargetFrame--) | Trả về khung trong bộ khung HTML cha cho mục tiêu của siêu liên kết cha khi tồn tại. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Trả về khung trong bộ khung HTML cha cho mục tiêu của siêu liên kết cha khi tồn tại. |
| [getTooltip()](#getTooltip--) | Trả về chuỗi có thể hiển thị trong giao diện người dùng liên quan đến siêu liên kết cha. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Trả về chuỗi có thể hiển thị trong giao diện người dùng liên quan đến siêu liên kết cha. |
| [getHistory()](#getHistory--) | Xác định liệu mục tiêu của siêu liên kết cha có được thêm vào danh sách các siêu liên kết đã xem khi được gọi hay không. |
| [setHistory(boolean value)](#setHistory-boolean-) | Xác định liệu mục tiêu của siêu liên kết cha có được thêm vào danh sách các siêu liên kết đã xem khi được gọi hay không. |
| [getHighlightClick()](#getHighlightClick--) | Xác định liệu siêu liên kết có được làm nổi bật khi nhấp chuột hay không. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Xác định liệu siêu liên kết có được làm nổi bật khi nhấp chuột hay không. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Xác định liệu âm thanh có bị dừng khi nhấp vào siêu liên kết hay không. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Xác định liệu âm thanh có bị dừng khi nhấp vào siêu liên kết hay không. |
| [getSound()](#getSound--) | Biểu diễn âm thanh đang phát của siêu liên kết. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Biểu diễn âm thanh đang phát của siêu liên kết. |
| [getColorSource()](#getColorSource--) | Biểu diễn nguồn màu của siêu liên kết – từ style hoặc định dạng phần. |
| [setColorSource(int value)](#setColorSource-int-) | Biểu diễn nguồn màu của siêu liên kết – từ style hoặc định dạng phần. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Xác định liệu hai thể hiện Hyperlink có bằng nhau hay không. |
### getActionType() {#getActionType--}
```
public abstract int getActionType()
```


Trả về kiểu của hành động của HyperLinkEx. Chỉ đọc [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Trả về:**
int
### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```


Xác định URL bên ngoài. Nếu thuộc tính này không null thì thuộc tính TargetSlide sẽ null. Chỉ đọc String.

**Trả về:**
java.lang.String
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```


Biểu diễn một siêu liên kết được đặt cho phần này mà không quan tâm đến nội dung thực của phần.

--------------------

PowerPoint xử lý đặc biệt các liên kết và văn bản tương ứng trong một phần. Nó cho phép tạo văn bản cho siêu liên kết dưới dạng URL hợp lệ, khác với địa chỉ thực của liên kết. Trong trường hợp này, khi bạn xem liên kết trong cửa sổ chỉnh sửa, nó sẽ được thay đổi để khớp với phần văn bản. Thuộc tính này biểu diễn giá trị gốc của siêu liên kết.

**Trả về:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```


Nếu HyperlinkEx hướng tới một slide cụ thể, trả về slide đó. Nếu thuộc tính này không null thì thuộc tính ExternalUrl sẽ null. Chỉ đọc [ISlide](../../com.aspose.slides/islide).

**Trả về:**
[ISlide](../../com.aspose.slides/islide)
### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```


Trả về khung trong bộ khung HTML cha cho mục tiêu của siêu liên kết cha khi tồn tại. Đọc/ghi String.

**Trả về:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```


Trả về khung trong bộ khung HTML cha cho mục tiêu của siêu liên kết cha khi tồn tại. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```


Trả về chuỗi có thể hiển thị trong giao diện người dùng liên quan đến siêu liên kết cha. Đọc/ghi String.

**Trả về:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```


Trả về chuỗi có thể hiển thị trong giao diện người dùng liên quan đến siêu liên kết cha. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```


Xác định liệu mục tiêu của siêu liên kết cha có được thêm vào danh sách các siêu liên kết đã xem khi được gọi hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```


Xác định liệu mục tiêu của siêu liên kết cha có được thêm vào danh sách các siêu liên kết đã xem khi được gọi hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public abstract boolean getHighlightClick()
```


Xác định liệu siêu liên kết có được làm nổi bật khi nhấp chuột hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public abstract void setHighlightClick(boolean value)
```


Xác định liệu siêu liên kết có được làm nổi bật khi nhấp chuột hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public abstract boolean getStopSoundOnClick()
```


Xác định liệu âm thanh có bị dừng khi nhấp vào siêu liên kết hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```


Xác định liệu âm thanh có bị dừng khi nhấp vào siêu liên kết hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Biểu diễn âm thanh đang phát của siêu liên kết. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lấy siêu liên kết của shape đầu tiên
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Trích xuất âm thanh siêu liên kết thành mảng byte
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Trả về:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


Biểu diễn âm thanh đang phát của siêu liên kết. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lấy siêu liên kết của shape đầu tiên
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Trích xuất âm thanh siêu liên kết thành mảng byte
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public abstract int getColorSource()
```


Biểu diễn nguồn màu của siêu liên kết – từ style hoặc định dạng phần. Đọc/ghi [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Trả về:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```


Biểu diễn nguồn màu của siêu liên kết – từ style hoặc định dạng phần. Đọc/ghi [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public abstract boolean equals(IHyperlink hlink)
```


Xác định liệu hai thể hiện Hyperlink có bằng nhau hay không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink để so sánh với Hyperlink hiện tại. |

**Trả về:**
boolean - **true** nếu Hyperlink được chỉ định bằng với Hyperlink hiện tại; nếu không, **false**.