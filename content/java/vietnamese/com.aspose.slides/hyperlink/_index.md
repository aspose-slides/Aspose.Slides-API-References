---
title: Hyperlink
second_title: Tham chiếu API Aspose.Slides cho Java
description: Biểu thị một siêu liên kết.
type: docs
url: /vi/com.aspose.slides/hyperlink/
---
**Kế thừa:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tất cả các giao diện được triển khai:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Biểu thị một siêu liên kết.
## Các hàm tạo

| Hàm tạo | Mô tả |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Tạo một thể hiện của siêu liên kết. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Tạo một thể hiện của siêu liên kết trỏ tới slide cụ thể. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Tạo một thể hiện của siêu liên kết bằng cách sử dụng một siêu liên kết khác làm nguồn, ghi đè các thuộc tính phụ. |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Trả về một siêu liên kết đặc biệt "không làm gì". |
| [getMedia()](#getMedia--) | Trả về một siêu liên kết đặc biệt "phát tệp media". |
| [getNextSlide()](#getNextSlide--) | Trả về một siêu liên kết tới slide tiếp theo. |
| [getPreviousSlide()](#getPreviousSlide--) | Trả về một siêu liên kết tới slide trước đó. |
| [getFirstSlide()](#getFirstSlide--) | Trả về một siêu liên kết tới slide đầu tiên của bản trình chiếu. |
| [getLastSlide()](#getLastSlide--) | Trả về một siêu liên kết tới slide cuối cùng của bản trình chiếu. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Trả về một siêu liên kết tới slide đã xem cuối cùng. |
| [getEndShow()](#getEndShow--) | Trả về một siêu liên kết kết thúc buổi chiếu. |
| [getActionType()](#getActionType--) | Trả về loại hành động của Hyperlink. |
| [getExternalUrl()](#getExternalUrl--) | Xác định URL bên ngoài. |
| [getTargetSlide()](#getTargetSlide--) | Nếu Hyperlink mục tiêu là slide cụ thể, trả về slide này. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Biểu thị một siêu liên kết được đặt cho phần này mà không quan tâm tới nội dung thực tế của phần. |
| [getTargetFrame()](#getTargetFrame--) | Trả về khung trong HTML frameset cha cho mục tiêu của siêu liên kết cha khi tồn tại. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Trả về khung trong HTML frameset cha cho mục tiêu của siêu liên kết cha khi tồn tại. |
| [getTooltip()](#getTooltip--) | Trả về chuỗi có thể được hiển thị trong giao diện người dùng liên kết với siêu liên kết cha. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Trả về chuỗi có thể được hiển thị trong giao diện người dùng liên kết với siêu liên kết cha. |
| [getHistory()](#getHistory--) | Xác định liệu mục tiêu của siêu liên kết cha có được thêm vào danh sách các siêu liên kết đã xem khi nó được gọi hay không. |
| [setHistory(boolean value)](#setHistory-boolean-) | Xác định liệu mục tiêu của siêu liên kết cha có được thêm vào danh sách các siêu liên kết đã xem khi nó được gọi hay không. |
| [getHighlightClick()](#getHighlightClick--) | Xác định liệu siêu liên kết có được làm nổi bật khi nhấp chuột hay không. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Xác định liệu siêu liên kết có được làm nổi bật khi nhấp chuột hay không. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Xác định liệu âm thanh có được dừng khi nhấp vào siêu liên kết hay không. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Xác định liệu âm thanh có được dừng khi nhấp vào siêu liên kết hay không. |
| [getSound()](#getSound--) | Biểu thị âm thanh đang phát của siêu liên kết. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Biểu thị âm thanh đang phát của siêu liên kết. |
| [getColorSource()](#getColorSource--) | Biểu thị nguồn màu của siêu liên kết - hoặc là styles hoặc portion format. |
| [setColorSource(int value)](#setColorSource-int-) | Biểu thị nguồn màu của siêu liên kết - hoặc là styles hoặc portion format. |
| [equals(Object obj)](#equals-java.lang.Object-) | Xác định liệu hai đối tượng Hyperlink có bằng nhau hay không. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Xác định liệu hai đối tượng Hyperlink có bằng nhau hay không. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Kiểm tra hai siêu liên kết có bằng nhau hay không. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Kiểm tra hai siêu liên kết không bằng nhau. |
| [hashCode()](#hashCode--) | Đóng vai trò như một hàm băm cho một kiểu cụ thể, phù hợp để sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm. |
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

Tạo một thể hiện của siêu liên kết trỏ tới slide cụ thể. Lưu ý: siêu liên kết được tạo phải được gán cho một đối tượng trong cùng bản trình chiếu, nếu không liên kết sẽ được lưu dưới dạng NoAction.

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
| tooltip | java.lang.String | Văn bản chú giải công cụ |
| history | boolean | Xác định liệu mục tiêu của siêu liên kết cha có được thêm vào danh sách các siêu liên kết đã xem khi nó được gọi hay không. |
| stopSoundsOnClick | boolean | Xác định liệu âm thanh có được dừng khi nhấp vào siêu liên kết hay không. |
| highlightClick | boolean | Xác định liệu siêu liên kết có được làm nổi bật khi nhấp chuột hay không. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Phiên bản. Chỉ-đọc long.

**Trả về:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Trả về một siêu liên kết đặc biệt "không làm gì". Chỉ-đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Trả về một siêu liên kết đặc biệt "phát tệp media". Được sử dụng trong AudioFrame và VideoFrame. Chỉ-đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Trả về một siêu liên kết tới slide tiếp theo. Chỉ-đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Trả về một siêu liên kết tới slide trước đó. Chỉ-đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Trả về một siêu liên kết tới slide đầu tiên của bản trình chiếu. Chỉ-đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Trả về một siêu liên kết tới slide cuối cùng của bản trình chiếu. Chỉ-đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Trả về một siêu liên kết tới slide đã xem cuối cùng. Chỉ-đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Trả về một siêu liên kết kết thúc buổi chiếu. Chỉ-đọc [Hyperlink](../../com.aspose.slides/hyperlink).

**Trả về:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Trả về loại hành động của Hyperlink. Chỉ-đọc [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Trả về:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Xác định URL bên ngoài. Chỉ-đọc String.

**Trả về:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Nếu Hyperlink mục tiêu là slide cụ thể, trả về slide này. Chỉ-đọc [ISlide](../../com.aspose.slides/islide).

**Trả về:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Biểu thị một siêu liên kết được đặt cho phần này mà không quan tâm tới nội dung thực tế của phần.

PowerPoint xử lý đặc biệt các liên kết và văn bản tương ứng trong một phần. Nó cho phép tạo văn bản cho siêu liên kết dưới dạng một URL hợp lệ, khác với địa chỉ thực tế của liên kết. Trong trường hợp này, khi bạn xem liên kết trong cửa sổ chỉnh sửa, nó sẽ được thay đổi để khớp với phần văn bản. Thuộc tính này biểu thị giá trị gốc của siêu liên kết.

**Trả về:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Trả về khung trong HTML frameset cha cho mục tiêu của siêu liên kết cha khi tồn tại. Đọc/ghi String.

**Trả về:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Trả về khung trong HTML frameset cha cho mục tiêu của siêu liên kết cha khi tồn tại. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Trả về chuỗi có thể được hiển thị trong giao diện người dùng liên kết với siêu liên kết cha. Đọc/ghi String.

**Trả về:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Trả về chuỗi có thể được hiển thị trong giao diện người dùng liên kết với siêu liên kết cha. Đọc/ghi String.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | java.lang.String |  |
### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Xác định liệu mục tiêu của siêu liên kết cha có được thêm vào danh sách các siêu liên kết đã xem khi nó được gọi hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Xác định liệu mục tiêu của siêu liên kết cha có được thêm vào danh sách các siêu liên kết đã xem khi nó được gọi hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Xác định liệu siêu liên kết có được làm nổi bật khi nhấp chuột hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Xác định liệu siêu liên kết có được làm nổi bật khi nhấp chuột hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Xác định liệu âm thanh có được dừng khi nhấp vào siêu liên kết hay không. Đọc/ghi boolean.

**Trả về:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Xác định liệu âm thanh có được dừng khi nhấp vào siêu liên kết hay không. Đọc/ghi boolean.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | boolean |  |
### getSound() {#getSound--}
```
public final IAudio getSound()
```

Biểu thị âm thanh đang phát của siêu liên kết. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lấy siêu liên kết của hình đầu tiên
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Trích xuất âm thanh siêu liên kết dưới dạng mảng byte
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

Biểu thị âm thanh đang phát của siêu liên kết. Đọc/ghi [IAudio](../../com.aspose.slides/iaudio).

> ``` 
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Lấy siêu liên kết của hình đầu tiên
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Trích xuất âm thanh siêu liên kết dưới dạng mảng byte
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

Biểu thị nguồn màu của siêu liên kết - hoặc là styles hoặc portion format. Đọc/ghi [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Trả về:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Biểu thị nguồn màu của siêu liên kết - hoặc là styles hoặc portion format. Đọc/ghi [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | int |  |
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Xác định liệu hai đối tượng Hyperlink có bằng nhau hay không.

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

Xác định liệu hai đối tượng Hyperlink có bằng nhau hay không.

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

Kiểm tra hai siêu liên kết có bằng nhau hay không.

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

Kiểm tra hai siêu liên kết không bằng nhau.

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

Đóng vai trò như một hàm băm cho một kiểu cụ thể, phù hợp để sử dụng trong các thuật toán băm và cấu trúc dữ liệu như bảng băm.

**Trả về:**
int - Mã băm cho một URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Trả về đối tượng Parent_Immediate. Chỉ-đọc IDOMObject.

**Trả về:**
com.aspose.slides.IDOMObject