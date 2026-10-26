---
title: Hyperlink
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Biểu diễn một siêu liên kết.
type: docs
url: /vi/com.aspose.slides/hyperlink/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Biểu diễn một siêu liên kết.
## Constructors

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Tạo một thể hiện của siêu liên kết. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Tạo một thể hiện của siêu liên kết trỏ đến slide cụ thể. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Tạo một thể hiện của siêu liên kết bằng cách sử dụng một siêu liên kết khác làm nguồn, ghi đè các thuộc tính phụ. |
## Methods

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Trả về một siêu liên kết đặc biệt “không làm gì”. |
| [getMedia()](#getMedia--) | Trả về một siêu liên kết đặc biệt “phát tệp media”. |
| [getNextSlide()](#getNextSlide--) | Trả về một siêu liên kết tới slide tiếp theo. |
| [getPreviousSlide()](#getPreviousSlide--) | Trả về một siêu liên kết tới slide trước đó. |
| [getFirstSlide()](#getFirstSlide--) | Trả về một siêu liên kết tới slide đầu tiên của bài thuyết trình. |
| [getLastSlide()](#getLastSlide--) | Trả về một siêu liên kết tới slide cuối cùng của bài thuyết trình. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Trả về một siêu liên kết tới slide đã xem lần cuối. |
| [getEndShow()](#getEndShow--) | Trả về một siêu liên kết kết thúc buổi trình chiếu. |
| [getActionType()](#getActionType--) | Trả về loại hành động của Hyperlink. |
| [getExternalUrl()](#getExternalUrl--) | Xác định URL bên ngoài. |
| [getTargetSlide()](#getTargetSlide--) | Nếu Hyperlink trỏ tới slide cụ thể thì trả về slide đó. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Đại diện cho một siêu liên kết được đặt cho phần này mà không quan tâm đến nội dung thực tế của phần. |
| [getTargetFrame()](#getTargetFrame--) | Trả về khung trong parent HTML frameset cho mục tiêu của parent hyperlink khi tồn tại. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Trả về khung trong parent HTML frameset cho mục tiêu của parent hyperlink khi tồn tại. |
| [getTooltip()](#getTooltip--) | Trả về chuỗi có thể được hiển thị trong giao diện người dùng như liên kết với parent hyperlink. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Trả về chuỗi có thể được hiển thị trong giao diện người dùng như liên kết với parent hyperlink. |
| [getHistory()](#getHistory--) | Xác định xem mục tiêu của parent hyperlink có được thêm vào danh sách các siêu liên kết đã xem khi nó được gọi hay không. |
| [setHistory(boolean value)](#setHistory-boolean-) | Xác định xem mục tiêu của parent hyperlink có được thêm vào danh sách các siêu liên kết đã xem khi nó được gọi hay không. |
| [getHighlightClick()](#getHighlightClick--) | Xác định xem siêu liên kết có được đánh dấu khi nhấp chuột hay không. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Xác định xem siêu liên kết có được đánh dấu khi nhấp chuột hay không. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Xác định xem âm thanh có được dừng khi nhấp chuột vào siêu liên kết hay không. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Xác định xem âm thanh có được dừng khi nhấp chuột vào siêu liên kết hay không. |
| [getSound()](#getSound--) | Đại diện cho âm thanh đang phát của siêu liên kết. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Đại diện cho âm thanh đang phát của siêu liên kết. |
| [getColorSource()](#getColorSource--) | Đại diện cho nguồn màu của siêu liên kết – hoặc kiểu dáng hoặc định dạng phần. |
| [setColorSource(int value)](#setColorSource-int-) | Đại diện cho nguồn màu của siêu liên kết – hoặc kiểu dáng hoặc định dạng phần. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định xem hai thể hiện Hyperlink có bằng nhau không. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Xác định xem hai thể hiện Hyperlink có bằng nhau không. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Kiểm tra hai siêu liên kết có bằng nhau. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Kiểm tra hai siêu liên kết có khác nhau. |
| [hashCode()](#hashCode--) | Đóng vai trò như hàm băm cho một kiểu cụ thể, phù hợp cho các thuật toán băm và cấu trúc dữ liệu như bảng băm. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Tạo một thể hiện của siêu liên kết.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| url | java.lang.String | URL của siêu liên kết. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Tạo một thể hiện của siêu liên kết trỏ đến slide cụ thể. Lưu ý: siêu liên kết được tạo phải được gán cho một đối tượng trong cùng một bài thuyết trình, nếu không liên kết sẽ được lưu dưới dạng NoAction.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide mục tiêu. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Tạo một thể hiện của siêu liên kết bằng cách sử dụng một siêu liên kết khác làm nguồn, ghi đè các thuộc tính phụ.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Siêu liên kết nguồn |
| targetFrame | java.lang.String | Khung mục tiêu |
| tooltip | java.lang.String | Văn bản gợi ý |
| history | boolean | Xác định xem mục tiêu của parent hyperlink có được thêm vào danh sách các siêu liên kết đã xem khi nó được gọi hay không. |
| stopSoundsOnClick | boolean | Xác định xem âm thanh có được dừng khi nhấp chuột vào siêu liên kết hay không. |
| highlightClick | boolean | Xác định xem siêu liên kết có được đánh dấu khi nhấp chuột hay không. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ đọc long.

**Trả về:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Trả về một siêu liên kết đặc biệt “không làm gì”. Chỉ đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Trả về một siêu liên kết đặc biệt “phát tệp media”. Được sử dụng trong AudioFrame và VideoFrame. Chỉ đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Trả về một siêu liên kết tới slide tiếp theo. Chỉ đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Trả về một siêu liên kết tới slide trước đó. Chỉ đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Trả về một siêu liên kết tới slide đầu tiên của bài thuyết trình. Chỉ đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Trả về một siêu liên kết tới slide cuối cùng của bài thuyết trình. Chỉ đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Trả về một siêu liên kết tới slide đã xem lần cuối. Chỉ đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Trả về một siêu liên kết kết thúc buổi trình chiếu. Chỉ đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Trả về loại hành động của Hyperlink. Chỉ đọc [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Trả về:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Xác định URL bên ngoài. Chỉ đọc String.

**Trả về:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Nếu Hyperlink trỏ tới slide cụ thể thì trả về slide đó. Chỉ đọc [ISlide](../../com.aspose.slides/islide).

**Trả về:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Đại diện cho một siêu liên kết được đặt cho phần này mà không quan tâm đến nội dung thực tế của phần.

--------------------

PowerPoint có xử lý đặc biệt cho các liên kết và văn bản tương ứng trong một phần. Nó cho phép tạo văn bản cho siêu liên kết dưới dạng URL hợp lệ, khác với địa chỉ thực của liên kết. Trong trường hợp này, khi bạn xem liên kết trong cửa sổ chỉnh sửa, nó sẽ được thay đổi để khớp với phần văn bản. Thuộc tính này đại diện cho giá trị gốc của siêu liên kết.

**Trả về:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Trả về khung trong parent HTML frameset cho mục tiêu của parent hyperlink khi tồn tại. Đọc/ghi String.

**Trả về:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Trả về khung trong parent HTML frameset cho mục tiêu của parent hyperlink khi tồn tại. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Trả về chuỗi có thể được hiển thị trong giao diện người dùng như liên kết với parent hyperlink. Đọc/ghi String.

**Trả về:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Trả về chuỗi có thể được hiển thị trong giao diện người dùng như liên kết với parent hyperlink. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Xác định xem mục tiêu của parent hyperlink có được thêm vào danh sách các siêu liên kết đã xem khi nó được gọi hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Xác định xem mục tiêu của parent hyperlink có được thêm vào danh sách các siêu liên kết đã xem khi nó được gọi hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Xác định xem siêu liên kết có được đánh dấu khi nhấp chuột hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Xác định xem siêu liên kết có được đánh dấu khi nhấp chuột hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Xác định xem âm thanh có được dừng khi nhấp chuột vào siêu liên kết hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Xác định xem âm thanh có được dừng khi nhấp chuột vào siêu liên kết hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Đại diện cho âm thanh đang phát của siêu liên kết. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lấy siêu liên kết của hình dạng đầu tiên
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
public final void setSound(IAudio value)
```

Đại diện cho âm thanh đang phát của siêu liên kết. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lấy siêu liên kết của hình dạng đầu tiên
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
public final int getColorSource()
```

Đại diện cho nguồn màu của siêu liên kết – hoặc kiểu dáng hoặc định dạng phần. Đọc/ghi [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Trả về:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Đại diện cho nguồn màu của siêu liên kết – hoặc kiểu dáng hoặc định dạng phần. Đọc/ghi [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Xác định xem hai thể hiện Hyperlink có bằng nhau không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| obj | java.lang.Object | Siêu liên kết để so sánh với Hyperlink hiện tại. |

**Trả về:**
boolean - **true** nếu Hyperlink được chỉ định bằng với Hyperlink hiện tại; ngược lại, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Xác định xem hai thể hiện Hyperlink có bằng nhau không.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Siêu liên kết để so sánh với Hyperlink hiện tại. |

**Trả về:**
boolean - **true** nếu Hyperlink được chỉ định bằng với Hyperlink hiện tại; ngược lại, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Kiểm tra hai siêu liên kết có bằng nhau.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Siêu liên kết đầu tiên để kiểm tra. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Siêu liên kết thứ hai để kiểm tra. |

**Trả về:**
boolean - **true** nếu các siêu liên kết bằng nhau.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Kiểm tra hai siêu liên kết có khác nhau.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Siêu liên kết đầu tiên để kiểm tra. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Siêu liên kết thứ hai để kiểm tra. |

**Trả về:**
boolean - **false** nếu các siêu liên kết bằng nhau.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Đóng vai trò như hàm băm cho một kiểu cụ thể, phù hợp cho các thuật toán băm và cấu trúc dữ liệu như bảng băm.

**Trả về:**
int - Mã băm cho một URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject