---
title: IHyperlink
second_title: Aspose.Slides for Java API Reference
description: Biểu diễn một siêu liên kết.
type: docs
url: /vi/com.aspose.slides/ihyperlink/
---```
public interface IHyperlink
```

Biểu diễn một siêu liên kết.
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getActionType()](#getActionType--) | Returns type of HyperLinkEx's action. |
| [getExternalUrl()](#getExternalUrl--) | Specifies the external URL If this property become not null then property TargetSlide become null. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Represents a hyperlink that is set for this portion without regard to the actual content of the portion. |
| [getTargetSlide()](#getTargetSlide--) | If the HyperlinkEx targets specific slide returns this slide. |
| [getTargetFrame()](#getTargetFrame--) | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Returns the frame within the parent HTML frameset for the target of the parent hyperlink when one exists. |
| [getTooltip()](#getTooltip--) | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Returns the string which may be surfaced in a user interface as associated with the parent hyperlink. |
| [getHistory()](#getHistory--) | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. |
| [setHistory(boolean value)](#setHistory-boolean-) | Determines whether the target of the parent hyperlink shall be added to a list of viewed hyperlinks when it is invoked. |
| [getHighlightClick()](#getHighlightClick--) | Determines whether the hyperlink should be highlighted on click. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Determines whether the hyperlink should be highlighted on click. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Determines whether the sound should be stopped on hyperlink click. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Determines whether the sound should be stopped on hyperlink click. |
| [getSound()](#getSound--) | Represents the playing sound of the hyperlink. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Represents the playing sound of the hyperlink. |
| [getColorSource()](#getColorSource--) | Represents the source of hyperlink color - either styles or portion format. |
| [setColorSource(int value)](#setColorSource-int-) | Represents the source of hyperlink color - either styles or portion format. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Determines whether the two Hyperlink instances are equal. |

### getActionType() {#getActionType--}
```
public abstract int getActionType()
```

Trả về kiểu hành động của HyperLinkEx. Chỉ đọc [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Trả về:**
int

### getExternalUrl() {#getExternalUrl--}
```
public abstract String getExternalUrl()
```

Specifies the external URL If this property become not null then property TargetSlide become null. Chỉ đọc String.

**Trả về:**
java.lang.String

### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public abstract String getExternalUrlOriginal()
```

Represents a hyperlink that is set for this portion without regard to the actual content of the portion.

--------------------

PowerPoint behaves specifically for links and their corresponding text in a portion. It allows to create text for the hyperlink in the form of a valid URL, different from the real address of the link. In this case, when you view the link in the edit window, it will be changed to match the text portion. This property represents the original value of the hyperlink.

**Trả về:**
java.lang.String

### getTargetSlide() {#getTargetSlide--}
```
public abstract ISlide getTargetSlide()
```

If the HyperlinkEx targets specific slide returns this slide. If the property become not null then property ExternalUrl become null. Chỉ đọc [ISlide](../../com.aspose.slides/islide).

**Trả về:**
[ISlide](../../com.aspose.slides/islide)

### getTargetFrame() {#getTargetFrame--}
```
public abstract String getTargetFrame()
```

Trả về khung trong tập khung HTML cha cho mục tiêu của siêu liên kết cha khi tồn tại. Đọc/ghi String.

**Trả về:**
java.lang.String

### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public abstract void setTargetFrame(String value)
```

Trả về khung trong tập khung HTML cha cho mục tiêu của siêu liên kết cha khi tồn tại. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public abstract String getTooltip()
```

Trả về chuỗi có thể hiển thị trong giao diện người dùng liên quan tới siêu liên kết cha. Đọc/ghi String.

**Trả về:**
java.lang.String

### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public abstract void setTooltip(String value)
```

Trả về chuỗi có thể hiển thị trong giao diện người dùng liên quan tới siêu liên kết cha. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public abstract boolean getHistory()
```

Xác định liệu mục tiêu của siêu liên kết cha có được thêm vào danh sách các siêu liên kết đã xem khi nó được gọi hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setHistory(boolean value) {#setHistory-boolean-}
```
public abstract void setHistory(boolean value)
```

Xác định liệu mục tiêu của siêu liên kết cha có được thêm vào danh sách các siêu liên kết đã xem khi nó được gọi hay không. Đọc/ghi boolean.

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

Xác định liệu âm thanh có nên dừng khi nhấp vào siêu liên kết hay không. Đọc/ghi boolean.

**Trả về:**
boolean

### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public abstract void setStopSoundOnClick(boolean value)
```

Xác định liệu âm thanh có nên dừng khi nhấp vào siêu liên kết hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Represents the playing sound of the hyperlink. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lấy siêⁿ liên kết hình dạng đầu tiên
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

Represents the playing sound of the hyperlink. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lấy siêu liên kết hình dạng đầu tiên
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Trích xuất âm thanh của siêu liên kết thành mảng byte
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

Represents the source of hyperlink color - either styles or portion format. Đọc/ghi [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Trả về:**
int

### setColorSource(int value) {#setColorSource-int-}
```
public abstract void setColorSource(int value)
```

Represents the source of hyperlink color - either styles or portion format. Đọc/ghi [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

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
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Siêu liên kết để so sánh với siêu liên kết hiện tại. |

**Trả về:**
boolean - **true** nếu Siêu liên kết được chỉ định bằng với Siêu liên kết hiện tại; ngược lại, **false**.