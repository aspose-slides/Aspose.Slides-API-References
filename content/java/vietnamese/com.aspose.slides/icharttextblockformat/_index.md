---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Java - Tham chiếu API
description: Đại diện cho các thuộc tính định dạng cho các phần tử văn bản biểu đồ.
type: docs
url: /vi/com.aspose.slides/icharttextblockformat/
---
```
public interface IChartTextBlockFormat
```

Đại diện cho các thuộc tính định dạng cho các phần tử văn bản biểu đồ.

## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Trả về hoặc đặt văn bản neo dọc trong một TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Trả về hoặc đặt văn bản neo dọc trong một TextFrame. |
| [getCenterText()](#getCenterText--) | Nếu NullableBool.True thì văn bản nên được căn giữa theo chiều ngang trong ô. |
| [setCenterText(byte value)](#setCenterText-byte-) | Nếu NullableBool.True thì văn bản nên được căn giữa theo chiều ngang trong ô. |
| [getTextVerticalType()](#getTextVerticalType--) | Xác định hướng văn bản. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Xác định hướng văn bản. |
| [getMarginLeft()](#getMarginLeft--) | Trả về hoặc đặt lề trái (điểm) trong một TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Trả về hoặc đặt lề trái (điểm) trong một TextFrame. |
| [getMarginRight()](#getMarginRight--) | Trả về hoặc đặt lề phải (điểm) trong một TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Trả về hoặc đặt lề phải (điểm) trong một TextFrame. |
| [getMarginTop()](#getMarginTop--) | Trả về hoặc đặt lề trên (điểm) trong một TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Trả về hoặc đặt lề trên (điểm) trong một TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Trả về hoặc đặt lề dưới (điểm) trong một TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Trả về hoặc đặt lề dưới (điểm) trong một TextFrame. |
| [getWrapText()](#getWrapText--) | Đúng nếu văn bản được cuộn ở các lề của TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Đúng nếu văn bản được cuộn ở các lề của TextFrame. |
| [getAutofitType()](#getAutofitType--) | Trả về hoặc đặt chế độ tự động vừa văn bản. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Trả về hoặc đặt chế độ tự động vừa văn bản. |
| [getRotationAngle()](#getRotationAngle--) | Xác định góc xoay tùy chỉnh được áp dụng cho văn bản trong hộp giới hạn. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Xác định góc xoay tùy chỉnh được áp dụng cho văn bản trong hộp giới hạn. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Trả về hoặc đặt văn bản neo dọc trong một TextFrame. Đọc/ghi [TextAnchorType](../../com.aspose.slides/textanchortype).

**Trả về:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Trả về hoặc đặt văn bản neo dọc trong một TextFrame. Đọc/ghi [TextAnchorType](../../com.aspose.slides/textanchortype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Nếu NullableBool.True thì văn bản nên được căn giữa theo chiều ngang trong ô. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Nếu NullableBool.True thì văn bản nên được căn giữa theo chiều ngang trong ô. Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Xác định hướng văn bản. Giá trị kết quả của góc xoay văn bản trực quan được tóm tắt từ thuộc tính này và góc tùy chỉnh trong thuộc tính RotationAngle. Đọc/ghi [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Trả về:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Xác định hướng văn bản. Giá trị kết quả của góc xoay văn bản trực quan được tóm tắt từ thuộc tính này và góc tùy chỉnh trong thuộc tính RotationAngle. Đọc/ghi [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Trả về hoặc đặt lề trái (điểm) trong một TextFrame. Thay đổi thuộc tính này có thể ảnh hưởng chỉ đến các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có ảnh hưởng khi hiển thị). Đọc/ghi double.

**Trả về:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Trả về hoặc đặt lề trái (điểm) trong một TextFrame. Thay đổi thuộc tính này có thể ảnh hưởng chỉ đến các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có ảnh hưởng khi hiển thị). Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Trả về hoặc đặt lề phải (điểm) trong một TextFrame. Thay đổi thuộc tính này có thể ảnh hưởng chỉ đến các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có ảnh hưởng khi hiển thị). Đọc/ghi double.

**Trả về:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Trả về hoặc đặt lề phải (điểm) trong một TextFrame. Thay đổi thuộc tính này có thể ảnh hưởng chỉ đến các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có ảnh hưởng khi hiển thị). Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Trả về hoặc đặt lề trên (điểm) trong một TextFrame. Thay đổi thuộc tính này có thể ảnh hưởng chỉ đến các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có ảnh hưởng khi hiển thị). Đọc/ghi double.

**Trả về:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Trả về hoặc đặt lề trên (điểm) trong một TextFrame. Thay đổi thuộc tính này có thể ảnh hưởng chỉ đến các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có ảnh hưởng khi hiển thị). Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Trả về hoặc đặt lề dưới (điểm) trong một TextFrame. Thay đổi thuộc tính này có thể ảnh hưởng chỉ đến các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có ảnh hưởng khi hiển thị). Đọc/ghi double.

**Trả về:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Trả về hoặc đặt lề dưới (điểm) trong một TextFrame. Thay đổi thuộc tính này có thể ảnh hưởng chỉ đến các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có ảnh hưởng khi hiển thị). Đọc/ghi double.

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Đúng nếu văn bản được cuộn ở các lề của TextFrame. Thay đổi thuộc tính này có thể ảnh hưởng chỉ đến các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2007/2013). Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Trả về:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Đúng nếu văn bản được cuộn ở các lề của TextFrame. Thay đổi thuộc tính này có thể ảnh hưởng chỉ đến các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2007/2013). Đọc/ghi [NullableBool](../../com.aspose.slides/nullablebool).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Trả về hoặc đặt chế độ tự động vừa văn bản. Thay đổi thuộc tính này có thể ảnh hưởng chỉ đến các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có ảnh hưởng khi hiển thị). Đọc/ghi [TextAutofitType](../../com.aspose.slides/textautofittype).

**Trả về:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Trả về hoặc đặt chế độ tự động vừa văn bản. Thay đổi thuộc tính này có thể ảnh hưởng chỉ đến các phần biểu đồ sau: DataLabel và DataLabelFormat (hỗ trợ đầy đủ trong PowerPoint 2013; trong PowerPoint 2007 không có ảnh hưởng khi hiển thị). Đọc/ghi [TextAutofitType](../../com.aspose.slides/textautofittype).

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Xác định góc xoay tùy chỉnh được áp dụng cho văn bản trong hộp giới hạn. Nếu không được chỉ định, góc xoay của hình dạng kèm theo sẽ được sử dụng. Nếu được chỉ định, thì góc này được áp dụng độc lập với hình dạng. Nghĩa là hình dạng có thể có một góc xoay được áp dụng thêm vào góc xoay đã áp dụng cho văn bản. Giá trị cuối cùng của góc xoay văn bản trực quan được tóm tắt từ thuộc tính này và loại dọc định trước trong thuộc tính TextVerticalType. Đọc/ghi float.

--------------------

> ```
> Xem xét trường hợp một hình có góc quay 90 độ theo chiều kim đồng hồ được áp dụng cho nó. 
>  Thêm vào đó, phần văn bản tự nó có góc quay -90 độ 
>  ngược chiều kim đồng hồ được áp dụng cho nó. Khi đó, hình tạo ra sẽ có vẻ
>  được quay nhưng văn bản bên trong nó sẽ có vẻ như không bị quay cả.
> ```


**Trả về:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Xác định góc xoay tùy chỉnh được áp dụng cho văn bản trong hộp giới hạn. Nếu không được chỉ định, góc xoay của hình dạng kèm theo sẽ được sử dụng. Nếu được chỉ định, thì góc này được áp dụng độc lập với hình dạng. Nghĩa là hình dạng có thể có một góc xoay được áp dụng thêm vào góc xoay đã áp dụng cho văn bản. Giá trị cuối cùng của góc xoay văn bản trực quan được tóm tắt từ thuộc tính này và loại dọc định trước trong thuộc tính TextVerticalType. Đọc/ghi float.

--------------------

> ```
> Xem xét trường hợp một hình có góc quay 90 độ theo chiều kim đồng hồ được áp dụng cho nó. 
>  Thêm vào đó, phần văn bản tự nó có góc quay -90 độ 
>  ngược chiều kim đồng hồ được áp dụng cho nó. Khi đó, hình tạo ra sẽ có vẻ
>  được quay nhưng văn bản bên trong nó sẽ có vẻ như không bị quay chút nào.
> ```


**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| value | float |  |